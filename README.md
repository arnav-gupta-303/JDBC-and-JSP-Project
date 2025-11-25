# 📚 JDBC and JSP Project

A simple **Student Management System** built using **JSP**, **JDBC**, and **MySQL**.  
This project demonstrates how to perform **CRUD operations** using both a **JSP webpage** and a **Java JDBC console application**.

---

## 🌐 Live on Localhost

Once deployed on Tomcat, open:

http://localhost:8080/jdbc-demo-1.0-SNAPSHOT/index.jsp


This JSP page will fetch and display all students from the database.

---

## 🚀 Features

### ✔ JSP Page
- Connects to MySQL database  
- Runs SQL queries  
- Displays student records in an HTML table  

### ✔ Java JDBC Console App
Contains functions for CRUD operations:

| Method | Description |
|--------|-------------|
| `insertStudent()` | Insert a new student |
| `selectStudent()` | Fetch and print all students |
| `updateStudent()` | Update student name/email |
| `deleteStudent()` | Delete student by ID |

---

## 🗄 Database Setup

Create database:

```sql
CREATE DATABASE demo;
CREATE TABLE student (
  id INT PRIMARY KEY AUTO_INCREMENT,
  name VARCHAR(100),
  email VARCHAR(100)
);
