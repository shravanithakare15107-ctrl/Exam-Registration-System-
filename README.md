🎓 Exam Registration System

A desktop-based Exam Registration System developed using Python, Tkinter, and MySQL.

📌 Project Overview

The Exam Registration System is designed to digitally manage student exam registration records.

The system provides:

- 🔐 User Login
- 📝 Add Exam Registration
- 📋 View Registrations
- 🔎 Search Registration
- ✏️ Update Registration
- 🗑️ Delete Registration
- 🔄 Clear / Reset Form
- ✅ Input Validation
- 💾 MySQL Database Storage
- 🚪 Logout

🛠️ Technologies Used

- Python — Application logic
- Tkinter — Graphical User Interface
- MySQL — Database management
- mysql-connector-python — Python-MySQL connection

📋 Registration Details

The system stores:

- Registration ID
- Student Name
- Roll Number
- Branch
- Semester
- Exam Type
- Subject
- Exam Date
- Email
- Phone Number

🗄️ Database

Database Name:

exam_registration_db

Tables

users

- username
- password

registrations

- registration_id
- student_name
- roll_no
- branch
- semester
- exam_type
- subject
- exam_date
- email
- phone

🔄 CRUD Operations

Operation| Function
Create| Add a new exam registration
Read| View and search registrations
Update| Modify registration details
Delete| Remove a registration

🚀 How to Run

1. Install Python

Make sure Python is installed on your computer.

2. Install MySQL Connector

Open the VS Code terminal and run:

pip install mysql-connector-python

3. Create the Database

Create the database:

exam_registration_db

Create the required "registrations" table according to the fields used in the project.

4. Configure MySQL

Open "exam_registration_system.py" and configure:

DB_USER = "root"
DB_PASSWORD = "YOUR_MYSQL_PASSWORD"

Replace "YOUR_MYSQL_PASSWORD" with your own MySQL password when running the project.

⚠️ Never upload your real MySQL password to GitHub.

5. Run the Application

python exam_registration_system.py

🔐 Default Application Login

Username: admin
Password: admin123

«This is the application login, not your MySQL password.»

📂 Project Structure

Exam-Registration-System/
│
└── exam_registration_system.py

🎯 Project Objective

The main objective of this project is to create a simple and user-friendly system for managing student examination registrations while demonstrating Python GUI development and MySQL database management.

👩‍💻 Developed By

Shravani B. Thakare

Branch: AI&DS

Project: Exam Registration System
