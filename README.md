**Online Voting System**

A secure and user-friendly platform for online elections


🧾**Overview**

The Online Voting System is a web-based application designed to simplify the voting process while ensuring security and transparency. Voters can securely cast their votes from anywhere, and election administrators can manage and monitor the voting process in real-time.


🦾**Features**

  User Authentication: Secure login system for voters and admins.

  Secure Voting: AES encryption guarantees vote security and confidentiality.

  Admin Dashboard: Manage elections, voters, and view real-time results.

  Responsive UI: Mobile-friendly and accessible from any device.


💻**Technologies Used**


  Backend: Python (Flask)

  Frontend: HTML, CSS, JavaScript

  Database: SQL (PostgreSQL/MySQL)

  Encryption: Advanced Encryption Standard (AES)


📐**Setup & Installation**

  Prerequisites

  Python 3.x

  PostgreSQL or MySQL

  A virtual environment tool (optional)

🏃‍♂️**Steps to Run Locally**🏃‍♂️
Clone the repository:

git clone https://github.com/your-username/online-voting-system.git

Navigate to the project directory:

cd online-voting-system

Create a virtual environment (optional):

python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Set up the database in config.py:

DATABASE_URI = 'your-database-uri'

Run the application:

python run.py

Open http://127.0.0.1:5000/ in your browser to view the app.
