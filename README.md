# Assignment - PostgreSQL Query Execution

## Student Information
- **Student ID:** 27881
- **Name:** Nkurunziza Fiacre
- **Departement:** Networking
- **Course:** Database Management System

# 📊 PostgreSQL Employee & Project Management Database

A hands-on SQL project using **PostgreSQL** that explores over 50 practical queries using **String**, **Numeric**, **Date/Time**, and **Conditional** functions. This project is ideal for students, developers, and data analysts looking to strengthen their SQL skills with real-world examples and clean query logic.

---

## 🧠 What You’ll Learn

- How to write advanced SQL queries in PostgreSQL.
- Effective use of SQL **string manipulation**, **math operations**, **date calculations**, and **conditional logic**.
- Realistic query design for employee and project management databases.
- Best practices in SQL formatting and data function usage.

---

## 🧠 Project Overview

This database simulates a simplified **Employee Management System** for a tech company. It includes:

- Employee records with personal and job information
- Departments and their mappings
- Projects (ongoing and completed)
- Employee-Project assignments (many-to-many)

It’s designed to practice and demonstrate SQL functions through **String manipulation**, **Numeric calculations**, **Date/time operations**, and **Conditional logic** using real-world business cases.

---

## ⚙️ Technologies Used

- PostgreSQL 14+
- SQL (PostgreSQL dialect)
- pgAdmin / DBeaver (recommended for query visualization)
- GitHub for version control

---

## 🗂️ Database Schema

The project includes four main tables:

| Table               | Description                            |
|--------------------|----------------------------------------|
| `employees`         | Stores employee info (names, salary, gender, etc.) |
| `departments`       | Holds department names and IDs         |
| `projects`          | Details of projects (name, start, end) |
| `employee_projects` | Links employees with assigned projects |

Relationships:
- `employees.department_id → departments.department_id`
- `employee_projects` serves as a join table for the many-to-many relationship between `employees` and `projects`.

---

## 🧪 Sample Queries (From Exercises)

- `String Functions`: Concatenation, trimming, casing, substring, replacing
- <img width="1366" height="768" alt="1 (4)" src="https://github.com/user-attachments/assets/cb57bc64-11f2-4a4d-9427-d2eba3f6f973" />


- <img width="1366" height="768" alt="Screenshot (536)" src="https://github.com/user-attachments/assets/2298accc-b27b-4e7e-8a95-61e688fbf2db" />


- `Numeric Functions`: MOD, ROUND, ABS, POWER
- <img width="1366" height="768" alt="Screenshot (553)" src="https://github.com/user-attachments/assets/fce437c7-f327-428d-9fcc-5839085277fb" />

- <img width="1366" height="768" alt="Screenshot (552)" src="https://github.com/user-attachments/assets/14ae91bc-7295-4cb4-97c7-f42bd88a957d" />


- `Date/Time`: CURRENT_DATE, DATEDIFF, YEAR, MONTH, DAY
- <img width="1366" height="768" alt="Screenshot (560)" src="https://github.com/user-attachments/assets/611794e5-013e-48a3-96b0-e23c051491f8" />
- <img width="1366" height="768" alt="1 (30)" src="https://github.com/user-attachments/assets/1fbfca77-553c-49f1-9a3e-e99c94e9956c" />


  
- `Conditional`: CASE, COALESCE, Nested logic
- <img width="1366" height="768" alt="1 (47)" src="https://github.com/user-attachments/assets/d2d7b45b-8127-4550-a577-2d979c422fcc" />

- <img width="1366" height="768" alt="1 (42)" src="https://github.com/user-attachments/assets/817b92b4-2e30-4491-99f4-f8997e149d56" />




- `Joins & Aggregations`: Employee-project mappings, department-based logic
- <img width="1366" height="768" alt="Screenshot (574)" src="https://github.com/user-attachments/assets/a620f16c-78dc-43f1-8a7a-93cb6fadd495" />
- <img width="1366" height="768" alt="Screenshot (573)" src="https://github.com/user-attachments/assets/6426c6f9-737a-4813-87ac-62815eefb966" />


Over **50 SQL queries** included in `exercise_queries.sql` to test all edge cases and business scenarios.

---

## 🚀 Getting Started

### 🔧 Prerequisites

- PostgreSQL installed 
- Basic knowledge of SQL


**📌 Author:**  **Nkurunziza Fiacre**
**📚 Course:** Database Management System






