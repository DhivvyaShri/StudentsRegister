# Student Registration System (Java + JDBC)

## Description
This project is a Java console application that allows users to enter student
details and store them in a MySQL database using JDBC.

## Objective
To demonstrate JDBC concepts such as database connection, PreparedStatement,
secure data insertion, and transaction handling.

## Technologies Used
- Java
- JDBC
- MySQL
- Eclipse IDE

## Project Structure
- StudentRegistration.java
- MySQL Connector/J
- Database: college
- Table: students

## Database Schema
```sql
CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50),
    roll INT,
    dept VARCHAR(50)
);
