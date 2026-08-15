# 🎓 Student Career Database – SQL Project

## 📌 Project Overview

The **Student Career Database** is a MySQL-based SQL project designed to store, manage, and analyze student academic, career, skill, and placement information.

This project demonstrates the use of SQL concepts such as **database creation, table creation, data insertion, filtering, sorting, aggregation, grouping, subqueries, CTEs, CASE statements, and window functions**.

The project contains **50 SQL queries** covering beginner to advanced SQL operations.

---

## 🗄️ Database Details

**Database Name:** `student`

**Main Table:** `StudentCareer`

The `StudentCareer` table stores information related to:

* Student details
* Academic performance
* Internships and experience
* Career interests
* Job goals
* Salary expectations
* Preferred locations
* Technical skills
* Soft skills
* Certifications
* LinkedIn and hackathon participation
* English proficiency
* Placement status

---

## 📊 Table Structure

| Column                  | Description                   |
| ----------------------- | ----------------------------- |
| Student_ID              | Unique student ID             |
| Student_Name            | Student name                  |
| Age                     | Student age                   |
| Gender                  | Gender                        |
| Qualification           | Educational qualification     |
| Department              | Department                    |
| CGPA                    | Academic CGPA                 |
| Backlogs                | Number of backlogs            |
| Experience_Years        | Years of experience           |
| Internships             | Number of internships         |
| Hobby                   | Student hobby                 |
| Interest                | Area of interest              |
| Field_of_Interest       | Preferred career field        |
| Job_Goal                | Target job role               |
| Preferred_Location      | Preferred work location       |
| Expected_Salary         | Expected annual salary        |
| Preferred_Company_Type  | Preferred company type        |
| Preferred_Work_Mode     | Remote, Hybrid, or Office     |
| Subject_Knowledge       | Subject knowledge level       |
| Programming_Skill       | Programming skill level       |
| Communication_Skill     | Communication skill level     |
| Leadership_Skill        | Leadership skill level        |
| Certifications          | Number of certifications      |
| LinkedIn_Profile        | LinkedIn profile availability |
| Hackathon_Participation | Hackathon participation       |
| English_Proficiency     | English proficiency level     |
| Placement_Status        | Current placement status      |

---

## 🔍 SQL Concepts Covered

### Basic SQL

* `CREATE DATABASE`
* `CREATE TABLE`
* `INSERT INTO`
* `SELECT`
* `DISTINCT`

### Filtering

* `WHERE`
* `BETWEEN`
* `IN`
* `LIKE`
* Comparison operators
* `AND`

### Sorting & Limiting

* `ORDER BY`
* `ASC`
* `DESC`
* `LIMIT`

### Aggregate Functions

* `COUNT()`
* `AVG()`
* `MAX()`
* `MIN()`
* `SUM()`
* `ROUND()`

### Grouping

* `GROUP BY`
* `HAVING`

### Conditional Logic

* `CASE`
* CGPA categorization
* Experience categorization
* Salary categorization

### Window Functions

* `ROW_NUMBER()`
* `RANK()`
* `PARTITION BY`

### Advanced SQL

* Subqueries
* Common Table Expressions (CTEs)
* Correlated subqueries

---

## 🎯 Project Objectives

* Practice SQL from basic to advanced level.
* Analyze student academic performance.
* Understand student career preferences.
* Analyze expected salary trends.
* Identify placement-related patterns.
* Practice grouping and aggregation.
* Understand SQL window functions.
* Apply subqueries and CTEs to real-world-style data.
* Develop practical database analysis skills.

---

## 💡 Key Learning Outcomes

Through this project, I strengthened my understanding of:

* Relational database concepts
* MySQL syntax
* Data filtering and sorting
* Aggregate functions
* Grouping and conditional analysis
* Subqueries and CTEs
* Window functions
* Career and placement data analysis
* Writing structured and analytical SQL queries

---

## 🛠️ Technologies Used

* **Database:** MySQL
* **Language:** SQL
* **Tools:** MySQL Workbench / MySQL Server
* **Version Control:** Git & GitHub

---

## 📁 Project Structure

```text
Student-Career-SQL/
│
├── Student_Career.sql
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Create the database

```sql
CREATE DATABASE student;
USE student;
```

### 2. Create the table

Run the `CREATE TABLE StudentCareer` statement from the SQL file.

### 3. Insert the data

Execute the `INSERT INTO StudentCareer` statements.

### 4. Run the queries

Execute the 50 SQL queries individually to analyze the student career dataset.

---

## 📌 Sample Analysis

The project can be used to answer questions such as:

* Which students have a CGPA above 8?
* Which department has the highest average CGPA?
* What is the average expected salary for each job goal?
* Which location is most preferred by students?
* Who are the top students based on CGPA?
* Which students have advanced programming skills?
* What is the most popular career goal?
* Which students have salary expectations above their department average?

---

## 👩‍💻 Author

**Nafeela Beer**

Aspiring Data Analyst | SQL | Python | Machine Learning | Generative AI

---

## ⭐ Future Improvements

Possible future enhancements include:

* Adding more student records
* Creating multiple related tables
* Adding primary and foreign key relationships
* Performing JOIN-based analysis
* Creating views and stored procedures
* Connecting the database to Power BI
* Building dashboards for student career and placement analysis

---

⭐ **If you find this project useful, feel free to explore the repository and give it a star!**
