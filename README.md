📊 DataTalk – Talk with Your Data

An intelligent platform to query, analyze, and interact with your database in natural language.
Built with Flask, MySQL, and LLM-powered insights.

✨ Features

🔍 Natural Language to SQL – Ask questions in plain English, get SQL queries generated.

📈 Data Insights – Automatically fetch insights and return results in an easy-to-read format.

⚡ REST API Support – Access insights programmatically via endpoints.

🔐 Secure Connection – Environment-based credentials for database access.

🌐 Cross-Origin Support – Enabled with CORS for frontend integration.

🏗️ Tech Stack

Backend: Flask, Python

Database: MySQL / MariaDB

ORM / Parsing: SQLParse

Security: dotenv, certifi

Frontend Ready: CORS enabled

🚀 Getting Started

Follow these steps to set up the project locally.

1️⃣ Clone the Repository
git clone https://github.com/indrajitdey/DataTalk-talk-with-your-data.git
cd DataTalk-talk-with-your-data

2️⃣ Create Virtual Environment
python -m venv .venv
source .venv/bin/activate   # On Linux/Mac
.venv\Scripts\activate      # On Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Configure Environment Variables

Create a .env file in the project root:

SQL_USER=your_username
SQL_PASSWORD=your_password
SQL_HOST=localhost
SQL_DATABASE=your_db_name
API_KEY=your_api_key   # if needed

5️⃣ Run the Application
python app.py


Server will start at:
👉 http://127.0.0.1:5000/

📡 API Endpoints
Method	Endpoint	Description
POST	/query	Send natural language query → SQL
GET	/health	Check if API is running
POST	/execute	Run SQL query on connected database

(Add more here depending on your routes)

📂 Project Structure
├── app.py              # Main Flask app
├── schema.py           # Database schema handler
├── requirements.txt    # Dependencies
├── templates/          # HTML templates (if used)
├── static/             # Static files (CSS, JS)
└── .env.example        # Example environment variables

🤝 Contributing

Contributions are welcome!

Fork the repo

Create a new branch (feature/awesome-feature)

Commit your changes

Open a Pull Request 🚀

🛡️ License

This project is licensed under the MIT License.

💡 Author

👤 Indrajit Dey

GitHub: @indrajitdey

LinkedIn: [Your LinkedIn Profile]

✨ Now you can literally talk with your data! ✨
