# 📊 SQL Learning Repository

![SQL](https://img.shields.io/badge/SQL-Learning-blue?style=for-the-badge&logo=mysql&logoColor=white)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Progress-green?style=for-the-badge)

## 👋 About This Repository

Welcome to my SQL Learning Repository!

I am learning SQL from the basics and practicing queries to improve my database management, logical thinking, and problem-solving skills.

This repository contains SQL commands, practice programs, examples, and interview preparation questions. I will continuously update it as I learn new concepts.

## 🎯 Objectives

- Learn SQL from beginner to advanced level.
- Understand relational databases and tables.
- Practice SQL queries with real-world examples.
- Learn to retrieve, filter, sort, and manipulate data.
- Understand database relationships and joins.
- Prepare for technical interviews and placement opportunities.
- Build a strong foundation for Data Analyst and Software Developer roles.

## 🛠️ Technologies Used

- **SQL:** Structured Query Language
- **MySQL:** Relational Database Management System
- **Git:** Version Control
- **GitHub:** Code Repository
- **Online SQL Editors:** Query Practice

## 📚 SQL Learning Roadmap

### 1. SQL Fundamentals

- Introduction to SQL
- Introduction to databases
- DBMS vs RDBMS
- Types of SQL commands
- Creating databases using `CREATE DATABASE`
- Creating tables using `CREATE TABLE`
- Inserting records using `INSERT INTO`
- Retrieving records using `SELECT`

### 2. Data Filtering and Sorting

- `WHERE`
- `DISTINCT`
- `ORDER BY`
- `LIMIT`
- `AND`
- `OR`
- `NOT`
- `IN`
- `BETWEEN`
- `LIKE`
- `IS NULL`
- `IS NOT NULL`

### 3. Data Manipulation

- `INSERT`
- `UPDATE`
- `DELETE`
- `ALTER TABLE`
- `DROP TABLE`
- `TRUNCATE TABLE`

### 4. SQL Constraints

- `PRIMARY KEY`
- `FOREIGN KEY`
- `UNIQUE`
- `NOT NULL`
- `CHECK`
- `DEFAULT`
- `AUTO_INCREMENT`

### 5. SQL Operators

- Arithmetic Operators
- Comparison Operators
- Logical Operators
- Special Operators

### 6. SQL Functions

**Aggregate Functions**
- `COUNT()`
- `SUM()`
- `AVG()`
- `MIN()`
- `MAX()`

**String Functions**
- `UPPER()`
- `LOWER()`
- `LENGTH()`
- `CONCAT()`
- `SUBSTRING()`

**Other Functions**
- Date and Time Functions
- Numeric Functions
- Conditional Expressions using `CASE`

### 7. Grouping Data

- `GROUP BY`
- `HAVING`
- Aggregate Functions with Grouping

### 8. SQL Joins

- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`
- `CROSS JOIN`
- Self Join

### 9. Advanced SQL

- Subqueries
- Nested Queries
- Common Table Expressions (CTEs)
- Views
- Indexes
- Window Functions
- Stored Procedures
- Transactions
- Normalization

## 💻 Sample SQL Programs

### Create a Database

```sql
CREATE DATABASE CollegeDB;
```

### Create a Students Table

```sql
CREATE TABLE Students (
    ID INT PRIMARY KEY,
    Name VARCHAR(50),
    Age INT,
    City VARCHAR(50)
);
```

### Insert Records

```sql
INSERT INTO Students (ID, Name, Age, City)
VALUES
(1, 'Arun', 21, 'Chennai'),
(2, 'Priya', 22, 'Karur'),
(3, 'Kumar', 20, 'Coimbatore'),
(4, 'Divya', 21, 'Chennai');
```

### Display All Records

```sql
SELECT * FROM Students;
```

### Filter Records Using WHERE

```sql
SELECT *
FROM Students
WHERE City = 'Chennai';
```

### Display Unique Cities

```sql
SELECT DISTINCT City
FROM Students;
```

### Display Cities Except Chennai

```sql
SELECT DISTINCT City
FROM Students
WHERE City <> 'Chennai';
```

### Sort Students by Age

```sql
SELECT *
FROM Students
ORDER BY Age ASC;
```

### Update a Record

```sql
UPDATE Students
SET City = 'Madurai'
WHERE ID = 2;
```

### Delete a Specific Record

```sql
DELETE FROM Students
WHERE ID = 4;
```

## 📂 Repository Structure

```text
SQL-Learning/
│
├── README.md
│
├── 01_SQL_Basics.sql
├── 02_Create_Table.sql
├── 03_Insert_Records.sql
├── 04_Select_Queries.sql
├── 05_Where_Clause.sql
├── 06_Distinct_Queries.sql
├── 07_Order_By.sql
├── 08_Operators.sql
├── 09_Update_Delete.sql
├── 10_Alter_Table.sql
├── 11_Aggregate_Functions.sql
├── 12_Group_By_Having.sql
├── 13_SQL_Joins.sql
├── 14_Subqueries.sql
└── 15_Interview_Questions.sql
```

*Note: This is a suggested folder structure. Add these files as you create and practice the corresponding SQL queries.*

## 📈 Learning Progress

- [x] Introduction to SQL
- [x] CREATE TABLE
- [x] INSERT INTO
- [x] SELECT
- [x] WHERE
- [x] DISTINCT
- [ ] ORDER BY and LIMIT
- [ ] SQL Operators
- [ ] UPDATE and DELETE
- [ ] Aggregate Functions
- [ ] GROUP BY and HAVING
- [ ] SQL Joins
- [ ] Subqueries
- [ ] Advanced SQL
- [ ] SQL Interview Questions
- [ ] SQL Mini Project

*Update this checklist as you complete each topic.*

## 🧠 What I Am Learning

Through this repository, I am developing the ability to:

- Write SQL queries efficiently.
- Retrieve specific information from databases.
- Filter and organize data.
- Modify database records safely.
- Understand relationships between tables.
- Solve database-related problems.
- Apply SQL concepts to real-world datasets.

## 🚀 Future Plans

- Complete the SQL learning roadmap.
- Practice SQL interview questions.
- Work with real-world datasets.
- Build a database mini project.
- Learn advanced SQL for data analysis.
- Integrate SQL with Python and Power BI.

## 🤝 Connect With Me

**GitHub:** https://github.com/YourUsername

**LinkedIn:** Add your LinkedIn profile URL here.

## ⭐ Support

If you find this repository helpful, consider giving it a star ⭐.

Thank you for visiting my SQL Learning Repository!

---

**Learning SQL one query at a time! 🚀**
