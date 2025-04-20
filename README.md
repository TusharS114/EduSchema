# EduSchema
EduSchema - Educational DBMS Project
EduSchema is a simple educational database management system built using Python, MySQL, and Tkinter. It allows you to perform CRUD operations on Courses, Students, Instructors, Enrollments, Assessments, and Grades through a graphical user interface

Features:
1. Add, update, delete, and view data for all entities
2. Archive deleted records for backup
3. Easy-to-use GUI with Tkinter
4. MySQL database connection

Files
1. main.py - GUI interface using Tkinter
2. crud_operations.py - Functions to perform CRUD operations
3. database.py - Database connection setup
4. EduSchema.sql - SQL script to create tables and schema

How to Run
1. Set up a MySQL database named eduschema and run the EduSchema.sql script.
2. Update your MySQL credentials in database.py.
3. Install MySQL connector: pip install mysql-connector-python
4. Run the app: python main.py

Requirements
1. Python 3.x
2. MySQL Server
3. mysql-connector-python

Notes
This project is for learning purposes. Feel free to modify and improve it!
