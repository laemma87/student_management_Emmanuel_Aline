# student_management_Emmanuel_Aline
<?php
/*
README - Student Management Application 


Project Title:
Development of a PHP Desktop/ Web CRUD Application Using OOP and Database

Group Members:
- Emmanuel – Reg No: 24RP03266
- Aline – Reg No: 24RP03478

Short Description:
This project is a web-based PHP application for managing student records.
It uses Object-Oriented Programming principles, MySQL database connectivity,
and provides a clean interface to perform CRUD (Create, Read, Update, Delete) operations.

Features:
- Add Student: Insert new student records with validation.
- View Students: Display all students in a table.
- Update Student: Modify existing student information.
- Delete Student: Remove a student record.
- Clear Form: Clear all input fields.
- Data Validation: Email and phone fields validated using PHP Regex.
- Interactive GUI: User-friendly interface with HTML tables for data display.

Technical Requirements:
- PHP 8.x
- MySQL database
- OOP structure: Encapsulation, Abstraction, and Interfaces
- Proper error and exception handling
- HTML, CSS, and optionally JavaScript for better UI

Database Setup:
1. Install MySQL and create a database.
2. Run the included `students.sql` file to create the students table:
    
    CREATE DATABASE student_db;
    USE student_db;

    CREATE TABLE students (
        id INT PRIMARY KEY AUTO_INCREMENT,
        firstname VARCHAR(50) NOT NULL,
        lastname VARCHAR(50) NOT NULL,
        email VARCHAR(100) NOT NULL,
        phone VARCHAR(15) NOT NULL
    );

Running the Application:
1. Clone or fork this repository:
   https://github.com/YourUsername/StudentManagementApp-Emmanuel-Aline
2. Open the project in a PHP-compatible server (XAMPP, WAMP, or Laragon).
3. Make sure the MySQL server is running.
4. Access `index.php` in your browser.
5. Perform CRUD operations using the web interface.

Folder Structure:
/project_root
 ├─ /model       → Student.php
 ├─ /db          → DBConnection.php
 ├─ /service     → StudentService.php, StudentServiceImpl.php
 └─ /ui          → index.php, add_student.php, update_student.php

Notes:
- Ensure the database credentials in DBConnection.php match your MySQL setup.
- All CRUD operations use prepared statements to prevent SQL injection.
- Input validation ensures correct email and phone formats.
- Proper exception handling prevents runtime errors.
*/
?>
