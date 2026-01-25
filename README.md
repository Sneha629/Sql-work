📚 Student Database Project (MySQL)
📌 Project Description

This project demonstrates basic SQL operations using MySQL.
It covers creating a database, creating a table, inserting records, and retrieving data using SELECT queries.

🗄️ Database Used

Database Name: eflowdatabase

📋 Table Structure
Table Name: students
Column Name	Data Type	Description
id	INT	Primary key, unique student ID
name	VARCHAR(50)	Student name
age	INT	Student age
email	VARCHAR(100)	Student email address
🛠️ SQL Commands Used
1️⃣ Create Database
CREATE DATABASE eflowdatabase;

2️⃣ Use Database
USE eflowdatabase;

3️⃣ Create Table
CREATE TABLE students (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT,
    email VARCHAR(100)
);

4️⃣ Insert Data
INSERT INTO students (id, name, age, email)
VALUES (1, 'SNEHA', 20, 'SNEHA@GMAIL.COM');

INSERT INTO students (id, name, age, email)
VALUES
(2, 'DIKSHA', 19, 'DIKSHA@'),
(3, 'HARSHIT', 18, 'HARSHIT@');

5️⃣ View Records
SELECT * FROM students;

✅ Output

The students table stores student details such as ID, name, age, and email, and the data can be retrieved using SELECT queries.

🎯 Purpose of Project

Practice basic SQL syntax

Understand database & table creation

Learn INSERT and SELECT operations

Beginner-friendly MySQL project

🧑‍💻 Author

Sneha
