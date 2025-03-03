Secure Flask Application - README

Prerequisites

Before running the application, ensure you have the following installed:

Python 3.7 or later

Virtual Environment (optional but recommended)

SQLite (pre-installed with Python)

Installation Steps

Clone the Repository

git clone <repository-url>
cd <repository-folder>

Create and Activate a Virtual Environment (Recommended)

python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows

Install Dependencies

pip install -r requirements.txt

Set Up the Database

flask db init
flask db migrate -m "Initial migration."
flask db upgrade

Run the Flask Application

flask run

The application will start on http://127.0.0.1:5000/
