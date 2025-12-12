# 📚 All About MySQL - Complete SQL Learning Guide

> A comprehensive guide to SQL and MySQL database concepts in Bangla (বাংলা) and English.  
> 🌟 **Perfect for beginners to advanced developers** | 💡 **Real-world examples** | 🚀 **Interview ready**

[![GitHub stars](https://img.shields.io/github/stars/https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced?style=social)](https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced)
[![GitHub forks](https://img.shields.io/github/forks/https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced?style=social)](https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced/fork)
[![GitHub issues](https://img.shields.io/github/issues/https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced)](https://github.com/https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced/issues)

---

## 📑 Table of Contents

> **💡 Tip:** এই repository টি modular structure এ সাজানো হয়েছে। প্রতিটি topic এর জন্য আলাদা folder রয়েছে যেখানে বিস্তারিত examples এবং explanations দেওয়া আছে।

### 🎯 **Core Concepts**

#### 📖 [Introduction to SQL & MySQL](./docs/01-introduction/README.md)
- SQL কি? | RDBMS কি?
- MySQL Features
- SQL vs NoSQL Databases Comparison
- Basic SQL Syntax
- SQL Keywords Reference
- PostgreSQL Basics

#### 🗄️ [Database Basics](./docs/02-database-basics/README.md)
- CREATE Database
- USE Database
- SHOW Databases
- DROP Database
- Database Information

#### 📊 [Data Types](./docs/03-data-types/README.md)
- Numeric Types (INT, BIGINT, DECIMAL, FLOAT)
- String Types (VARCHAR, TEXT, CHAR)
- Date/Time Types (DATE, DATETIME, TIMESTAMP)
- Binary Types (BLOB, BINARY)

---

### 🔨 **SQL Commands**

#### 🔨 [DDL - Data Definition Language](./docs/04-ddl-commands/README.md)
- CREATE TABLE
- ALTER TABLE
- DROP TABLE
- TRUNCATE TABLE
- RENAME TABLE

#### 📝 [DML - Data Manipulation Language](#dml-commands)
- INSERT INTO
- UPDATE
- DELETE
- Batch Operations

#### 🔍 [DQL - Data Query Language](#dql-commands)
- SELECT Statements
- WHERE Clause
- ORDER BY
- GROUP BY & HAVING
- LIMIT & OFFSET

---

### 🛡️ **Database Features**

#### 🔐 [Constraints](#constraints)
- PRIMARY KEY
- FOREIGN KEY
- UNIQUE
- NOT NULL
- CHECK
- DEFAULT

#### ⚙️ [Operators](#operators)
- Comparison Operators (=, !=, >, <)
- Logical Operators (AND, OR, NOT)
- Special Operators (IN, BETWEEN, LIKE)

#### 📊 [Functions](#functions)
- String Functions
- Numeric Functions
- Date/Time Functions
- Aggregate Functions

---

### 🔗 **Advanced Queries**

#### 🔗 [Joins](./docs/06-joins/README.md)
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN
- CROSS JOIN
- SELF JOIN

#### 🔍 [Subqueries](#subqueries)
- Single-row Subqueries
- Multi-row Subqueries
- Correlated Subqueries
- EXISTS, IN, ANY, ALL

#### 👁️ [Views](#views)
- Creating Views
- Modifying Views
- Updatable Views
- Dropping Views

#### 📋 [Common Table Expressions (CTEs)](#common-table-expressions-ctes)
- Simple CTEs
- Multiple CTEs
- Recursive CTEs
- CTEs with Aggregations

#### 🪟 [Window Functions](#window-functions-advanced-sql)
- ROW_NUMBER(), RANK(), DENSE_RANK()
- LAG(), LEAD()
- FIRST_VALUE(), LAST_VALUE()
- Running Totals & Moving Averages

---

### 🚀 **Performance & Optimization**

#### 📑 [Indexes](#indexes)
- Creating Indexes
- Composite Indexes
- Index Optimization
- When to Use Indexes

#### 💾 [Transactions](#transactions)
- ACID Properties
- BEGIN/START TRANSACTION
- COMMIT & ROLLBACK
- SAVEPOINT
- Isolation Levels

#### 🚀 [Performance Optimization](./docs/07-performance/README.md)
- EXPLAIN & EXPLAIN ANALYZE
- Index Optimization Strategies
- Query Optimization Techniques
- Performance Monitoring
- Slow Query Log

---

### 🔧 **Advanced Features**

#### 🔧 [Stored Procedures & Functions](#stored-procedures)
- Creating Procedures
- IN/OUT Parameters
- Functions vs Procedures

#### ⚡ [Triggers](#triggers)
- BEFORE Triggers
- AFTER Triggers
- INSERT/UPDATE/DELETE Triggers

#### 🔄 [Pivot and Unpivot](#pivot-and-unpivot-operations)
- Dynamic Pivoting
- Unpivot Operations

#### 🔧 [Dynamic SQL](#dynamic-sql)
- PREPARE, EXECUTE, DEALLOCATE
- Dynamic Queries
- Security Considerations

---

### 📚 **Additional Resources**

#### 🎓 [Interview Questions](./docs/08-interview-questions/README.md)
- **500+ Questions** with Answers
- Basic Level Questions
- Intermediate Level Questions
- Advanced Level Questions
- Real-world Scenarios

#### 📚 [Advanced Topics](#advanced-topics)
- Database Replication
- Sharding
- Partitioning

#### 🛠️ [Database Design Best Practices](#database-design-best-practices)
- Normalization (1NF, 2NF, 3NF)
- ER Diagrams
- Schema Design

#### 🔐 [Data Integrity & Security](#data-integrity--security)
- User Management
- GRANT/REVOKE Permissions
- SQL Injection Prevention

#### 📊 [Backup & Recovery](#backup--recovery)
- mysqldump Usage
- Restore Strategies
- Point-in-Time Recovery

#### 💡 [Tips & Tricks](#tips--tricks)
- Performance Tips
- Best Practices
- Common Pitfalls

---

## 🚀 Quick Start

### 1. Clone this repository
```bash
git clone https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced
cd MySQL-Database-Basic-To-Advanced
```

### 2. Navigate to any topic
```bash
# Example: Learn about Joins
cd docs/06-joins
# Open README.md in your preferred editor
```

### 3. Follow along with examples
প্রতিটি section এ complete examples এবং explanations দেওয়া আছে যা আপনি সরাসরি MySQL/PostgreSQL এ run করতে পারবেন।

---

## 📂 Repository Structure

```
AllAboutMySQL/
├── README.md                          # Main documentation (this file)
├── docs/
│   ├── 01-introduction/
│   │   └── README.md                  # SQL & MySQL Introduction
│   ├── 02-database-basics/
│   │   └── README.md                  # Database Operations
│   ├── 03-data-types/
│   │   └── README.md                  # Data Types Reference
│   ├── 04-ddl-commands/
│   │   └── README.md                  # DDL Commands
│   ├── 05-dml-commands/
│   │   └── README.md                  # DML Commands (coming soon)
│   ├── 06-joins/
│   │   └── README.md                  # All About Joins
│   ├── 07-performance/
│   │   └── README.md                  # Performance Optimization
│   ├── 08-interview-questions/
│   │   └── README.md                  # Interview Questions
│   └── ... (more topics)
└── examples/
    ├── sample-database.sql            # Sample database for practice
    └── practice-queries.sql           # Practice exercises
```
---

## 🎯 Introduction to SQL & MySQL {#introduction}

### SQL কি?
**SQL (Structured Query Language)** হলো একটি প্রোগ্রামিং ল্যাঙ্গুয়েজ যা ডাটাবেজ ম্যানেজমেন্টের জন্য ব্যবহার করা হয়।

### RDBMS কি?
**RDBMS (Relational Database Management System)** হলো এমন একটি সিস্টেম যেখানে ডাটা টেবিল আকারে সংরক্ষিত থাকে এবং টেবিলগুলোর মধ্যে সম্পর্ক (Relation) থাকে।

### MySQL Features:
✅ Open Source  
✅ Fast & Reliable  
✅ Supports Large Databases  
✅ Cross-Platform Support  
✅ Security Features

### 🔄 SQL vs NoSQL Databases

#### SQL Databases (Relational)

**বৈশিষ্ট্য:**
- টেবিল-ভিত্তিক কাঠামো (Table-based structure)
- নির্দিষ্ট স্কিমা (Fixed schema)
- ACID properties সমর্থন করে
- Vertical scaling (CPU, RAM বাড়ানো)
- জটিল queries এবং joins সমর্থন করে

**উদাহরণ:**
- MySQL
- PostgreSQL
- Oracle Database
- Microsoft SQL Server
- SQLite

**কখন ব্যবহার করবেন:**
- যখন data structure স্থির
- Complex queries প্রয়োজন
- Transaction integrity গুরুত্বপূর্ণ
- Banking, Finance, E-commerce

#### NoSQL Databases (Non-relational)

**বৈশিষ্ট্য:**
- Document, Key-Value, Graph, Column-family based
- Dynamic schema (নমনীয়)
- BASE properties (Basically Available, Soft state, Eventually consistent)
- Horizontal scaling (বেশি servers যোগ করা)
- Large-scale data এবং high performance

**উদাহরণ:**
- MongoDB (Document)
- Redis (Key-Value)
- Cassandra (Column-family)
- Neo4j (Graph)
- DynamoDB (Key-Value)

**কখন ব্যবহার করবেন:**
- যখন data structure পরিবর্তনশীল
- Large-scale, distributed data
- Real-time applications
- Social media, IoT, Big Data

**তুলনা টেবিল:**

| Feature | SQL | NoSQL |
|---------|-----|-------|
| **Schema** | Fixed, predefined | Dynamic, flexible |
| **Scaling** | Vertical | Horizontal |
| **Query Language** | Standard SQL | Varies by database |
| **Transactions** | Strong ACID | Eventually consistent |
| **Best for** | Complex queries | Large-scale data |
| **Examples** | MySQL, PostgreSQL | MongoDB, Redis |

### 📝 Basic SQL Syntax

```sql
-- Single line comment

/* 
   Multi-line 
   comment 
*/

-- Basic query structure
SELECT column1, column2
FROM table_name
WHERE condition
ORDER BY column1;
```

### 🔑 SQL Keywords

**Must-know SQL Keywords:**

```sql
-- Data Query
SELECT, FROM, WHERE, ORDER BY, GROUP BY, HAVING, LIMIT, OFFSET

-- Data Manipulation
INSERT, UPDATE, DELETE

-- Data Definition
CREATE, ALTER, DROP, TRUNCATE

-- Constraints
PRIMARY KEY, FOREIGN KEY, UNIQUE, NOT NULL, CHECK, DEFAULT

-- Joins
INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN, CROSS JOIN

-- Aggregation
SUM, COUNT, AVG, MIN, MAX

-- Conditional
CASE, WHEN, THEN, ELSE, END, IF, IFNULL, COALESCE, NULLIF

-- Logical Operators
AND, OR, NOT, IN, BETWEEN, LIKE, EXISTS

-- Set Operations
UNION, UNION ALL, INTERSECT, EXCEPT

-- Subqueries
ANY, ALL, SOME

-- Transactions
BEGIN, COMMIT, ROLLBACK, SAVEPOINT

-- Access Control
GRANT, REVOKE

-- Functions
DISTINCT, AS, IS NULL, IS NOT NULL
```

### 🎨 PostgreSQL Basics

**PostgreSQL** হলো একটি powerful, open-source relational database system যা MySQL এর চেয়ে বেশি features সমর্থন করে।

#### PostgreSQL vs MySQL

| Feature | PostgreSQL | MySQL |
|---------|------------|-------|
| **ACID Compliance** | Full | Partial (depends on engine) |
| **JSON Support** | Native JSON & JSONB | Basic JSON |
| **Window Functions** | Excellent | Limited |
| **Inheritance** | ✅ Supports | ❌ No |
| **Full Text Search** | Built-in | Basic |
| **Recursive Queries** | ✅ Advanced | ✅ Basic |

#### PostgreSQL Specific Features

**1️⃣ JSONB Data Type**
```sql
-- Creating table with JSONB
CREATE TABLE products (
    id SERIAL PRIMARY KEY,
    name VARCHAR(100),
    attributes JSONB
);

-- Inserting JSON data
INSERT INTO products (name, attributes) VALUES
('Laptop', '{"brand": "Dell", "ram": "16GB", "storage": "512GB SSD"}'),
('Phone', '{"brand": "Samsung", "ram": "8GB", "camera": "108MP"}');

-- Querying JSON data
SELECT name, attributes->>'brand' AS brand
FROM products;

-- JSON operators
SELECT * FROM products WHERE attributes @> '{"brand": "Dell"}';
```

**2️⃣ Array Data Type**
```sql
-- Creating table with array
CREATE TABLE students (
    id SERIAL PRIMARY KEY,
    name VARCHAR(100),
    subjects TEXT[]
);

-- Inserting array data
INSERT INTO students (name, subjects) VALUES
('Karim', ARRAY['Math', 'Physics', 'Chemistry']),
('Nusrat', ARRAY['Biology', 'Chemistry', 'English']);

-- Querying arrays
SELECT name FROM students WHERE 'Physics' = ANY(subjects);
SELECT name FROM students WHERE subjects @> ARRAY['Math'];
```

**3️⃣ SERIAL Auto-increment**
```sql
-- PostgreSQL uses SERIAL instead of AUTO_INCREMENT
CREATE TABLE employees (
    id SERIAL PRIMARY KEY,
    name VARCHAR(100) NOT NULL
);
```

**4️⃣ RETURNING Clause**
```sql
-- Get inserted/updated data immediately
INSERT INTO employees (name, salary) 
VALUES ('Ahmed', 50000)
RETURNING id, name, salary;

UPDATE employees 
SET salary = salary * 1.1 
WHERE department = 'IT'
RETURNING id, name, salary;
```

**5️⃣ Table Inheritance**
```sql
-- Parent table
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100)
);

-- Child table inherits from parent
CREATE TABLE premium_users (
    subscription_end_date DATE
) INHERITS (users);

-- Querying includes child tables
SELECT * FROM users;  -- Shows both regular and premium users
SELECT * FROM ONLY users;  -- Shows only parent table data
```  

---

## 🗄️ Database Basics {#database-basics}

### Database তৈরি করা

```sql
CREATE DATABASE my_database;
```

### Database ব্যবহার করা

```sql
USE my_database;
```

### সব Database দেখা

```sql
SHOW DATABASES;
```

### Database মুছে ফেলা

```sql
DROP DATABASE my_database;
```

### Database-এর তথ্য দেখা

```sql
SHOW CREATE DATABASE my_database;
```

---

## 📊 Data Types {#data-types}

### Numeric Data Types

| Data Type | Description | Size |
|-----------|-------------|------|
| `TINYINT` | Very small integer | 1 byte |
| `SMALLINT` | Small integer | 2 bytes |
| `MEDIUMINT` | Medium integer | 3 bytes |
| `INT` or `INTEGER` | Standard integer | 4 bytes |
| `BIGINT` | Large integer | 8 bytes |
| `DECIMAL(M,D)` | Fixed-point number | Variable |
| `FLOAT` | Single-precision floating point | 4 bytes |
| `DOUBLE` | Double-precision floating point | 8 bytes |

### String Data Types

| Data Type | Description | Max Size |
|-----------|-------------|----------|
| `CHAR(n)` | Fixed-length string | 255 characters |
| `VARCHAR(n)` | Variable-length string | 65,535 characters |
| `TEXT` | Long text | 65,535 characters |
| `MEDIUMTEXT` | Medium text | 16,777,215 characters |
| `LONGTEXT` | Very long text | 4,294,967,295 characters |
| `ENUM` | Enumeration (predefined list) | 65,535 values |
| `SET` | Set of values | 64 members |

### Date and Time Data Types

| Data Type | Format | Range |
|-----------|--------|-------|
| `DATE` | YYYY-MM-DD | 1000-01-01 to 9999-12-31 |
| `TIME` | HH:MM:SS | -838:59:59 to 838:59:59 |
| `DATETIME` | YYYY-MM-DD HH:MM:SS | 1000-01-01 to 9999-12-31 |
| `TIMESTAMP` | YYYY-MM-DD HH:MM:SS | 1970-01-01 to 2038-01-19 |
| `YEAR` | YYYY | 1901 to 2155 |

### Binary Data Types

| Data Type | Description |
|-----------|-------------|
| `BINARY(n)` | Fixed-length binary |
| `VARBINARY(n)` | Variable-length binary |
| `BLOB` | Binary Large Object |
| `MEDIUMBLOB` | Medium BLOB |
| `LONGBLOB` | Long BLOB |

---

## 🔨 DDL - Data Definition Language {#ddl-commands}

### CREATE TABLE কিভাবে কাজ করে?

**SQL-এ CREATE TABLE ব্যবহার করা হয় একটি নতুন টেবিল তৈরি করতে।**

#### ✅ সাধারণ গঠন (Syntax)

```sql
CREATE TABLE table_name (
    column1 datatype constraints,
    column2 datatype constraints,
    column3 datatype constraints,
    ...
);
```

#### ✅ employees টেবিল তৈরি করা

```sql
CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT, 
    name VARCHAR(50) NOT NULL,
    department VARCHAR(30),
    age INT CHECK (age >= 18),
    salary DECIMAL(10,2),
    join_date DATE
);
```

🔹 **id** → Primary Key (স্বয়ংক্রিয়ভাবে ১, ২, ৩... হবে)  
🔹 **name** → নাম (VARCHAR(50), খালি রাখা যাবে না)  
🔹 **department** → বিভাগ (VARCHAR(30), খালি রাখা যাবে)  
🔹 **age** → বয়স (কমপক্ষে ১৮ হতে হবে)  
🔹 **salary** → বেতন (DECIMAL(10,2) অর্থাৎ, ১০ ডিজিটের মধ্যে ২ ডিজিট দশমিকের পর)  
🔹 **join_date** → যোগদানের তারিখ

#### ✅ IF NOT EXISTS ব্যবহার করা

```sql
CREATE TABLE IF NOT EXISTS employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(50) NOT NULL,
    department VARCHAR(30),
    age INT CHECK (age >= 18),
    salary DECIMAL(10,2),
    join_date DATE
);
```

🔹 **IF NOT EXISTS** → যদি employees টেবিল না থাকে, তাহলে নতুন করে তৈরি করবে

### ALTER TABLE - টেবিল পরিবর্তন করা

#### কলাম যোগ করা

```sql
ALTER TABLE employees 
ADD email VARCHAR(100);
```

#### কলাম মুছে ফেলা

```sql
ALTER TABLE employees 
DROP COLUMN email;
```

#### কলাম পরিবর্তন করা

```sql
ALTER TABLE employees 
MODIFY COLUMN salary DECIMAL(12,2);
```

#### কলামের নাম পরিবর্তন করা

```sql
ALTER TABLE employees 
CHANGE COLUMN department dept_name VARCHAR(50);
```

### DROP TABLE - টেবিল মুছে ফেলা

```sql
DROP TABLE employees;
```

#### নিরাপদ ভাবে মুছে ফেলা

```sql
DROP TABLE IF EXISTS employees;
```

### TRUNCATE TABLE - সব ডাটা মুছে ফেলা (কিন্তু টেবিল রাখা)

```sql
TRUNCATE TABLE employees;
```

### RENAME TABLE - টেবিলের নাম পরিবর্তন করা

```sql
RENAME TABLE employees TO staff_members;
```

---

## 📝 DML - Data Manipulation Language {#dml-commands}

### INSERT INTO কিভাবে কাজ করে?

**SQL-এ INSERT INTO ব্যবহার করা হয় টেবিলে নতুন ডাটা সংযুক্ত করতে।**

#### ✅ সাধারণ গঠন (Syntax)

```sql
INSERT INTO table_name (column1, column2, column3, ...) 
VALUES (value1, value2, value3, ...);
```

#### ✅ employees টেবিলে ২০ জন কর্মীর ডাটা ইনসার্ট করা

```sql
INSERT INTO employees (name, department, age, salary, join_date) VALUES
('Karim Ahmed', 'IT', 28, 65000.00, '2020-01-15'),
('Nusrat Jahan', 'Operations', 32, 58000.00, '2019-05-22'),
('Md. Hasan', 'Finance', 35, 72000.00, '2018-11-08'),
('Sadia Islam', 'Marketing', 26, 52000.00, '2021-03-14'),
('Rafiq Uddin', 'IT', 29, 68000.00, '2020-07-19'),
('Fatema Begum', 'HR', 31, 54000.00, '2019-12-03'),
('Jahangir Alam', 'Sales', 27, 49000.00, '2021-09-25'),
('Sharmin Akter', 'Finance', 33, 71000.00, '2018-06-17'),
('Imran Hossain', 'IT', 24, 62000.00, '2022-02-10'),
('Roksana Parvin', 'Marketing', 28, 55000.00, '2020-10-30'),
('Abdul Kadir', 'Operations', 36, 76000.00, '2017-08-12'),
('Sultana Razia', 'HR', 30, 53000.00, '2019-04-28'),
('Firoz Kabir', 'Sales', 25, 47000.00, '2022-06-05'),
('Nasima Khatun', 'IT', 34, 74000.00, '2018-03-21'),
('Selim Reza', 'Finance', 29, 66000.00, '2020-11-16'),
('Amina Siddiqui', 'Marketing', 27, 51000.00, '2021-07-09'),
('Habib Rahman', 'Operations', 31, 59000.00, '2019-09-14'),
('Tahmina Yasmin', 'HR', 26, 50000.00, '2022-01-20'),
('Monir Hossain', 'Sales', 33, 63000.00, '2018-12-07'),
('Dilruba Akhter', 'IT', 30, 70000.00, '2019-10-23');
```

#### ✅ INSERT + SELECT (অন্য টেবিল থেকে ডাটা কপি করা)

```sql
INSERT INTO employees (name, department, age, salary, join_date)
SELECT full_name, dept, years, pay, start_date FROM old_employees;
```

### UPDATE কিভাবে কাজ করে?

**SQL-এ UPDATE ব্যবহার করা হয় অবস্থানে থাকা ডাটা পরিবর্তন করতে।**

#### ✅ সাধারণ গঠন (Syntax)

```sql
UPDATE table_name  
SET column1 = value1, column2 = value2, ...  
WHERE condition;
```

⚠️ **IMPORTANT:** WHERE না দিলে পুরো টেবিলের ডাটা আপডেট হয়ে যাবে!

#### ✅ এক কলাম আপডেট করা

```sql
UPDATE employees  
SET salary = 75000  
WHERE id = 1;
```

#### ✅ একাধিক কলাম আপডেট করা

```sql
UPDATE employees  
SET salary = 62000, department = 'IT'  
WHERE id = 2;
```

#### ✅ শর্ত অনুযায়ী আপডেট করা

```sql
UPDATE employees  
SET salary = salary * 1.10  
WHERE department = 'IT';
```

### DELETE - ডাটা মুছে ফেলা

#### ✅ সাধারণ গঠন (Syntax)

```sql
DELETE FROM table_name  
WHERE condition;
```

⚠️ **IMPORTANT:** WHERE না দিলে পুরো টেবিলের ডাটা মুছে যাবে!

#### ✅ নির্দিষ্ট রো মুছে ফেলা

```sql
DELETE FROM employees  
WHERE id = 10;
```

#### ✅ শর্ত অনুযায়ী মুছে ফেলা

```sql
DELETE FROM employees  
WHERE salary < 40000;
```

---

## 🔍 DQL - Data Query Language {#dql-commands}

### SELECT - ডাটা দেখা

#### ✅ সব কলাম দেখা

```sql
SELECT * FROM employees;
```

#### ✅ নির্দিষ্ট কলাম দেখা

```sql
SELECT name, salary FROM employees;
```

#### ✅ DISTINCT - ডুপ্লিকেট বাদ দিয়ে দেখা

```sql
SELECT DISTINCT department FROM employees;
```

### WHERE Clause কি এবং এটি কিভাবে কাজ করে?

**WHERE ক্লজ SQL-তে শর্ত নির্ধারণের জন্য ব্যবহৃত হয়।**

#### ✅ নির্দিষ্ট ডিপার্টমেন্টের কর্মচারীদের খুঁজে বের করা

```sql
SELECT * FROM employees WHERE department = 'IT';
```

#### ✅ ৩০ বছরের বেশি বয়সী কর্মচারীদের তালিকা

```sql
SELECT * FROM employees WHERE age > 30;
```

#### ✅ নির্দিষ্ট বেতনসীমার মধ্যে কর্মচারীদের তালিকা

```sql
SELECT * FROM employees WHERE salary BETWEEN 40000 AND 50000;
```

### LIMIT & OFFSET

#### ✅ প্রথম ৫ জন কর্মী দেখানো

```sql
SELECT * FROM employees LIMIT 5;
```

#### ✅ প্রথম ৫টি রো বাদ দিয়ে, পরের ৫টি রো দেখানো

```sql
SELECT * FROM employees LIMIT 5 OFFSET 5;
```

### ORDER BY - ডাটা সাজানো

#### ✅ নাম ক্রমানুসারে সাজানো (A-Z)

```sql
SELECT * FROM employees ORDER BY name ASC;
```

#### ✅ বেতন অনুযায়ী বড় থেকে ছোট সাজানো

```sql
SELECT * FROM employees ORDER BY salary DESC;
```

#### ✅ একাধিক কলামের উপর ORDER BY

```sql
SELECT * FROM employees 
ORDER BY department ASC, age ASC;
```

---

## 🔐 Constraints {#constraints}

### PRIMARY KEY

```sql
CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(50) NOT NULL
);
```

### FOREIGN KEY

```sql
CREATE TABLE departments (
    id INT PRIMARY KEY,
    department_name VARCHAR(50) NOT NULL
);

CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    department_id INT,
    FOREIGN KEY (department_id) REFERENCES departments(id)
);
```

### UNIQUE - অনন্য মান

```sql
CREATE TABLE users (
    id INT PRIMARY KEY,
    email VARCHAR(100) UNIQUE,
    username VARCHAR(50) UNIQUE
);
```

### NOT NULL - খালি রাখা যাবে না

```sql
CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    email VARCHAR(100) NOT NULL
);
```

### CHECK - শর্ত নির্ধারণ করা

```sql
CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    age INT CHECK (age >= 18),
    salary DECIMAL(10,2) CHECK (salary > 0)
);
```

### DEFAULT - ডিফল্ট মান সেট করা

```sql
CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    department VARCHAR(30) DEFAULT 'Unknown',
    status VARCHAR(20) DEFAULT 'Active'
);
```

### NULL এবং NOT NULL কিভাবে কাজ করে?

**SQL-এ NULL মানে হলো কোনো ডাটা নেই বা অজানা মান।**

#### ✅ NULL চেক করা

```sql
SELECT * FROM employees WHERE department IS NULL;
```

#### ✅ NULL না থাকা ডাটা খুঁজা

```sql
SELECT * FROM employees WHERE department IS NOT NULL;
```

#### ✅ NULL ফিল্ড আপডেট করা

```sql
UPDATE employees  
SET department = 'HR'  
WHERE department IS NULL;
```

---

## ⚙️ Operators {#operators}

### Comparison Operators

| Operator | Description | Example |
|----------|-------------|---------|
| `=` | সমান | `WHERE age = 25` |
| `!=` or `<>` | সমান নয় | `WHERE age != 25` |
| `>` | বড় | `WHERE age > 25` |
| `<` | ছোট | `WHERE age < 25` |
| `>=` | বড় বা সমান | `WHERE age >= 25` |
| `<=` | ছোট বা সমান | `WHERE age <= 25` |

### Logical Operators - AND, OR, NOT

#### ✅ AND অপারেটর (দুটি শর্ত একসাথে পূরণ করতে হবে)

```sql
SELECT * FROM employees 
WHERE department = 'IT' AND age >= 30;
```

#### ✅ OR অপারেটর (একটি শর্ত মিললেই হবে)

```sql
SELECT * FROM employees 
WHERE department = 'HR' OR department = 'IT';
```

#### ✅ NOT অপারেটর (শর্ত না মিললে রিটার্ন করবে)

```sql
SELECT * FROM employees 
WHERE NOT department = 'IT';
```

### BETWEEN - দুটি মানের মধ্যে ডাটা ফিল্টার করা

```sql
SELECT * FROM employees 
WHERE salary BETWEEN 40000 AND 50000;
```

### IN - নির্দিষ্ট তালিকার মধ্যে থাকা মান

```sql
SELECT * FROM employees 
WHERE department IN ('HR', 'IT', 'Finance');
```

### NOT IN - নির্দিষ্ট মান বাদ দেওয়া

```sql
SELECT * FROM employees 
WHERE department NOT IN ('IT', 'Finance');
```

### LIKE - প্যাটার্ন মিলানো

#### ✅ নির্দিষ্ট অক্ষর দিয়ে শুরু হওয়া ডাটা

```sql
SELECT * FROM employees 
WHERE name LIKE 'S%';
```

#### ✅ নির্দিষ্ট অক্ষর দিয়ে শেষ হওয়া ডাটা

```sql
SELECT * FROM employees 
WHERE name LIKE '%n';
```

#### ✅ নামের মাঝখানে নির্দিষ্ট ক্যারেক্টার থাকলে

```sql
SELECT * FROM employees 
WHERE name LIKE '%ah%';
```

#### ✅ ঠিক ১টি ক্যারেক্টার রিপ্লেস করা

```sql
SELECT * FROM employees 
WHERE name LIKE '_a%';
```

---

## 📊 Functions {#functions}

### Aggregate Functions

#### ✅ MIN - সর্বনিম্ন মান

```sql
SELECT MIN(salary) AS min_salary FROM employees;
```

#### ✅ MAX - সর্বোচ্চ মান

```sql
SELECT MAX(salary) AS max_salary FROM employees;
```

#### ✅ COUNT - ডাটা সংখ্যা গোনা

```sql
SELECT COUNT(*) AS total_employees FROM employees;
```

#### ✅ AVG - গড় মান

```sql
SELECT AVG(salary) AS avg_salary FROM employees;
```

#### ✅ SUM - মোট মান

```sql
SELECT SUM(salary) AS total_salary FROM employees;
```

#### ✅ একত্রে ব্যবহার

```sql
SELECT 
    MIN(salary) AS min_salary,
    MAX(salary) AS max_salary,
    COUNT(*) AS total_employees,
    AVG(salary) AS avg_salary,
    SUM(salary) AS total_salary
FROM employees;
```

### GROUP BY - ডাটা গ্রুপ করা

#### ✅ department অনুযায়ী গড় বেতন

```sql
SELECT department, AVG(salary) AS avg_salary 
FROM employees
GROUP BY department;
```

#### ✅ একাধিক কলামে GROUP BY

```sql
SELECT department, salary, COUNT(*) AS total_employees
FROM employees
GROUP BY department, salary;
```

### HAVING - গ্রুপের উপর শর্ত

```sql
SELECT department, AVG(salary) AS avg_salary 
FROM employees
GROUP BY department
HAVING AVG(salary) > 45000;
```

### String Functions

#### ✅ CONCAT - স্ট্রিং জোড়া লাগানো

```sql
SELECT CONCAT(name, ' - ', department) AS employee_info 
FROM employees;
```

#### ✅ UPPER - বড় হাতের অক্ষরে রূপান্তর

```sql
SELECT UPPER(name) FROM employees;
```

#### ✅ LOWER - ছোট হাতের অক্ষরে রূপান্তর

```sql
SELECT LOWER(name) FROM employees;
```

#### ✅ LENGTH - স্ট্রিং এর দৈর্ঘ্য

```sql
SELECT name, LENGTH(name) AS name_length FROM employees;
```

#### ✅ SUBSTRING - স্ট্রিং এর অংশ বের করা

```sql
SELECT SUBSTRING(name, 1, 3) AS short_name FROM employees;
```

#### ✅ TRIM - স্পেস বাদ দেওয়া

```sql
SELECT TRIM(name) FROM employees;
```

#### ✅ REPLACE - স্ট্রিং প্রতিস্থাপন

```sql
SELECT REPLACE(department, 'IT', 'Information Technology') 
FROM employees;
```

### Date and Time Functions

#### ✅ NOW - বর্তমান তারিখ ও সময়

```sql
-- Returns current date and time
SELECT NOW();  -- 2025-11-21 10:30:45

-- Easy Example
INSERT INTO logs (event_name, created_at) 
VALUES ('User Login', NOW());

-- Complex Example: Calculate server uptime
SELECT 
    server_name,
    start_time,
    NOW() AS current_time,
    TIMESTAMPDIFF(HOUR, start_time, NOW()) AS uptime_hours,
    CONCAT(
        FLOOR(TIMESTAMPDIFF(HOUR, start_time, NOW()) / 24), ' days ',
        MOD(TIMESTAMPDIFF(HOUR, start_time, NOW()), 24), ' hours'
    ) AS uptime_formatted
FROM servers
WHERE status = 'running';
```

#### ✅ CURDATE / CURRENT_DATE - বর্তমান তারিখ

```sql
-- Returns current date only
SELECT CURDATE();           -- 2025-11-21
SELECT CURRENT_DATE();      -- 2025-11-21

-- Easy Example
SELECT * FROM orders WHERE order_date = CURDATE();

-- Complex Example: Daily report
SELECT 
    CURDATE() AS report_date,
    COUNT(*) AS total_orders,
    SUM(amount) AS total_revenue,
    AVG(amount) AS avg_order_value,
    COUNT(DISTINCT customer_id) AS unique_customers
FROM orders
WHERE order_date = CURDATE();
```

#### ✅ CURTIME / CURRENT_TIME - বর্তমান সময়

```sql
-- Returns current time only
SELECT CURTIME();           -- 10:30:45
SELECT CURRENT_TIME();      -- 10:30:45

-- Easy Example
INSERT INTO attendance (employee_id, check_in_time) 
VALUES (101, CURTIME());

-- Complex Example: Shift analysis
SELECT 
    employee_id,
    name,
    check_in_time,
    CURTIME() AS current_time,
    CASE 
        WHEN check_in_time <= '09:00:00' THEN 'On Time'
        WHEN check_in_time <= '09:30:00' THEN 'Late'
        ELSE 'Very Late'
    END AS attendance_status
FROM attendance
WHERE DATE(check_in_date) = CURDATE();
```

#### ✅ YEAR, MONTH, DAY - তারিখের অংশ বের করা

```sql
-- Extract parts from date
SELECT 
    YEAR(join_date) AS join_year,
    MONTH(join_date) AS join_month,
    DAY(join_date) AS join_day
FROM employees;

-- Easy Example
SELECT * FROM orders WHERE YEAR(order_date) = 2024;

-- Complex Example: Cohort analysis by join month
SELECT 
    YEAR(join_date) AS year,
    MONTH(join_date) AS month,
    CONCAT(YEAR(join_date), '-', LPAD(MONTH(join_date), 2, '0')) AS cohort,
    COUNT(*) AS employees_joined,
    AVG(salary) AS avg_starting_salary
FROM employees
GROUP BY YEAR(join_date), MONTH(join_date)
ORDER BY year DESC, month DESC;
```

#### ✅ QUARTER, WEEK - কোয়ার্টার ও সপ্তাহ

```sql
-- Get quarter and week number
SELECT 
    order_date,
    QUARTER(order_date) AS quarter,
    WEEK(order_date) AS week_number
FROM orders;

-- Easy Example: Quarterly sales
SELECT 
    YEAR(order_date) AS year,
    QUARTER(order_date) AS quarter,
    SUM(amount) AS total_sales
FROM orders
GROUP BY YEAR(order_date), QUARTER(order_date);

-- Complex Example: Week-over-week growth
WITH weekly_sales AS (
    SELECT 
        YEARWEEK(order_date) AS year_week,
        SUM(amount) AS weekly_revenue
    FROM orders
    GROUP BY YEARWEEK(order_date)
)
SELECT 
    year_week,
    weekly_revenue,
    LAG(weekly_revenue) OVER (ORDER BY year_week) AS prev_week_revenue,
    ROUND(
        ((weekly_revenue - LAG(weekly_revenue) OVER (ORDER BY year_week)) / 
         LAG(weekly_revenue) OVER (ORDER BY year_week)) * 100,
        2
    ) AS wow_growth_pct
FROM weekly_sales;
```

#### ✅ DATEDIFF - দুই তারিখের মধ্যে পার্থক্য

```sql
-- Returns difference in days
SELECT DATEDIFF('2025-12-31', '2025-01-01');  -- 364

-- Easy Example
SELECT name, DATEDIFF(CURDATE(), join_date) AS days_worked 
FROM employees;

-- Complex Example: Employee tenure analysis
SELECT 
    name,
    join_date,
    CURDATE() AS today,
    DATEDIFF(CURDATE(), join_date) AS days_worked,
    ROUND(DATEDIFF(CURDATE(), join_date) / 365.25, 1) AS years_worked,
    CASE 
        WHEN DATEDIFF(CURDATE(), join_date) < 365 THEN 'New (<1 year)'
        WHEN DATEDIFF(CURDATE(), join_date) < 1095 THEN 'Junior (1-3 years)'
        WHEN DATEDIFF(CURDATE(), join_date) < 1825 THEN 'Mid-Level (3-5 years)'
        ELSE 'Senior (>5 years)'
    END AS seniority_level
FROM employees
ORDER BY days_worked DESC;
```

#### ✅ TIMESTAMPDIFF - নির্দিষ্ট একক অনুযায়ী পার্থক্য

```sql
-- TIMESTAMPDIFF(unit, start, end)
-- Units: SECOND, MINUTE, HOUR, DAY, WEEK, MONTH, YEAR

-- Easy Example
SELECT 
    name,
    join_date,
    TIMESTAMPDIFF(YEAR, join_date, CURDATE()) AS years,
    TIMESTAMPDIFF(MONTH, join_date, CURDATE()) AS months,
    TIMESTAMPDIFF(DAY, join_date, CURDATE()) AS days
FROM employees;

-- Complex Example: Detailed age calculation
SELECT 
    name,
    birth_date,
    TIMESTAMPDIFF(YEAR, birth_date, CURDATE()) AS age_years,
    TIMESTAMPDIFF(MONTH, birth_date, CURDATE()) - 
        (TIMESTAMPDIFF(YEAR, birth_date, CURDATE()) * 12) AS additional_months,
    CONCAT(
        TIMESTAMPDIFF(YEAR, birth_date, CURDATE()), ' years, ',
        TIMESTAMPDIFF(MONTH, birth_date, CURDATE()) - 
        (TIMESTAMPDIFF(YEAR, birth_date, CURDATE()) * 12), ' months'
    ) AS precise_age
FROM employees;
```

#### ✅ DATE_ADD / DATE_SUB - তারিখে যোগ/বিয়োগ

```sql
-- Add/Subtract intervals
SELECT DATE_ADD(CURDATE(), INTERVAL 1 YEAR);     -- Next year
SELECT DATE_ADD(CURDATE(), INTERVAL 30 DAY);     -- 30 days later
SELECT DATE_SUB(CURDATE(), INTERVAL 1 MONTH);    -- Last month

-- Easy Example
SELECT 
    name,
    join_date,
    DATE_ADD(join_date, INTERVAL 1 YEAR) AS first_anniversary
FROM employees;

-- Complex Example: Subscription expiry tracking
SELECT 
    customer_id,
    customer_name,
    subscription_start,
    subscription_months,
    DATE_ADD(subscription_start, INTERVAL subscription_months MONTH) AS expiry_date,
    DATEDIFF(
        DATE_ADD(subscription_start, INTERVAL subscription_months MONTH), 
        CURDATE()
    ) AS days_remaining,
    CASE 
        WHEN CURDATE() > DATE_ADD(subscription_start, INTERVAL subscription_months MONTH) 
        THEN 'Expired'
        WHEN DATEDIFF(DATE_ADD(subscription_start, INTERVAL subscription_months MONTH), CURDATE()) <= 7 
        THEN 'Expiring Soon'
        ELSE 'Active'
    END AS status
FROM subscriptions;
```

#### ✅ DATEPART (SQL Server) / EXTRACT (MySQL/PostgreSQL)

```sql
-- MySQL/PostgreSQL: EXTRACT
SELECT EXTRACT(YEAR FROM join_date) AS year FROM employees;
SELECT EXTRACT(MONTH FROM join_date) AS month FROM employees;
SELECT EXTRACT(DAY FROM join_date) AS day FROM employees;

-- Easy Example
SELECT * FROM orders 
WHERE EXTRACT(MONTH FROM order_date) = 12;  -- December orders

-- Complex Example: Time-based pattern analysis
SELECT 
    EXTRACT(HOUR FROM created_at) AS hour_of_day,
    EXTRACT(DOW FROM created_at) AS day_of_week,  -- 0=Sunday, 6=Saturday
    COUNT(*) AS event_count,
    CASE EXTRACT(DOW FROM created_at)
        WHEN 0 THEN 'Sunday'
        WHEN 1 THEN 'Monday'
        WHEN 2 THEN 'Tuesday'
        WHEN 3 THEN 'Wednesday'
        WHEN 4 THEN 'Thursday'
        WHEN 5 THEN 'Friday'
        WHEN 6 THEN 'Saturday'
    END AS day_name
FROM user_activities
WHERE created_at >= CURDATE() - INTERVAL 30 DAY
GROUP BY EXTRACT(HOUR FROM created_at), EXTRACT(DOW FROM created_at)
ORDER BY day_of_week, hour_of_day;
```

#### ✅ DATEADD (SQL Server) / DATE_ADD (MySQL)

```sql
-- SQL Server syntax: DATEADD(datepart, number, date)
-- MySQL syntax: DATE_ADD(date, INTERVAL number unit)

-- Easy Example (MySQL)
SELECT DATE_ADD(CURDATE(), INTERVAL 7 DAY) AS next_week;
SELECT DATE_ADD(NOW(), INTERVAL 2 HOUR) AS two_hours_later;

-- Complex Example: Payment schedule generator
SELECT 
    loan_id,
    customer_name,
    loan_amount,
    monthly_payment,
    start_date,
    installment_number,
    DATE_ADD(start_date, INTERVAL (installment_number - 1) MONTH) AS due_date,
    monthly_payment AS payment_amount
FROM loans
CROSS JOIN (
    SELECT 1 AS installment_number UNION SELECT 2 UNION SELECT 3 
    UNION SELECT 4 UNION SELECT 5 UNION SELECT 6
    UNION SELECT 7 UNION SELECT 8 UNION SELECT 9
    UNION SELECT 10 UNION SELECT 11 UNION SELECT 12
) AS installments
WHERE duration_months >= installment_number
ORDER BY loan_id, installment_number;
```

#### ✅ DATE_FORMAT - তারিখ ফরম্যাট করা

```sql
-- Format dates in various ways
SELECT DATE_FORMAT(join_date, '%d-%m-%Y') AS formatted_date 
FROM employees;

-- Common format codes:
-- %Y = 4-digit year (2025)
-- %y = 2-digit year (25)
-- %M = Full month name (January)
-- %m = 2-digit month (01-12)
-- %d = 2-digit day (01-31)
-- %W = Weekday name (Monday)
-- %H = Hour 24h format (00-23)
-- %i = Minutes (00-59)
-- %s = Seconds (00-59)

-- Easy Example
SELECT 
    order_id,
    DATE_FORMAT(order_date, '%W, %M %d, %Y') AS formatted_date
FROM orders;

-- Complex Example: Comprehensive date formatting
SELECT 
    name,
    join_date,
    DATE_FORMAT(join_date, '%d/%m/%Y') AS format_ddmmyyyy,
    DATE_FORMAT(join_date, '%M %d, %Y') AS format_full,
    DATE_FORMAT(join_date, '%W') AS day_of_week,
    DATE_FORMAT(join_date, '%Y-Q%q') AS quarter,
    DATE_FORMAT(NOW(), '%Y-%m-%d %H:%i:%s') AS timestamp_format,
    CONCAT(
        DATE_FORMAT(join_date, '%M %d, %Y'), ' (',
        TIMESTAMPDIFF(YEAR, join_date, CURDATE()), ' years ago)'
    ) AS descriptive_date
FROM employees
LIMIT 5;
```

#### ✅ TIMESTAMP Functions

```sql
-- Working with timestamps
SELECT 
    UNIX_TIMESTAMP() AS current_unix_time,
    FROM_UNIXTIME(1700000000) AS from_unix,
    TIMESTAMP('2025-11-21', '10:30:00') AS combined_timestamp;

-- Easy Example
SELECT 
    event_name,
    UNIX_TIMESTAMP(event_time) AS unix_time
FROM events;

-- Complex Example: Session duration tracking
SELECT 
    session_id,
    user_id,
    login_time,
    logout_time,
    TIMESTAMPDIFF(SECOND, login_time, logout_time) AS session_seconds,
    CONCAT(
        FLOOR(TIMESTAMPDIFF(SECOND, login_time, logout_time) / 3600), 'h ',
        FLOOR((TIMESTAMPDIFF(SECOND, login_time, logout_time) % 3600) / 60), 'm ',
        MOD(TIMESTAMPDIFF(SECOND, login_time, logout_time), 60), 's'
    ) AS session_duration
FROM user_sessions
WHERE logout_time IS NOT NULL
ORDER BY session_seconds DESC;
```

### Mathematical Functions

#### ✅ ROUND - রাউন্ড করা

```sql
-- Basic rounding
SELECT ROUND(salary, 0) FROM employees;
SELECT ROUND(1234.5678, 2);  -- 1234.57

-- Easy Example
SELECT name, salary, ROUND(salary/12, 2) AS monthly_salary
FROM employees;

-- Complex Example: Calculate bonus with rounding
SELECT 
    name,
    salary,
    ROUND(salary * 0.15, 0) AS bonus,
    ROUND(salary + (salary * 0.15), 2) AS total_compensation
FROM employees
WHERE department = 'Sales';
```

#### ✅ CEIL / CEILING - উপরের দিকে রাউন্ড

```sql
-- Always rounds up
SELECT CEIL(salary) FROM employees;
SELECT CEILING(123.01);  -- 124

-- Easy Example
SELECT CEIL(price) AS rounded_price FROM products;

-- Complex Example: Calculate required batches
SELECT 
    product_name,
    total_items,
    batch_size,
    CEIL(total_items / batch_size) AS required_batches,
    CEIL(total_items / batch_size) * batch_size AS items_to_produce
FROM (
    SELECT 
        'Widget' AS product_name,
        527 AS total_items,
        50 AS batch_size
) AS production_data;
-- Result: Need 11 batches (550 items) to fulfill 527 items order
```

#### ✅ FLOOR - নিচের দিকে রাউন্ড

```sql
-- Always rounds down
SELECT FLOOR(salary) FROM employees;
SELECT FLOOR(123.99);  -- 123

-- Easy Example
SELECT name, FLOOR(age) AS age_floor FROM employees;

-- Complex Example: Calculate completed years
SELECT 
    name,
    join_date,
    FLOOR(DATEDIFF(CURDATE(), join_date) / 365) AS completed_years,
    FLOOR(DATEDIFF(CURDATE(), join_date) / 30) AS completed_months
FROM employees
ORDER BY completed_years DESC;
```

#### ✅ ABS - পরম মান (Absolute Value)

```sql
-- Remove negative sign
SELECT ABS(-100) AS absolute_value;  -- 100
SELECT ABS(50) AS absolute_value;    -- 50

-- Easy Example
SELECT ABS(balance) AS amount FROM accounts;

-- Complex Example: Calculate variance from target
SELECT 
    employee_name,
    sales_target,
    actual_sales,
    actual_sales - sales_target AS difference,
    ABS(actual_sales - sales_target) AS absolute_difference,
    CASE 
        WHEN actual_sales >= sales_target THEN 'Met Target'
        ELSE 'Below Target'
    END AS status
FROM sales_performance;
```

#### ✅ MOD - ভাগশেষ (Modulo)

```sql
-- Returns remainder after division
SELECT MOD(10, 3);  -- 1
SELECT MOD(15, 4);  -- 3

-- Easy Example: Find even/odd numbers
SELECT 
    id,
    name,
    CASE WHEN MOD(id, 2) = 0 THEN 'Even' ELSE 'Odd' END AS parity
FROM employees;

-- Complex Example: Distribute employees into teams
SELECT 
    id,
    name,
    department,
    MOD(id, 5) + 1 AS team_number,
    CASE 
        WHEN MOD(id, 5) = 0 THEN 'Team 1'
        WHEN MOD(id, 5) = 1 THEN 'Team 2'
        WHEN MOD(id, 5) = 2 THEN 'Team 3'
        WHEN MOD(id, 5) = 3 THEN 'Team 4'
        ELSE 'Team 5'
    END AS team_name
FROM employees
WHERE department = 'IT'
ORDER BY team_number;
```

#### ✅ POWER / POW - ঘাত (Exponentiation)

```sql
-- Calculate power
SELECT POWER(2, 3) AS result;  -- 2^3 = 8
SELECT POW(5, 2);               -- 5^2 = 25

-- Easy Example
SELECT POWER(10, 2) AS hundred;  -- 100

-- Complex Example: Compound interest calculation
SELECT 
    account_id,
    principal_amount,
    interest_rate,
    years,
    ROUND(
        principal_amount * POWER((1 + interest_rate/100), years), 
        2
    ) AS maturity_amount,
    ROUND(
        (principal_amount * POWER((1 + interest_rate/100), years)) - principal_amount,
        2
    ) AS interest_earned
FROM investments;
```

#### ✅ SQRT - বর্গমূল (Square Root)

```sql
-- Calculate square root
SELECT SQRT(16);    -- 4
SELECT SQRT(25);    -- 5

-- Easy Example
SELECT SQRT(area) AS side_length FROM squares;

-- Complex Example: Calculate distance between two points
SELECT 
    p1.location_name AS from_location,
    p2.location_name AS to_location,
    ROUND(
        SQRT(
            POWER(p2.x_coordinate - p1.x_coordinate, 2) + 
            POWER(p2.y_coordinate - p1.y_coordinate, 2)
        ),
        2
    ) AS distance
FROM locations p1
CROSS JOIN locations p2
WHERE p1.id < p2.id;
```

#### ✅ SIGN - চিহ্ন নির্ণয় (Sign Function)

```sql
-- Returns -1, 0, or 1
SELECT SIGN(-45);   -- -1
SELECT SIGN(0);     -- 0
SELECT SIGN(123);   -- 1

-- Easy Example
SELECT 
    transaction_id,
    amount,
    SIGN(amount) AS sign_value,
    CASE 
        WHEN SIGN(amount) = 1 THEN 'Credit'
        WHEN SIGN(amount) = -1 THEN 'Debit'
        ELSE 'Zero'
    END AS transaction_type
FROM transactions;

-- Complex Example: Classify profit/loss trends
SELECT 
    quarter,
    revenue,
    expenses,
    (revenue - expenses) AS net_profit,
    SIGN(revenue - expenses) AS profit_indicator,
    LAG(SIGN(revenue - expenses)) OVER (ORDER BY quarter) AS prev_quarter_indicator,
    CASE 
        WHEN SIGN(revenue - expenses) = 1 AND 
             LAG(SIGN(revenue - expenses)) OVER (ORDER BY quarter) = 1 
        THEN 'Consistent Profit'
        WHEN SIGN(revenue - expenses) = -1 AND 
             LAG(SIGN(revenue - expenses)) OVER (ORDER BY quarter) = -1 
        THEN 'Consistent Loss'
        ELSE 'Fluctuating'
    END AS trend
FROM quarterly_financials;
```

#### ✅ TRUNCATE - নির্দিষ্ট দশমিক স্থান পর্যন্ত কাটা

```sql
-- Cut decimal places (not round)
SELECT TRUNCATE(123.456, 2);  -- 123.45
SELECT TRUNCATE(123.456, 0);  -- 123

-- Easy Example
SELECT name, TRUNCATE(salary, -3) AS salary_rounded_thousands
FROM employees;

-- Complex Example: Price tiers
SELECT 
    product_name,
    actual_price,
    TRUNCATE(actual_price, 0) AS price_floor,
    TRUNCATE(actual_price, -1) AS price_tens,
    TRUNCATE(actual_price, -2) AS price_hundreds,
    CASE 
        WHEN TRUNCATE(actual_price, -2) < 1000 THEN 'Budget'
        WHEN TRUNCATE(actual_price, -2) < 5000 THEN 'Mid-Range'
        ELSE 'Premium'
    END AS price_category
FROM products;
```

### Conditional Functions

#### ✅ IF - শর্ত অনুযায়ী মান ফেরত

```sql
SELECT name, salary,
    IF(salary > 50000, 'High', 'Low') AS salary_category
FROM employees;
```

#### ✅ CASE WHEN - একাধিক শর্ত

```sql
SELECT name, salary,
    CASE 
        WHEN salary > 50000 THEN 'High'
        WHEN salary > 40000 THEN 'Medium'
        ELSE 'Low'
    END AS salary_category
FROM employees;
```

#### ✅ COALESCE - প্রথম NON-NULL মান ফেরত

```sql
SELECT COALESCE(department, 'No Department') AS dept 
FROM employees;
```

#### ✅ NULLIF - দুটি মান সমান হলে NULL ফেরত

```sql
SELECT NULLIF(department, 'IT') FROM employees;
```

---

## 🔗 Joins {#joins}

### INNER JOIN - মিলে যাওয়া রেকর্ড

```sql
SELECT employees.name, departments.department_name  
FROM employees  
INNER JOIN departments  
ON employees.department_id = departments.id;
```

**Result:** শুধুমাত্র যাদের ডিপার্টমেন্ট আছে, তাদের দেখাবে।

### LEFT JOIN - বামের সব + ডানের মিল

```sql
SELECT employees.name, departments.department_name  
FROM employees  
LEFT JOIN departments  
ON employees.department_id = departments.id;
```

**Result:** সব কর্মী দেখাবে, এমনকি যাদের ডিপার্টমেন্ট নেই তাদেরও।

### RIGHT JOIN - ডানের সব + বামের মিল

```sql
SELECT employees.name, departments.department_name  
FROM employees  
RIGHT JOIN departments  
ON employees.department_id = departments.id;
```

**Result:** সব ডিপার্টমেন্ট দেখাবে, এমনকি যেখানে কর্মী নেই।

### FULL OUTER JOIN - উভয় পক্ষের সব

```sql
SELECT employees.name, departments.department_name  
FROM employees  
LEFT JOIN departments ON employees.department_id = departments.id
UNION
SELECT employees.name, departments.department_name  
FROM employees  
RIGHT JOIN departments ON employees.department_id = departments.id;
```

**Note:** MySQL-এ সরাসরি FULL OUTER JOIN নেই, তাই UNION ব্যবহার করা হয়।

### CROSS JOIN - সব সম্ভাব্য সংমিশ্রণ

```sql
SELECT employees.name, departments.department_name  
FROM employees  
CROSS JOIN departments;
```

### SELF JOIN - একই টেবিলের সাথে JOIN

```sql
SELECT e1.name AS employee, e2.name AS manager
FROM employees e1
INNER JOIN employees e2 ON e1.manager_id = e2.id;
```

### USING - একই নামের কলামে JOIN

```sql
SELECT employees.name, departments.department_name  
FROM employees  
INNER JOIN departments  
USING (department_id);
```

**Note:** USING শুধুমাত্র তখন ব্যবহার করা যায় যখন উভয় টেবিলে কলামের নাম একই হয়।

---

## 🔍 Subqueries {#subqueries}

### Simple Subquery

```sql
SELECT name, salary  
FROM employees  
WHERE salary > (SELECT AVG(salary) FROM employees);
```

### Subquery in FROM clause

```sql
SELECT dept, avg_salary  
FROM (
    SELECT department AS dept, AVG(salary) AS avg_salary  
    FROM employees  
    GROUP BY department
) AS dept_avg  
WHERE avg_salary > 50000;
```

### Correlated Subquery

```sql
SELECT name, salary, department  
FROM employees e1  
WHERE salary > (
    SELECT AVG(salary)
    FROM employees e2
    WHERE e2.department = e1.department
);
```

### EXISTS - রেকর্ড আছে কিনা চেক করা

```sql
SELECT name 
FROM employees e
WHERE EXISTS (
    SELECT 1 FROM departments d 
    WHERE d.id = e.department_id
);
```

### IN with Subquery

```sql
SELECT name 
FROM employees
WHERE department_id IN (
    SELECT id FROM departments 
    WHERE location = 'Dhaka'
);
```

### ANY - যেকোনো একটি শর্ত মিললেই

```sql
SELECT name, salary
FROM employees
WHERE salary > ANY (
    SELECT salary FROM employees WHERE department = 'IT'
);
```

### ALL - সব শর্ত মিলতে হবে

```sql
SELECT name, salary
FROM employees
WHERE salary > ALL (
    SELECT salary FROM employees WHERE department = 'HR'
);
```

---

## 👁️ Views {#views}

### View কি?
**View হলো একটি ভার্চুয়াল টেবিল যা একটি SQL কুয়েরির রেজাল্ট সংরক্ষণ করে।**

### ✅ Creating Views - View তৈরি করা

#### Easy Example 1: Simple View
```sql
-- Create a basic view
CREATE VIEW high_salary_employees AS
SELECT name, salary, department
FROM employees
WHERE salary > 50000;

-- Use the view
SELECT * FROM high_salary_employees;
```

#### Easy Example 2: Department Summary View
```sql
CREATE VIEW department_summary AS
SELECT 
    department,
    COUNT(*) AS employee_count,
    AVG(salary) AS avg_salary,
    MAX(salary) AS max_salary
FROM employees
GROUP BY department;

-- Query the view
SELECT * FROM department_summary WHERE employee_count > 5;
```

#### Complex Example: Multi-table View with Calculations
```sql
CREATE VIEW employee_performance_view AS
SELECT 
    e.id,
    e.name,
    e.department,
    e.salary,
    d.department_name,
    d.budget AS dept_budget,
    COUNT(p.project_id) AS projects_count,
    SUM(p.budget) AS total_project_budget,
    ROUND((e.salary / d.budget) * 100, 2) AS salary_percentage_of_dept_budget,
    CASE 
        WHEN COUNT(p.project_id) >= 5 THEN 'High Performer'
        WHEN COUNT(p.project_id) >= 3 THEN 'Good Performer'
        ELSE 'Average Performer'
    END AS performance_level
FROM employees e
INNER JOIN departments d ON e.department_id = d.id
LEFT JOIN employee_projects ep ON e.id = ep.employee_id
LEFT JOIN projects p ON ep.project_id = p.id
GROUP BY e.id, e.name, e.department, e.salary, d.department_name, d.budget;

-- Query the complex view
SELECT * FROM employee_performance_view 
WHERE performance_level = 'High Performer'
ORDER BY total_project_budget DESC;
```

### ✅ Modifying Views - View পরিবর্তন করা

#### Method 1: CREATE OR REPLACE VIEW

```sql
-- Easy Example: Add more columns to existing view
CREATE OR REPLACE VIEW high_salary_employees AS
SELECT 
    id,
    name, 
    salary, 
    department, 
    age,
    join_date
FROM employees
WHERE salary > 50000;
```

#### Method 2: ALTER VIEW (MySQL 5.7.18+)

```sql
-- Modify existing view definition
ALTER VIEW high_salary_employees AS
SELECT 
    id,
    name, 
    salary, 
    department, 
    age,
    join_date,
    TIMESTAMPDIFF(YEAR, join_date, CURDATE()) AS years_of_service
FROM employees
WHERE salary > 50000;
```

#### Complex Example: Modifying Multi-table View

```sql
-- Original view
CREATE VIEW sales_report AS
SELECT 
    o.order_id,
    c.customer_name,
    o.order_date,
    SUM(oi.quantity * oi.price) AS total_amount
FROM orders o
INNER JOIN customers c ON o.customer_id = c.id
INNER JOIN order_items oi ON o.order_id = oi.order_id
GROUP BY o.order_id, c.customer_name, o.order_date;

-- Modified view with additional analytics
CREATE OR REPLACE VIEW sales_report AS
SELECT 
    o.order_id,
    c.customer_name,
    c.email,
    c.city,
    o.order_date,
    COUNT(oi.item_id) AS items_count,
    SUM(oi.quantity * oi.price) AS total_amount,
    AVG(oi.quantity * oi.price) AS avg_item_value,
    CASE 
        WHEN SUM(oi.quantity * oi.price) > 10000 THEN 'Premium'
        WHEN SUM(oi.quantity * oi.price) > 5000 THEN 'Standard'
        ELSE 'Basic'
    END AS order_category,
    DATEDIFF(CURDATE(), o.order_date) AS days_since_order
FROM orders o
INNER JOIN customers c ON o.customer_id = c.id
INNER JOIN order_items oi ON o.order_id = oi.order_id
GROUP BY o.order_id, c.customer_name, c.email, c.city, o.order_date;
```

### ✅ Dropping Views - View মুছে ফেলা

#### Easy Example
```sql
-- Drop single view
DROP VIEW high_salary_employees;

-- Drop view if exists (safe)
DROP VIEW IF EXISTS high_salary_employees;
```

#### Complex Example: Drop multiple views
```sql
-- Drop multiple views at once
DROP VIEW IF EXISTS 
    high_salary_employees,
    department_summary,
    employee_performance_view,
    sales_report;
```

### ✅ Managing Views - View ম্যানেজমেন্ট

#### Show all views in database
```sql
-- MySQL
SHOW FULL TABLES WHERE Table_type = 'VIEW';

-- Get view definition
SHOW CREATE VIEW high_salary_employees;
```

#### Check view information
```sql
-- View details from information schema
SELECT 
    TABLE_NAME AS view_name,
    VIEW_DEFINITION,
    CHECK_OPTION,
    IS_UPDATABLE
FROM information_schema.VIEWS
WHERE TABLE_SCHEMA = 'your_database_name';
```

### ✅ Updatable Views - আপডেটযোগ্য Views

#### Easy Example: Simple updatable view
```sql
-- Create updatable view (single table, no aggregation)
CREATE VIEW editable_employees AS
SELECT id, name, salary, department
FROM employees
WHERE department = 'IT';

-- Update through view
UPDATE editable_employees 
SET salary = salary * 1.1 
WHERE id = 5;

-- Insert through view
INSERT INTO editable_employees (name, salary, department)
VALUES ('New Employee', 55000, 'IT');
```

#### Complex Example: View with CHECK OPTION
```sql
-- Create view with WITH CHECK OPTION
CREATE VIEW high_earners AS
SELECT id, name, salary, department
FROM employees
WHERE salary > 60000
WITH CHECK OPTION;

-- This will work
UPDATE high_earners SET salary = 65000 WHERE id = 1;

-- This will FAIL (violates WHERE clause)
UPDATE high_earners SET salary = 50000 WHERE id = 1;
```

### View এর সুবিধা

✅ **Security** - নির্দিষ্ট ডাটা দেখা যায়  
✅ **Simplicity** - জটিল কুয়েরি সহজভাবে ব্যবহার করা যায়  
✅ **Consistency** - একই কুয়েরি বারবার লিখতে হয় না  
✅ **Logical Data Independence** - Table structure পরিবর্তন করলেও view একই থাকে  
✅ **Query Simplification** - Complex joins সহজ করে

### View এর সীমাবদ্ধতা

❌ **Performance** - Complex views slow হতে পারে  
❌ **Dependencies** - Base table পরিবর্তন view ভেঙে দিতে পারে  
❌ **Update Restrictions** - সব view updatable নয়  
❌ **No Indexes** - Views নিজে index রাখে না (base table-এর index ব্যবহার করে)

---

## 📑 Indexes {#indexes}

### Index কি?
**Index ডাটা দ্রুত খুঁজে পেতে সাহায্য করে, বই এর সূচিপত্রের মতো।**

### Index তৈরি করা

```sql
CREATE INDEX idx_salary ON employees(salary);
```

### একাধিক কলামে Index

```sql
CREATE INDEX idx_dept_salary ON employees(department, salary);
```

### UNIQUE Index

```sql
CREATE UNIQUE INDEX idx_email ON employees(email);
```

### Index দেখা

```sql
SHOW INDEX FROM employees;
```

### Index মুছে ফেলা

```sql
DROP INDEX idx_salary ON employees;
```

### Index এর সুবিধা ও অসুবিধা

#### ✅ সুবিধা:
- দ্রুত সার্চ করা যায়
- WHERE, ORDER BY, JOIN দ্রুত হয়

#### ❌ অসুবিধা:
- ডিস্ক স্পেস নেয়
- INSERT, UPDATE, DELETE ধীর হয়

---

## 💾 Transactions {#transactions}

### Transaction কি?
**Transaction হলো একগুচ্ছ SQL কমান্ড যা একসাথে সম্পন্ন হয় অথবা কোনোটাই হয় না।**

### ✅ ACID Properties - বিস্তারিত

#### **A - Atomicity (পরমাণুবিকতা)**
সব operations সফল হবে অথবা কোনোটাই হবে না। Partial execution হবে না।

```sql
-- Easy Example: Bank transfer
START TRANSACTION;

UPDATE accounts SET balance = balance - 1000 WHERE account_id = 'ACC001';
UPDATE accounts SET balance = balance + 1000 WHERE account_id = 'ACC002';

-- If both succeed
COMMIT;

-- If any fails
ROLLBACK;
```

```sql
-- Complex Example: Order processing
START TRANSACTION;

-- Step 1: Create order
INSERT INTO orders (customer_id, order_date, total_amount) 
VALUES (101, NOW(), 5000);

SET @order_id = LAST_INSERT_ID();

-- Step 2: Add order items
INSERT INTO order_items (order_id, product_id, quantity, price)
VALUES 
    (@order_id, 501, 2, 1500),
    (@order_id, 502, 1, 2000);

-- Step 3: Update inventory
UPDATE products SET stock = stock - 2 WHERE product_id = 501;
UPDATE products SET stock = stock - 1 WHERE product_id = 502;

-- Step 4: Record payment
INSERT INTO payments (order_id, amount, payment_date)
VALUES (@order_id, 5000, NOW());

-- All or nothing!
COMMIT;
```

#### **C - Consistency (সামঞ্জস্যতা)**
Database সবসময় valid state-এ থাকবে। সব constraints মেনে চলবে।

```sql
-- Easy Example: CHECK constraint ensures consistency
CREATE TABLE accounts (
    account_id VARCHAR(10) PRIMARY KEY,
    balance DECIMAL(10,2) CHECK (balance >= 0)  -- Can't be negative
);

-- This will fail (maintains consistency)
UPDATE accounts SET balance = -500 WHERE account_id = 'ACC001';
```

```sql
-- Complex Example: Maintaining referential integrity
START TRANSACTION;

-- Insert order (must reference existing customer)
INSERT INTO orders (customer_id, order_date)
VALUES (999, NOW());  -- Will fail if customer 999 doesn't exist

-- Update with consistency check
UPDATE inventory 
SET quantity = quantity - 10
WHERE product_id = 101 AND quantity >= 10;  -- Ensures stock won't go negative

IF ROW_COUNT() = 0 THEN
    ROLLBACK;  -- Maintain consistency
ELSE
    COMMIT;
END IF;
```

#### **I - Isolation (বিচ্ছিন্নতা)**
একটি transaction অন্য transaction দেখতে পাবে না যতক্ষণ না complete হয়।

```sql
-- Easy Example: Two transactions isolated
-- Transaction 1
START TRANSACTION;
UPDATE accounts SET balance = balance - 100 WHERE account_id = 'ACC001';
-- Not committed yet

-- Transaction 2 (running simultaneously)
SELECT balance FROM accounts WHERE account_id = 'ACC001';
-- Will see OLD value (before Transaction 1)

-- Transaction 1 commits
COMMIT;

-- Now Transaction 2 will see NEW value
```

#### **D - Durability (স্থায়িত্ব)**
একবার COMMIT হলে data permanently সংরক্ষিত হয়, system crash হলেও।

```sql
-- Easy Example
START TRANSACTION;
INSERT INTO critical_data (id, value) VALUES (1, 'Important');
COMMIT;  -- Now safe even if server crashes immediately
```

### ✅ BEGIN / START TRANSACTION - Transaction শুরু করা

```sql
-- Method 1: START TRANSACTION
START TRANSACTION;

-- Method 2: BEGIN
BEGIN;

-- Method 3: BEGIN WORK
BEGIN WORK;

-- Easy Example
START TRANSACTION;
INSERT INTO logs (message, created_at) VALUES ('User login', NOW());
COMMIT;
```

```sql
-- Complex Example: Multi-step transaction
START TRANSACTION;

-- Create new employee
INSERT INTO employees (name, department, salary, join_date)
VALUES ('Kamal Ahmed', 'IT', 65000, CURDATE());

SET @new_emp_id = LAST_INSERT_ID();

-- Assign to projects
INSERT INTO employee_projects (employee_id, project_id, role)
VALUES 
    (@new_emp_id, 101, 'Developer'),
    (@new_emp_id, 102, 'Tester');

-- Update department count
UPDATE departments 
SET employee_count = employee_count + 1 
WHERE department_name = 'IT';

-- Add to payroll
INSERT INTO payroll (employee_id, salary, pay_frequency)
VALUES (@new_emp_id, 65000, 'Monthly');

COMMIT;
```

### ✅ COMMIT - পরিবর্তন স্থায়ী করা

```sql
-- Easy Example
START TRANSACTION;
UPDATE employees SET salary = salary * 1.1 WHERE department = 'Sales';
COMMIT;  -- Changes are now permanent
```

```sql
-- Complex Example: Conditional commit
START TRANSACTION;

UPDATE inventory SET quantity = quantity - 50 WHERE product_id = 101;

-- Check if enough stock
IF (SELECT quantity FROM inventory WHERE product_id = 101) < 0 THEN
    ROLLBACK;
    SELECT 'Insufficient stock' AS message;
ELSE
    INSERT INTO sales (product_id, quantity, sale_date)
    VALUES (101, 50, NOW());
    COMMIT;
    SELECT 'Sale completed' AS message;
END IF;
```

### ✅ ROLLBACK - পরিবর্তন বাতিল করা

```sql
-- Easy Example
START TRANSACTION;
DELETE FROM employees WHERE department = 'IT';
-- Oops, mistake!
ROLLBACK;  -- Nothing deleted
```

```sql
-- Complex Example: Error handling with rollback
DELIMITER //

CREATE PROCEDURE transfer_funds(
    IN from_account VARCHAR(10),
    IN to_account VARCHAR(10),
    IN amount DECIMAL(10,2)
)
BEGIN
    DECLARE EXIT HANDLER FOR SQLEXCEPTION
    BEGIN
        ROLLBACK;
        SELECT 'Transaction failed and rolled back' AS message;
    END;
    
    START TRANSACTION;
    
    -- Deduct from sender
    UPDATE accounts 
    SET balance = balance - amount 
    WHERE account_id = from_account AND balance >= amount;
    
    IF ROW_COUNT() = 0 THEN
        SIGNAL SQLSTATE '45000' SET MESSAGE_TEXT = 'Insufficient funds';
    END IF;
    
    -- Add to receiver
    UPDATE accounts 
    SET balance = balance + amount 
    WHERE account_id = to_account;
    
    -- Log transaction
    INSERT INTO transaction_log (from_acc, to_acc, amount, trans_date)
    VALUES (from_account, to_account, amount, NOW());
    
    COMMIT;
    SELECT 'Transfer successful' AS message;
END //

DELIMITER ;
```

### ✅ SAVEPOINT - নির্দিষ্ট পয়েন্টে ফিরে যাওয়া

```sql
-- Easy Example
START TRANSACTION;

UPDATE employees SET salary = salary + 5000 WHERE department = 'IT';
SAVEPOINT after_it_raise;

UPDATE employees SET salary = salary + 3000 WHERE department = 'HR';
SAVEPOINT after_hr_raise;

-- Undo HR raise only
ROLLBACK TO after_it_raise;

-- IT raise is still there
COMMIT;
```

```sql
-- Complex Example: Multi-step data import with savepoints
START TRANSACTION;

-- Step 1: Import customers
INSERT INTO customers (name, email, city)
SELECT name, email, city FROM temp_import_customers;
SAVEPOINT customers_imported;

-- Step 2: Import orders
INSERT INTO orders (customer_id, order_date, amount)
SELECT c.id, ti.order_date, ti.amount
FROM temp_import_orders ti
INNER JOIN customers c ON ti.customer_email = c.email;
SAVEPOINT orders_imported;

-- Step 3: Import order items
INSERT INTO order_items (order_id, product_id, quantity)
SELECT o.id, tip.product_code, tip.quantity
FROM temp_import_products tip
INNER JOIN orders o ON tip.order_ref = o.reference_number;

-- If this step fails, rollback only to orders
-- ROLLBACK TO orders_imported;

-- If all successful
COMMIT;
```

### ✅ Transaction Isolation Levels

**Transaction Isolation Levels** নির্ধারণ করে একটি transaction অন্য transaction-এর পরিবর্তন কতটুকু দেখতে পাবে।

#### 1. READ UNCOMMITTED (সবচেয়ে কম isolation)

```sql
-- Dirty reads allowed
SET TRANSACTION ISOLATION LEVEL READ UNCOMMITTED;

START TRANSACTION;
-- Can see uncommitted changes from other transactions
SELECT * FROM accounts;
COMMIT;
```

**Problem: Dirty Read**
- Transaction A changes data but hasn't committed
- Transaction B can see those uncommitted changes
- If Transaction A rolls back, Transaction B saw invalid data

#### 2. READ COMMITTED (Default in many databases)

```sql
-- No dirty reads, but non-repeatable reads possible
SET TRANSACTION ISOLATION LEVEL READ COMMITTED;

START TRANSACTION;
-- Only sees committed data
SELECT * FROM accounts WHERE account_id = 'ACC001';  -- balance = 1000

-- Another transaction commits a change

SELECT * FROM accounts WHERE account_id = 'ACC001';  -- balance = 1500 (changed!)
COMMIT;
```

**Problem: Non-repeatable Read**
- Same query returns different results within same transaction

#### 3. REPEATABLE READ (MySQL Default)

```sql
-- Prevents dirty and non-repeatable reads
SET TRANSACTION ISOLATION LEVEL REPEATABLE READ;

START TRANSACTION;
SELECT * FROM accounts WHERE account_id = 'ACC001';  -- balance = 1000

-- Another transaction commits a change

SELECT * FROM accounts WHERE account_id = 'ACC001';  -- balance = 1000 (same!)
COMMIT;
```

**Problem: Phantom Read**
- New rows can appear in same query results

#### 4. SERIALIZABLE (সবচেয়ে বেশি isolation)

```sql
-- Complete isolation, transactions run serially
SET TRANSACTION ISOLATION LEVEL SERIALIZABLE;

START TRANSACTION;
SELECT * FROM accounts;
-- No other transaction can modify this data until we commit
COMMIT;
```

**No Problems but:** Slowest performance

#### Comparison Table

| Isolation Level | Dirty Read | Non-Repeatable Read | Phantom Read | Performance |
|-----------------|------------|---------------------|--------------|-------------|
| READ UNCOMMITTED | ✅ Yes | ✅ Yes | ✅ Yes | Fastest |
| READ COMMITTED | ❌ No | ✅ Yes | ✅ Yes | Fast |
| REPEATABLE READ | ❌ No | ❌ No | ✅ Yes | Medium |
| SERIALIZABLE | ❌ No | ❌ No | ❌ No | Slowest |

#### Complex Example: Using different isolation levels

```sql
-- Banking application example

-- Transaction 1: Check balance and withdraw (needs SERIALIZABLE)
SET TRANSACTION ISOLATION LEVEL SERIALIZABLE;
START TRANSACTION;

SELECT balance FROM accounts WHERE account_id = 'ACC001' FOR UPDATE;
-- Locks the row

UPDATE accounts SET balance = balance - 500 
WHERE account_id = 'ACC001' AND balance >= 500;

COMMIT;

-- Transaction 2: Read-only reports (READ COMMITTED is enough)
SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
START TRANSACTION;

SELECT 
    department,
    COUNT(*) AS employee_count,
    AVG(salary) AS avg_salary
FROM employees
GROUP BY department;

COMMIT;
```

---

## 🔧 Stored Procedures & Functions {#stored-procedures}

### Stored Procedure কি?
**Stored Procedure হলো SQL কোডের একটি সেট যা সংরক্ষণ করা হয় এবং বারবার ব্যবহার করা যায়।**

### Stored Procedure তৈরি করা

```sql
DELIMITER //

CREATE PROCEDURE GetEmployeesByDept(IN dept_name VARCHAR(30))
BEGIN
    SELECT * FROM employees WHERE department = dept_name;
END //

DELIMITER ;
```

### Stored Procedure ব্যবহার করা

```sql
CALL GetEmployeesByDept('IT');
```

### OUT Parameter সহ Procedure

```sql
DELIMITER //

CREATE PROCEDURE GetEmployeeCount(IN dept_name VARCHAR(30), OUT emp_count INT)
BEGIN
    SELECT COUNT(*) INTO emp_count 
    FROM employees 
    WHERE department = dept_name;
END //

DELIMITER ;
```

```sql
CALL GetEmployeeCount('IT', @count);
SELECT @count;
```

### Stored Function তৈরি করা

```sql
DELIMITER //

CREATE FUNCTION GetEmployeeSalary(emp_id INT) 
RETURNS DECIMAL(10,2)
DETERMINISTIC
BEGIN
    DECLARE emp_salary DECIMAL(10,2);
    SELECT salary INTO emp_salary FROM employees WHERE id = emp_id;
    RETURN emp_salary;
END //

DELIMITER ;
```

### Function ব্যবহার করা

```sql
SELECT GetEmployeeSalary(1);
```

### Procedure মুছে ফেলা

```sql
DROP PROCEDURE IF EXISTS GetEmployeesByDept;
```

### Function মুছে ফেলা

```sql
DROP FUNCTION IF EXISTS GetEmployeeSalary;
```

---

## ⚡ Triggers {#triggers}

### Trigger কি?
**Trigger হলো এমন একটি SQL কোড যা স্বয়ংক্রিয়ভাবে চলে যখন কোনো ইভেন্ট ঘটে (INSERT, UPDATE, DELETE)।**

### BEFORE INSERT Trigger

```sql
DELIMITER //

CREATE TRIGGER before_employee_insert
BEFORE INSERT ON employees
FOR EACH ROW
BEGIN
    IF NEW.salary < 0 THEN
        SET NEW.salary = 0;
    END IF;
END //

DELIMITER ;
```

### AFTER INSERT Trigger

```sql
DELIMITER //

CREATE TRIGGER after_employee_insert
AFTER INSERT ON employees
FOR EACH ROW
BEGIN
    INSERT INTO employee_audit (employee_id, action, action_date)
    VALUES (NEW.id, 'INSERT', NOW());
END //

DELIMITER ;
```

### BEFORE UPDATE Trigger

```sql
DELIMITER //

CREATE TRIGGER before_employee_update
BEFORE UPDATE ON employees
FOR EACH ROW
BEGIN
    IF NEW.salary < OLD.salary THEN
        SIGNAL SQLSTATE '45000' 
        SET MESSAGE_TEXT = 'Salary cannot be decreased';
    END IF;
END //

DELIMITER ;
```

### AFTER DELETE Trigger

```sql
DELIMITER //

CREATE TRIGGER after_employee_delete
AFTER DELETE ON employees
FOR EACH ROW
BEGIN
    INSERT INTO employee_audit (employee_id, action, action_date)
    VALUES (OLD.id, 'DELETE', NOW());
END //

DELIMITER ;
```

### Trigger দেখা

```sql
SHOW TRIGGERS;
```

### Trigger মুছে ফেলা

```sql
DROP TRIGGER IF EXISTS before_employee_insert;
```

---

## 🚀 Performance Optimization & Query Analysis {#performance-optimization}

Query performance খারাপ হওয়ার কারণে slow response time, high resource usage এবং poor user experience হতে পারে। এই section-এ comprehensive optimization techniques দেওয়া হলো।

---

### 📊 EXPLAIN and EXPLAIN ANALYZE

**EXPLAIN** query execution plan দেখায় - MySQL কীভাবে query execute করবে।
**EXPLAIN ANALYZE** actual execution করে এবং real timing data দেখায় (MySQL 8.0.18+)।

**Easy Example 1: Basic EXPLAIN**
```sql
EXPLAIN SELECT * FROM employees WHERE department = 'IT';

-- Output columns:
-- id: Query identifier
-- select_type: SIMPLE, PRIMARY, SUBQUERY, etc.
-- table: Table name
-- type: Join type (ALL, index, range, ref, eq_ref, const)
-- possible_keys: Indexes that could be used
-- key: Actually used index
-- rows: Estimated rows to examine
-- Extra: Additional information
```

**Easy Example 2: EXPLAIN with JOIN**
```sql
EXPLAIN SELECT e.name, d.department_name
FROM employees e
INNER JOIN departments d ON e.department_id = d.id
WHERE e.salary > 50000;

-- Look for:
-- type: Should be 'ref' or 'eq_ref' (good), not 'ALL' (bad - full table scan)
-- key: Should show index usage
-- rows: Lower is better
```

**Complex Example: Query optimization workflow**
```sql
-- Step 1: Check current performance
EXPLAIN SELECT 
    o.order_id,
    c.customer_name,
    p.product_name,
    oi.quantity,
    oi.price
FROM orders o
JOIN customers c ON o.customer_id = c.customer_id
JOIN order_items oi ON o.order_id = oi.order_id
JOIN products p ON oi.product_id = p.product_id
WHERE o.order_date >= '2024-01-01'
    AND o.status = 'Completed'
    AND p.category = 'Electronics';

-- If showing 'ALL' or 'index' in type column, add indexes:

-- Step 2: Add strategic indexes
CREATE INDEX idx_orders_date_status ON orders(order_date, status);
CREATE INDEX idx_products_category ON products(category);
CREATE INDEX idx_order_items_order ON order_items(order_id);
CREATE INDEX idx_order_items_product ON order_items(product_id);

-- Step 3: Verify improvement
EXPLAIN SELECT 
    o.order_id,
    c.customer_name,
    p.product_name,
    oi.quantity,
    oi.price
FROM orders o
JOIN customers c ON o.customer_id = c.customer_id
JOIN order_items oi ON o.order_id = oi.order_id
JOIN products p ON oi.product_id = p.product_id
WHERE o.order_date >= '2024-01-01'
    AND o.status = 'Completed'
    AND p.category = 'Electronics';

-- Step 4: Use EXPLAIN ANALYZE for actual timing (MySQL 8.0.18+)
EXPLAIN ANALYZE SELECT 
    o.order_id,
    c.customer_name,
    p.product_name,
    oi.quantity,
    oi.price
FROM orders o
JOIN customers c ON o.customer_id = c.customer_id
JOIN order_items oi ON o.order_id = oi.order_id
JOIN products p ON oi.product_id = p.product_id
WHERE o.order_date >= '2024-01-01'
    AND o.status = 'Completed'
    AND p.category = 'Electronics';
```

**EXPLAIN type column values (best to worst):**
```
system     - Table has only one row (best)
const      - Single row match via PRIMARY KEY or UNIQUE
eq_ref     - One row read for each combination (PRIMARY KEY/UNIQUE index)
ref        - Multiple rows with matching index value (good)
range      - Index scan with range (BETWEEN, >, <)
index      - Full index scan (better than ALL)
ALL        - Full table scan (worst - avoid this!)
```

---

### 🎯 Index Optimization Strategies

**Easy Example 1: Single column index**
```sql
-- Create index on frequently queried column
CREATE INDEX idx_employee_department ON employees(department);

-- Check index usage
EXPLAIN SELECT * FROM employees WHERE department = 'IT';
-- Should show: key = idx_employee_department, type = ref
```

**Easy Example 2: Composite index**
```sql
-- Composite index for multiple column queries
CREATE INDEX idx_emp_dept_salary ON employees(department, salary);

-- This index will be used for:
SELECT * FROM employees WHERE department = 'IT' AND salary > 50000; -- ✅ Both columns
SELECT * FROM employees WHERE department = 'IT'; -- ✅ First column only

-- But NOT for:
SELECT * FROM employees WHERE salary > 50000; -- ❌ Skips first column (leftmost prefix rule)
```

**Complex Example: Index strategy for complex queries**
```sql
-- Analyze query patterns
-- Query 1: Search by customer and date range
SELECT * FROM orders 
WHERE customer_id = 123 
    AND order_date BETWEEN '2024-01-01' AND '2024-12-31';

-- Query 2: Search by status and date
SELECT * FROM orders 
WHERE status = 'Pending' 
    AND order_date >= '2024-01-01';

-- Query 3: Get customer's recent orders
SELECT * FROM orders 
WHERE customer_id = 123 
ORDER BY order_date DESC 
LIMIT 10;

-- Optimal index strategy:
CREATE INDEX idx_orders_customer_date ON orders(customer_id, order_date DESC);
-- ✅ Covers Query 1 completely
-- ✅ Covers Query 3 with ORDER BY

CREATE INDEX idx_orders_status_date ON orders(status, order_date);
-- ✅ Covers Query 2

-- Verify with EXPLAIN
EXPLAIN SELECT * FROM orders 
WHERE customer_id = 123 
    AND order_date BETWEEN '2024-01-01' AND '2024-12-31';
-- Should show: type=range, key=idx_orders_customer_date

-- Check index usage statistics
SELECT 
    TABLE_NAME,
    INDEX_NAME,
    SEQ_IN_INDEX,
    COLUMN_NAME,
    CARDINALITY
FROM information_schema.STATISTICS
WHERE TABLE_SCHEMA = 'your_database'
    AND TABLE_NAME = 'orders'
ORDER BY TABLE_NAME, INDEX_NAME, SEQ_IN_INDEX;
```

**Covering Index Example:**
```sql
-- Create covering index (includes all columns needed by query)
CREATE INDEX idx_covering ON employees(department, salary, name, id);

-- This query doesn't need to access table (index-only scan)
EXPLAIN SELECT id, name, salary 
FROM employees 
WHERE department = 'IT' AND salary > 50000;
-- Extra: Using index condition
```

---

### ⚡ Query Optimization Techniques

**1. Selective Projection - Avoid SELECT ***

**Easy Example:**
```sql
-- ❌ BAD: Fetches all columns (wastes I/O and memory)
SELECT * FROM employees;

-- ✅ GOOD: Fetch only needed columns
SELECT id, name, email FROM employees;

-- Impact: If table has 20 columns but you need only 3,
-- you save ~85% of data transfer and processing
```

**2. Reduce Subqueries - Use JOINs**

**Easy Example:**
```sql
-- ❌ SLOW: Subquery executed for each row
SELECT name, 
    (SELECT department_name FROM departments d WHERE d.id = e.department_id) AS dept
FROM employees e;

-- ✅ FAST: Single JOIN operation
SELECT e.name, d.department_name
FROM employees e
JOIN departments d ON e.department_id = d.id;
```

**Complex Example:**
```sql
-- ❌ SLOW: Multiple subqueries
SELECT 
    e.name,
    e.salary,
    (SELECT AVG(salary) FROM employees WHERE department = e.department) AS dept_avg,
    (SELECT COUNT(*) FROM orders WHERE employee_id = e.id) AS order_count,
    (SELECT SUM(amount) FROM sales WHERE employee_id = e.id) AS total_sales
FROM employees e
WHERE e.status = 'Active';

-- ✅ FAST: Pre-aggregate with CTEs and JOIN
WITH dept_averages AS (
    SELECT department, AVG(salary) AS avg_salary
    FROM employees
    GROUP BY department
),
employee_orders AS (
    SELECT employee_id, COUNT(*) AS order_count
    FROM orders
    GROUP BY employee_id
),
employee_sales AS (
    SELECT employee_id, SUM(amount) AS total_sales
    FROM sales
    GROUP BY employee_id
)
SELECT 
    e.name,
    e.salary,
    da.avg_salary AS dept_avg,
    COALESCE(eo.order_count, 0) AS order_count,
    COALESCE(es.total_sales, 0) AS total_sales
FROM employees e
LEFT JOIN dept_averages da ON e.department = da.department
LEFT JOIN employee_orders eo ON e.id = eo.employee_id
LEFT JOIN employee_sales es ON e.id = es.employee_id
WHERE e.status = 'Active';
```

**3. Use EXISTS instead of IN for large subqueries**

**Easy Example:**
```sql
-- ❌ SLOW: IN with large subquery (loads all IDs into memory)
SELECT name FROM employees
WHERE department_id IN (
    SELECT id FROM departments WHERE region = 'Asia' -- Returns 10,000 IDs
);

-- ✅ FAST: EXISTS stops at first match
SELECT name FROM employees e
WHERE EXISTS (
    SELECT 1 FROM departments d 
    WHERE d.id = e.department_id AND d.region = 'Asia'
);
```

**4. Limit Result Sets**

**Easy Example:**
```sql
-- ❌ BAD: Returns millions of rows
SELECT * FROM log_table WHERE log_date >= '2024-01-01';

-- ✅ GOOD: Limit results
SELECT * FROM log_table 
WHERE log_date >= '2024-01-01'
ORDER BY log_date DESC
LIMIT 1000;

-- ✅ BETTER: Paginate
SELECT * FROM log_table 
WHERE log_date >= '2024-01-01'
ORDER BY log_date DESC
LIMIT 1000 OFFSET 0;  -- Page 1
```

**5. Optimize WHERE Clauses**

**Easy Example:**
```sql
-- ❌ BAD: Function on indexed column prevents index usage
SELECT * FROM employees WHERE YEAR(join_date) = 2024;

-- ✅ GOOD: Keep column untransformed
SELECT * FROM employees 
WHERE join_date >= '2024-01-01' AND join_date < '2025-01-01';

-- ❌ BAD: Leading wildcard prevents index usage
SELECT * FROM products WHERE name LIKE '%phone%';

-- ✅ GOOD: No leading wildcard
SELECT * FROM products WHERE name LIKE 'phone%';
```

**Complex Example:**
```sql
-- ❌ SLOW: Multiple inefficient conditions
SELECT * FROM orders
WHERE MONTH(order_date) = 12
    AND YEAR(order_date) = 2024
    AND UPPER(status) = 'COMPLETED'
    AND customer_id IN (SELECT id FROM customers WHERE region = 'Asia');

-- ✅ FAST: Optimized version
SELECT o.* FROM orders o
INNER JOIN customers c ON o.customer_id = c.customer_id
WHERE o.order_date >= '2024-12-01' 
    AND o.order_date < '2025-01-01'
    AND o.status = 'COMPLETED'  -- Assuming status is already uppercase in DB
    AND c.region = 'Asia';

-- Add indexes:
CREATE INDEX idx_orders_date_status ON orders(order_date, status);
CREATE INDEX idx_customers_region ON customers(region);
```

---

### 🔍 Query Performance Monitoring

**Easy Example 1: Slow query log**
```sql
-- Enable slow query log
SET GLOBAL slow_query_log = 1;
SET GLOBAL long_query_time = 2;  -- Queries taking > 2 seconds

-- Check slow queries
SELECT * FROM mysql.slow_log
ORDER BY start_time DESC
LIMIT 10;
```

**Easy Example 2: Query profiling**
```sql
-- Enable profiling
SET profiling = 1;

-- Run your query
SELECT * FROM orders WHERE customer_id = 123;

-- View profile
SHOW PROFILES;

-- Detailed profile
SHOW PROFILE FOR QUERY 1;
```

**Complex Example: Performance monitoring dashboard**
```sql
-- Get query statistics
SELECT 
    DIGEST_TEXT AS query_pattern,
    COUNT_STAR AS exec_count,
    ROUND(AVG_TIMER_WAIT / 1000000000, 3) AS avg_time_ms,
    ROUND(MAX_TIMER_WAIT / 1000000000, 3) AS max_time_ms,
    ROUND(SUM_TIMER_WAIT / 1000000000, 3) AS total_time_ms,
    ROUND(SUM_ROWS_EXAMINED / COUNT_STAR, 0) AS avg_rows_examined,
    ROUND(SUM_ROWS_SENT / COUNT_STAR, 0) AS avg_rows_returned
FROM performance_schema.events_statements_summary_by_digest
WHERE DIGEST_TEXT IS NOT NULL
ORDER BY total_time_ms DESC
LIMIT 20;

-- Index usage statistics
SELECT 
    object_schema AS database_name,
    object_name AS table_name,
    index_name,
    count_star AS times_used,
    ROUND(sum_timer_wait / 1000000000, 2) AS total_time_ms
FROM performance_schema.table_io_waits_summary_by_index_usage
WHERE index_name IS NOT NULL
    AND object_schema = 'your_database'
ORDER BY count_star DESC;

-- Table scan statistics (tables accessed without indexes)
SELECT 
    object_schema,
    object_name,
    count_read AS full_scans,
    ROUND(sum_timer_wait / 1000000000, 2) AS total_wait_ms
FROM performance_schema.table_io_waits_summary_by_table
WHERE object_schema NOT IN ('mysql', 'performance_schema', 'information_schema')
    AND count_read > 0
ORDER BY count_read DESC
LIMIT 20;
```

---

### 📈 Advanced Optimization Techniques

**1. Partitioning**

**Easy Example:**
```sql
-- Partition large table by date range
CREATE TABLE orders_partitioned (
    order_id INT,
    customer_id INT,
    order_date DATE,
    order_total DECIMAL(10,2)
) PARTITION BY RANGE (YEAR(order_date)) (
    PARTITION p2022 VALUES LESS THAN (2023),
    PARTITION p2023 VALUES LESS THAN (2024),
    PARTITION p2024 VALUES LESS THAN (2025),
    PARTITION p_future VALUES LESS THAN MAXVALUE
);

-- Query specific partition (much faster)
SELECT * FROM orders_partitioned
WHERE order_date >= '2024-01-01' AND order_date < '2025-01-01';
-- MySQL automatically queries only p2024 partition
```

**2. Query Cache (MySQL 5.7 and older)**

```sql
-- Check cache status
SHOW VARIABLES LIKE 'query_cache%';

-- Enable query cache
SET GLOBAL query_cache_size = 67108864;  -- 64MB
SET GLOBAL query_cache_type = ON;
```

**3. Batch Operations**

**Easy Example:**
```sql
-- ❌ SLOW: Individual inserts (1000 queries)
INSERT INTO logs (message, timestamp) VALUES ('Log 1', NOW());
INSERT INTO logs (message, timestamp) VALUES ('Log 2', NOW());
-- ... 998 more

-- ✅ FAST: Batch insert (1 query)
INSERT INTO logs (message, timestamp) VALUES
('Log 1', NOW()),
('Log 2', NOW()),
('Log 3', NOW());
-- ... up to 1000 rows

-- Even better: Use LOAD DATA INFILE for bulk operations
LOAD DATA LOCAL INFILE '/path/to/data.csv'
INTO TABLE logs
FIELDS TERMINATED BY ','
LINES TERMINATED BY '\n'
(message, timestamp);
```

---

### Query Execution Order

Understanding this helps optimize queries:

1. **FROM** - টেবিল এবং JOINs নির্বাচন
2. **WHERE** - Row filtering (indexes used here)
3. **GROUP BY** - Rows গ্রুপ করা
4. **HAVING** - Group filtering
5. **SELECT** - Columns নির্বাচন এবং calculations
6. **DISTINCT** - Duplicate removal
7. **ORDER BY** - Results সাজানো
8. **LIMIT / OFFSET** - Results সীমিত করা

**Optimization based on order:**
- Filters (WHERE) execute before aggregations - put filters here, not in HAVING
- GROUP BY before SELECT - can't use column aliases in GROUP BY
- ORDER BY is expensive - avoid on large datasets or add index
- LIMIT reduces final output - use early when possible

---

## 📋 Common Table Expressions (CTEs)

**CTE (Common Table Expression)** হলো temporary result set যা একটি query-র মধ্যে define করা হয় এবং শুধুমাত্র সেই query-র scope-এ available থাকে। এটি query-কে আরো readable এবং maintainable করে তোলে।

### 📖 CTE Syntax

```sql
WITH cte_name AS (
    SELECT ...
)
SELECT * FROM cte_name;

-- Multiple CTEs
WITH 
cte1 AS (SELECT ...),
cte2 AS (SELECT ...),
cte3 AS (SELECT ...)
SELECT * FROM cte1 JOIN cte2 ON ... JOIN cte3 ON ...;
```

**Benefits of CTEs:**
- ✅ Code reusability - একই CTE একাধিকবার reference করা যায়
- ✅ Improved readability - Complex queries-কে smaller, manageable parts-এ ভাগ করা যায়
- ✅ Recursive queries - Hierarchical data traverse করা যায়
- ✅ Better performance - Subquery-র চেয়ে efficient হতে পারে

---

### 1️⃣ Simple CTE

**Easy Example 1: Basic filtering**
```sql
WITH high_salary_employees AS (
    SELECT id, name, department, salary
    FROM employees
    WHERE salary > 60000
)
SELECT 
    department,
    COUNT(*) AS employee_count,
    ROUND(AVG(salary), 2) AS avg_salary
FROM high_salary_employees
GROUP BY department;
```

**Easy Example 2: Date-based filtering**
```sql
WITH recent_orders AS (
    SELECT *
    FROM orders
    WHERE order_date >= DATE_SUB(CURDATE(), INTERVAL 30 DAY)
)
SELECT 
    customer_id,
    COUNT(*) AS order_count,
    SUM(order_total) AS total_spent
FROM recent_orders
GROUP BY customer_id
ORDER BY total_spent DESC
LIMIT 10;
```

**Complex Example: Multi-step calculation**
```sql
-- Calculate employee performance score based on multiple factors
WITH 
-- Step 1: Get sales performance
sales_performance AS (
    SELECT 
        e.id AS employee_id,
        e.name,
        e.department,
        COALESCE(SUM(s.sale_amount), 0) AS total_sales,
        COALESCE(COUNT(s.sale_id), 0) AS sale_count
    FROM employees e
    LEFT JOIN sales s ON e.id = s.employee_id 
        AND s.sale_date >= DATE_SUB(CURDATE(), INTERVAL 90 DAY)
    GROUP BY e.id, e.name, e.department
),
-- Step 2: Get attendance record
attendance_record AS (
    SELECT 
        employee_id,
        COUNT(CASE WHEN status = 'Present' THEN 1 END) AS days_present,
        COUNT(CASE WHEN status = 'Late' THEN 1 END) AS days_late,
        COUNT(*) AS total_working_days
    FROM attendance
    WHERE attendance_date >= DATE_SUB(CURDATE(), INTERVAL 90 DAY)
    GROUP BY employee_id
),
-- Step 3: Get customer ratings
customer_ratings AS (
    SELECT 
        employee_id,
        AVG(rating) AS avg_customer_rating,
        COUNT(*) AS total_ratings
    FROM customer_feedback
    WHERE feedback_date >= DATE_SUB(CURDATE(), INTERVAL 90 DAY)
    GROUP BY employee_id
),
-- Step 4: Calculate performance score
performance_scores AS (
    SELECT 
        sp.employee_id,
        sp.name,
        sp.department,
        sp.total_sales,
        sp.sale_count,
        COALESCE(ar.days_present, 0) AS days_present,
        COALESCE(ar.total_working_days, 0) AS total_days,
        COALESCE(cr.avg_customer_rating, 0) AS avg_rating,
        -- Performance calculation
        (
            -- Sales score (40%)
            (CASE 
                WHEN sp.total_sales >= 100000 THEN 40
                WHEN sp.total_sales >= 50000 THEN 30
                WHEN sp.total_sales >= 25000 THEN 20
                ELSE 10
            END) +
            -- Attendance score (30%)
            (CASE 
                WHEN COALESCE(ar.days_present / NULLIF(ar.total_working_days, 0), 0) >= 0.95 THEN 30
                WHEN COALESCE(ar.days_present / NULLIF(ar.total_working_days, 0), 0) >= 0.85 THEN 20
                WHEN COALESCE(ar.days_present / NULLIF(ar.total_working_days, 0), 0) >= 0.75 THEN 10
                ELSE 0
            END) +
            -- Customer rating score (30%)
            (COALESCE(cr.avg_customer_rating, 0) * 6)
        ) AS performance_score
    FROM sales_performance sp
    LEFT JOIN attendance_record ar ON sp.employee_id = ar.employee_id
    LEFT JOIN customer_ratings cr ON sp.employee_id = cr.employee_id
)
SELECT 
    name,
    department,
    total_sales,
    sale_count,
    days_present,
    total_days,
    ROUND(avg_rating, 2) AS customer_rating,
    ROUND(performance_score, 2) AS final_score,
    CASE 
        WHEN performance_score >= 80 THEN 'Excellent'
        WHEN performance_score >= 60 THEN 'Good'
        WHEN performance_score >= 40 THEN 'Average'
        ELSE 'Needs Improvement'
    END AS performance_grade,
    RANK() OVER (PARTITION BY department ORDER BY performance_score DESC) AS dept_rank
FROM performance_scores
ORDER BY performance_score DESC;
```

---

### 2️⃣ Multiple CTEs

**Easy Example 1: Sequential calculations**
```sql
WITH 
monthly_sales AS (
    SELECT 
        DATE_FORMAT(order_date, '%Y-%m') AS month,
        SUM(order_total) AS total_sales
    FROM orders
    GROUP BY DATE_FORMAT(order_date, '%Y-%m')
),
sales_with_growth AS (
    SELECT 
        month,
        total_sales,
        LAG(total_sales) OVER (ORDER BY month) AS prev_month_sales,
        ROUND(
            ((total_sales - LAG(total_sales) OVER (ORDER BY month)) / 
            LAG(total_sales) OVER (ORDER BY month)) * 100,
            2
        ) AS growth_percent
    FROM monthly_sales
)
SELECT * FROM sales_with_growth WHERE growth_percent IS NOT NULL;
```

**Easy Example 2: Joining multiple CTEs**
```sql
WITH 
customer_orders AS (
    SELECT 
        customer_id,
        COUNT(*) AS order_count,
        SUM(order_total) AS lifetime_value
    FROM orders
    GROUP BY customer_id
),
customer_reviews AS (
    SELECT 
        customer_id,
        AVG(rating) AS avg_rating,
        COUNT(*) AS review_count
    FROM reviews
    GROUP BY customer_id
)
SELECT 
    c.customer_id,
    c.name,
    COALESCE(co.order_count, 0) AS orders,
    COALESCE(co.lifetime_value, 0) AS total_spent,
    COALESCE(cr.avg_rating, 0) AS rating,
    COALESCE(cr.review_count, 0) AS reviews
FROM customers c
LEFT JOIN customer_orders co ON c.customer_id = co.customer_id
LEFT JOIN customer_reviews cr ON c.customer_id = cr.customer_id;
```

**Complex Example: Data warehouse style reporting**
```sql
-- Comprehensive business intelligence report
WITH 
-- Dimension: Time periods
time_periods AS (
    SELECT DISTINCT
        DATE_FORMAT(order_date, '%Y') AS year,
        DATE_FORMAT(order_date, '%Y-%m') AS month,
        QUARTER(order_date) AS quarter,
        DATE_FORMAT(order_date, '%Y-Q%q') AS year_quarter
    FROM orders
),
-- Fact: Product sales
product_sales AS (
    SELECT 
        DATE_FORMAT(o.order_date, '%Y-%m') AS month,
        p.category,
        p.product_name,
        COUNT(DISTINCT o.order_id) AS order_count,
        SUM(oi.quantity) AS units_sold,
        SUM(oi.quantity * oi.price) AS revenue,
        SUM(oi.quantity * oi.price - oi.quantity * p.cost) AS profit
    FROM orders o
    JOIN order_items oi ON o.order_id = oi.order_id
    JOIN products p ON oi.product_id = p.product_id
    GROUP BY DATE_FORMAT(o.order_date, '%Y-%m'), p.category, p.product_name
),
-- Aggregate: Category performance
category_summary AS (
    SELECT 
        month,
        category,
        SUM(units_sold) AS total_units,
        SUM(revenue) AS total_revenue,
        SUM(profit) AS total_profit,
        ROUND(AVG(revenue / NULLIF(units_sold, 0)), 2) AS avg_selling_price,
        ROUND((SUM(profit) / NULLIF(SUM(revenue), 0)) * 100, 2) AS profit_margin_pct
    FROM product_sales
    GROUP BY month, category
),
-- Ranking: Top products per category
top_products AS (
    SELECT 
        month,
        category,
        product_name,
        revenue,
        ROW_NUMBER() OVER (PARTITION BY month, category ORDER BY revenue DESC) AS product_rank
    FROM product_sales
),
-- Trend: Growth calculation
category_growth AS (
    SELECT 
        month,
        category,
        total_revenue,
        LAG(total_revenue) OVER (PARTITION BY category ORDER BY month) AS prev_month_revenue,
        ROUND(
            ((total_revenue - LAG(total_revenue) OVER (PARTITION BY category ORDER BY month)) /
            NULLIF(LAG(total_revenue) OVER (PARTITION BY category ORDER BY month), 0)) * 100,
            2
        ) AS mom_growth_pct
    FROM category_summary
)
-- Final report: Combine all metrics
SELECT 
    cs.month,
    cs.category,
    cs.total_units,
    ROUND(cs.total_revenue, 2) AS revenue,
    ROUND(cs.total_profit, 2) AS profit,
    cs.profit_margin_pct,
    COALESCE(cg.mom_growth_pct, 0) AS growth_pct,
    tp.product_name AS top_product,
    ROUND(tp.revenue, 2) AS top_product_revenue,
    RANK() OVER (PARTITION BY cs.month ORDER BY cs.total_revenue DESC) AS category_rank,
    CASE 
        WHEN cg.mom_growth_pct > 10 THEN 'Strong Growth'
        WHEN cg.mom_growth_pct > 0 THEN 'Growing'
        WHEN cg.mom_growth_pct = 0 THEN 'Stable'
        WHEN cg.mom_growth_pct > -10 THEN 'Declining'
        ELSE 'Critical'
    END AS trend_status
FROM category_summary cs
LEFT JOIN category_growth cg ON cs.month = cg.month AND cs.category = cg.category
LEFT JOIN top_products tp ON cs.month = tp.month AND cs.category = tp.category AND tp.product_rank = 1
ORDER BY cs.month DESC, cs.total_revenue DESC;
```

---

### 3️⃣ Recursive CTEs

**Recursive CTE** নিজেকে reference করে এবং hierarchical বা tree-structured data traverse করতে ব্যবহৃত হয়।

**Syntax:**
```sql
WITH RECURSIVE cte_name AS (
    -- Base case (anchor member)
    SELECT ...
    
    UNION ALL
    
    -- Recursive case (recursive member)
    SELECT ... FROM cte_name ...
)
SELECT * FROM cte_name;
```

**Easy Example 1: Number sequence**
```sql
-- Generate numbers from 1 to 10
WITH RECURSIVE numbers AS (
    SELECT 1 AS n
    UNION ALL
    SELECT n + 1 FROM numbers WHERE n < 10
)
SELECT * FROM numbers;
```

**Easy Example 2: Date sequence**
```sql
-- Generate all dates in current month
WITH RECURSIVE date_series AS (
    SELECT DATE_FORMAT(CURDATE(), '%Y-%m-01') AS date
    UNION ALL
    SELECT DATE_ADD(date, INTERVAL 1 DAY)
    FROM date_series
    WHERE date < LAST_DAY(CURDATE())
)
SELECT 
    date,
    DAYNAME(date) AS day_name,
    CASE WHEN DAYOFWEEK(date) IN (1, 7) THEN 'Weekend' ELSE 'Weekday' END AS day_type
FROM date_series;
```

**Complex Example: Employee hierarchy**
```sql
-- Complete organizational hierarchy with all levels
WITH RECURSIVE org_hierarchy AS (
    -- Base case: CEO/Top level (no manager)
    SELECT 
        id,
        name,
        manager_id,
        department,
        salary,
        1 AS level,
        CAST(name AS CHAR(500)) AS hierarchy_path,
        CAST(id AS CHAR(500)) AS id_path
    FROM employees
    WHERE manager_id IS NULL
    
    UNION ALL
    
    -- Recursive case: Subordinates
    SELECT 
        e.id,
        e.name,
        e.manager_id,
        e.department,
        e.salary,
        oh.level + 1,
        CONCAT(oh.hierarchy_path, ' > ', e.name),
        CONCAT(oh.id_path, ',', e.id)
    FROM employees e
    INNER JOIN org_hierarchy oh ON e.manager_id = oh.id
    WHERE oh.level < 10  -- Prevent infinite loops
)
SELECT 
    level,
    REPEAT('  ', level - 1) AS indentation,
    CONCAT(REPEAT('  ', level - 1), name) AS employee_hierarchy,
    department,
    salary,
    hierarchy_path,
    manager_id,
    (SELECT name FROM employees WHERE id = org_hierarchy.manager_id) AS manager_name,
    (SELECT COUNT(*) FROM employees WHERE manager_id = org_hierarchy.id) AS direct_reports
FROM org_hierarchy
ORDER BY id_path;

-- Find all subordinates of a specific manager (including indirect)
WITH RECURSIVE subordinates AS (
    -- Base case: The manager
    SELECT id, name, manager_id, 0 AS distance
    FROM employees
    WHERE id = 5  -- Manager ID
    
    UNION ALL
    
    -- Recursive case: Direct and indirect subordinates
    SELECT e.id, e.name, e.manager_id, s.distance + 1
    FROM employees e
    INNER JOIN subordinates s ON e.manager_id = s.id
)
SELECT 
    name,
    distance,
    CASE distance
        WHEN 0 THEN 'Manager'
        WHEN 1 THEN 'Direct Report'
        ELSE CONCAT('Level ', distance, ' Subordinate')
    END AS relationship
FROM subordinates
ORDER BY distance, name;
```

---

### 4️⃣ CTEs with Aggregations

**Easy Example 1: Department statistics**
```sql
WITH dept_stats AS (
    SELECT 
        department,
        COUNT(*) AS emp_count,
        AVG(salary) AS avg_salary,
        MAX(salary) AS max_salary,
        MIN(salary) AS min_salary
    FROM employees
    GROUP BY department
)
SELECT 
    e.name,
    e.department,
    e.salary,
    ds.avg_salary AS dept_avg,
    ROUND(e.salary - ds.avg_salary, 2) AS diff_from_avg,
    ROUND((e.salary / ds.avg_salary - 1) * 100, 2) AS pct_diff_from_avg
FROM employees e
JOIN dept_stats ds ON e.department = ds.department
ORDER BY e.department, e.salary DESC;
```

**Easy Example 2: Running totals with CTE**
```sql
WITH daily_sales AS (
    SELECT 
        DATE(order_date) AS sale_date,
        SUM(order_total) AS daily_total
    FROM orders
    GROUP BY DATE(order_date)
)
SELECT 
    sale_date,
    daily_total,
    SUM(daily_total) OVER (ORDER BY sale_date) AS running_total,
    AVG(daily_total) OVER (
        ORDER BY sale_date 
        ROWS BETWEEN 6 PRECEDING AND CURRENT ROW
    ) AS seven_day_avg
FROM daily_sales
ORDER BY sale_date;
```

**Complex Example: Cohort analysis**
```sql
-- Customer cohort retention analysis
WITH 
-- Step 1: Identify first purchase month for each customer
customer_cohort AS (
    SELECT 
        customer_id,
        DATE_FORMAT(MIN(order_date), '%Y-%m') AS cohort_month
    FROM orders
    GROUP BY customer_id
),
-- Step 2: All orders with cohort information
orders_with_cohort AS (
    SELECT 
        o.customer_id,
        cc.cohort_month,
        DATE_FORMAT(o.order_date, '%Y-%m') AS order_month,
        TIMESTAMPDIFF(MONTH, 
            STR_TO_DATE(CONCAT(cc.cohort_month, '-01'), '%Y-%m-%d'),
            STR_TO_DATE(CONCAT(DATE_FORMAT(o.order_date, '%Y-%m'), '-01'), '%Y-%m-%d')
        ) AS months_since_first_purchase
    FROM orders o
    JOIN customer_cohort cc ON o.customer_id = cc.customer_id
),
-- Step 3: Count unique customers in each cohort/month combination
cohort_counts AS (
    SELECT 
        cohort_month,
        months_since_first_purchase,
        COUNT(DISTINCT customer_id) AS customer_count
    FROM orders_with_cohort
    GROUP BY cohort_month, months_since_first_purchase
),
-- Step 4: Get cohort sizes (month 0)
cohort_sizes AS (
    SELECT 
        cohort_month,
        customer_count AS cohort_size
    FROM cohort_counts
    WHERE months_since_first_purchase = 0
)
-- Step 5: Calculate retention percentages
SELECT 
    cc.cohort_month,
    cs.cohort_size,
    cc.months_since_first_purchase AS month_number,
    cc.customer_count AS retained_customers,
    ROUND((cc.customer_count * 100.0 / cs.cohort_size), 2) AS retention_pct,
    CASE 
        WHEN cc.months_since_first_purchase = 0 THEN 'New Customers'
        WHEN cc.months_since_first_purchase = 1 THEN 'Month 1'
        WHEN cc.months_since_first_purchase <= 3 THEN 'Quarter 1'
        WHEN cc.months_since_first_purchase <= 6 THEN 'Quarter 2'
        WHEN cc.months_since_first_purchase <= 12 THEN 'Year 1'
        ELSE 'Long-term'
    END AS retention_period
FROM cohort_counts cc
JOIN cohort_sizes cs ON cc.cohort_month = cs.cohort_month
WHERE cc.months_since_first_purchase <= 12  -- First year retention
ORDER BY cc.cohort_month, cc.months_since_first_purchase;
```

---

### 5️⃣ CTEs for Data Transformation

**Easy Example 1: Pivoting data**
```sql
-- Transform rows to columns
WITH monthly_data AS (
    SELECT 
        product_name,
        DATE_FORMAT(order_date, '%Y-%m') AS month,
        SUM(quantity * price) AS revenue
    FROM orders o
    JOIN order_items oi ON o.order_id = oi.order_id
    JOIN products p ON oi.product_id = p.product_id
    WHERE order_date >= DATE_SUB(CURDATE(), INTERVAL 3 MONTH)
    GROUP BY product_name, DATE_FORMAT(order_date, '%Y-%m')
)
SELECT 
    product_name,
    SUM(CASE WHEN month = DATE_FORMAT(DATE_SUB(CURDATE(), INTERVAL 2 MONTH), '%Y-%m') 
        THEN revenue ELSE 0 END) AS month_1,
    SUM(CASE WHEN month = DATE_FORMAT(DATE_SUB(CURDATE(), INTERVAL 1 MONTH), '%Y-%m') 
        THEN revenue ELSE 0 END) AS month_2,
    SUM(CASE WHEN month = DATE_FORMAT(CURDATE(), '%Y-%m') 
        THEN revenue ELSE 0 END) AS month_3,
    SUM(revenue) AS total
FROM monthly_data
GROUP BY product_name
ORDER BY total DESC;
```

**Easy Example 2: Data cleansing**
```sql
WITH cleaned_data AS (
    SELECT 
        id,
        TRIM(UPPER(name)) AS name,
        REPLACE(REPLACE(phone, '-', ''), ' ', '') AS phone,
        LOWER(TRIM(email)) AS email,
        CASE 
            WHEN status IS NULL OR status = '' THEN 'Unknown'
            ELSE status
        END AS status
    FROM customers
)
SELECT * FROM cleaned_data WHERE email LIKE '%@%.%';
```

**Complex Example: Advanced data transformation pipeline**
```sql
-- Multi-stage data transformation for analytics
WITH 
-- Stage 1: Raw data extraction
raw_transactions AS (
    SELECT 
        t.transaction_id,
        t.customer_id,
        c.customer_name,
        c.customer_segment,
        t.transaction_date,
        t.amount,
        t.transaction_type,
        t.payment_method,
        t.status
    FROM transactions t
    JOIN customers c ON t.customer_id = c.customer_id
    WHERE t.transaction_date >= DATE_SUB(CURDATE(), INTERVAL 6 MONTH)
),
-- Stage 2: Data validation and cleansing
validated_transactions AS (
    SELECT 
        transaction_id,
        customer_id,
        COALESCE(customer_name, 'Unknown') AS customer_name,
        COALESCE(customer_segment, 'Unclassified') AS customer_segment,
        transaction_date,
        CASE 
            WHEN amount < 0 THEN 0
            WHEN amount > 1000000 THEN 1000000  -- Cap extreme values
            ELSE amount
        END AS amount,
        transaction_type,
        payment_method,
        status
    FROM raw_transactions
    WHERE status = 'Completed'  -- Only completed transactions
        AND amount IS NOT NULL
),
-- Stage 3: Enrichment with calculated fields
enriched_transactions AS (
    SELECT 
        *,
        DATE_FORMAT(transaction_date, '%Y-%m') AS month,
        QUARTER(transaction_date) AS quarter,
        DAYNAME(transaction_date) AS day_of_week,
        CASE 
            WHEN amount < 100 THEN 'Small'
            WHEN amount < 1000 THEN 'Medium'
            WHEN amount < 10000 THEN 'Large'
            ELSE 'Extra Large'
        END AS transaction_size,
        CASE 
            WHEN HOUR(transaction_date) BETWEEN 6 AND 11 THEN 'Morning'
            WHEN HOUR(transaction_date) BETWEEN 12 AND 17 THEN 'Afternoon'
            WHEN HOUR(transaction_date) BETWEEN 18 AND 22 THEN 'Evening'
            ELSE 'Night'
        END AS time_of_day
    FROM validated_transactions
),
-- Stage 4: Aggregation
customer_metrics AS (
    SELECT 
        customer_id,
        customer_name,
        customer_segment,
        COUNT(*) AS transaction_count,
        SUM(amount) AS total_amount,
        AVG(amount) AS avg_transaction,
        MAX(amount) AS max_transaction,
        MIN(transaction_date) AS first_transaction,
        MAX(transaction_date) AS last_transaction,
        DATEDIFF(MAX(transaction_date), MIN(transaction_date)) AS customer_lifetime_days,
        COUNT(DISTINCT month) AS active_months
    FROM enriched_transactions
    GROUP BY customer_id, customer_name, customer_segment
),
-- Stage 5: Scoring and classification
customer_scores AS (
    SELECT 
        *,
        CASE 
            WHEN total_amount >= 50000 AND transaction_count >= 20 THEN 'VIP'
            WHEN total_amount >= 20000 OR transaction_count >= 10 THEN 'Premium'
            WHEN total_amount >= 5000 OR transaction_count >= 5 THEN 'Standard'
            ELSE 'Basic'
        END AS customer_tier,
        NTILE(10) OVER (ORDER BY total_amount DESC) AS value_decile,
        NTILE(4) OVER (ORDER BY transaction_count DESC) AS frequency_quartile
    FROM customer_metrics
)
-- Stage 6: Final output with recommendations
SELECT 
    customer_name,
    customer_segment,
    customer_tier,
    transaction_count,
    ROUND(total_amount, 2) AS lifetime_value,
    ROUND(avg_transaction, 2) AS avg_order_value,
    active_months,
    DATEDIFF(CURDATE(), last_transaction) AS days_since_last_purchase,
    CASE 
        WHEN DATEDIFF(CURDATE(), last_transaction) > 90 THEN 'At Risk'
        WHEN DATEDIFF(CURDATE(), last_transaction) > 60 THEN 'Needs Attention'
        ELSE 'Active'
    END AS engagement_status,
    CASE 
        WHEN customer_tier = 'VIP' AND DATEDIFF(CURDATE(), last_transaction) <= 30 
            THEN 'Maintain with exclusive offers'
        WHEN customer_tier IN ('VIP', 'Premium') AND DATEDIFF(CURDATE(), last_transaction) > 60 
            THEN 'Re-engage with personalized campaign'
        WHEN customer_tier = 'Standard' AND value_decile <= 5 
            THEN 'Upsell opportunity'
        WHEN DATEDIFF(CURDATE(), last_transaction) > 90 
            THEN 'Win-back campaign'
        ELSE 'Regular communication'
    END AS recommended_action
FROM customer_scores
ORDER BY lifetime_value DESC;
```

---

### 🎯 CTE Best Practices

1. **Use descriptive names** - CTE-র নাম meaningful হওয়া উচিত
2. **Break complex logic** - বড় queries-কে ছোট CTEs-এ ভাগ করুন
3. **Reuse CTEs** - একই CTE multiple times reference করা যায়
4. **Add comments** - প্রতিটি CTE-র purpose explain করুন
5. **Limit recursion depth** - Recursive CTEs-এ termination condition দিন
6. **Consider materialization** - Complex CTEs repeatedly used হলে temp table বিবেচনা করুন

---

## 🪟 Window Functions (Advanced SQL)

**Window Functions** হলো বিশেষ ধরনের function যা একটি "window" বা row-এর একটি set-এর উপর calculation করে। Normal aggregate functions-এর মতো rows group করে না, বরং প্রতিটি row-এর জন্য আলাদাভাবে result দেয়।

### 📖 Window Function Syntax

```sql
window_function(expression) OVER (
    [PARTITION BY partition_expression]
    [ORDER BY sort_expression [ASC | DESC]]
    [ROWS/RANGE frame_clause]
)
```

**Components:**
- `PARTITION BY`: Data কে groups-এ ভাগ করে (optional)
- `ORDER BY`: Window-এর মধ্যে rows-এর order নির্ধারণ করে (optional)
- `ROWS/RANGE`: Window frame নির্ধারণ করে (optional)

---

### 1️⃣ ROW_NUMBER() - Row Numbering

প্রতিটি row-কে একটি unique sequential number assign করে।

**Easy Example 1: Simple row numbering**
```sql
SELECT 
    name,
    department,
    salary,
    ROW_NUMBER() OVER (ORDER BY salary DESC) AS row_num
FROM employees;
```

**Easy Example 2: Row number within each department**
```sql
SELECT 
    name,
    department,
    salary,
    ROW_NUMBER() OVER (PARTITION BY department ORDER BY salary DESC) AS dept_rank
FROM employees;
```

**Complex Example: Find top 2 earners per department**
```sql
WITH ranked_employees AS (
    SELECT 
        id,
        name,
        department,
        salary,
        join_date,
        ROW_NUMBER() OVER (
            PARTITION BY department 
            ORDER BY salary DESC, join_date ASC
        ) AS salary_rank
    FROM employees
)
SELECT 
    department,
    name,
    salary,
    join_date,
    salary_rank
FROM ranked_employees
WHERE salary_rank <= 2
ORDER BY department, salary_rank;

-- Use Case: পেজিনেশন (pagination)
WITH numbered_products AS (
    SELECT 
        product_id,
        product_name,
        price,
        ROW_NUMBER() OVER (ORDER BY product_name) AS row_num
    FROM products
)
SELECT product_id, product_name, price
FROM numbered_products
WHERE row_num BETWEEN 21 AND 30;  -- Page 3, 10 items per page
```

---

### 2️⃣ RANK() - Ranking with Gaps

Rows-কে rank করে, same value থাকলে same rank দেয় এবং পরবর্তী rank skip করে।

**Easy Example 1: Overall ranking**
```sql
SELECT 
    name,
    score,
    RANK() OVER (ORDER BY score DESC) AS rank_position
FROM students;
-- Score: 95, 90, 90, 85 → Rank: 1, 2, 2, 4 (3 is skipped)
```

**Easy Example 2: Ranking by category**
```sql
SELECT 
    product_name,
    category,
    price,
    RANK() OVER (PARTITION BY category ORDER BY price DESC) AS price_rank
FROM products;
```

**Complex Example: Compare multiple ranking methods**
```sql
SELECT 
    name,
    department,
    salary,
    RANK() OVER (PARTITION BY department ORDER BY salary DESC) AS rank_with_gaps,
    DENSE_RANK() OVER (PARTITION BY department ORDER BY salary DESC) AS rank_no_gaps,
    ROW_NUMBER() OVER (PARTITION BY department ORDER BY salary DESC) AS row_num,
    PERCENT_RANK() OVER (PARTITION BY department ORDER BY salary DESC) AS percentile_rank,
    CASE 
        WHEN RANK() OVER (PARTITION BY department ORDER BY salary DESC) = 1 
        THEN 'Top Performer'
        WHEN RANK() OVER (PARTITION BY department ORDER BY salary DESC) <= 3 
        THEN 'High Performer'
        ELSE 'Regular'
    END AS performance_category
FROM employees
ORDER BY department, salary DESC;

-- Real scenario: Employee performance with salary percentile
WITH salary_stats AS (
    SELECT 
        e.*,
        RANK() OVER (ORDER BY salary DESC) AS overall_rank,
        PERCENT_RANK() OVER (ORDER BY salary) AS salary_percentile,
        AVG(salary) OVER (PARTITION BY department) AS dept_avg_salary
    FROM employees e
)
SELECT 
    name,
    department,
    salary,
    overall_rank,
    ROUND(salary_percentile * 100, 2) AS percentile,
    ROUND(dept_avg_salary, 2) AS dept_avg,
    ROUND(((salary - dept_avg_salary) / dept_avg_salary) * 100, 2) AS variance_from_avg
FROM salary_stats
WHERE overall_rank <= 10;
```

---

### 3️⃣ DENSE_RANK() - Ranking without Gaps

RANK()-এর মতো কিন্তু gaps skip করে না।

**Easy Example 1: Dense ranking**
```sql
SELECT 
    name,
    score,
    DENSE_RANK() OVER (ORDER BY score DESC) AS dense_rank
FROM students;
-- Score: 95, 90, 90, 85 → Rank: 1, 2, 2, 3 (no skip)
```

**Easy Example 2: Product ranking**
```sql
SELECT 
    product_name,
    sales_count,
    DENSE_RANK() OVER (ORDER BY sales_count DESC) AS popularity_rank
FROM product_sales;
```

**Complex Example: Multi-level ranking**
```sql
-- Find products that rank in top 3 in multiple metrics
WITH product_rankings AS (
    SELECT 
        p.product_id,
        p.product_name,
        p.category,
        COUNT(o.order_id) AS order_count,
        SUM(o.quantity) AS total_quantity,
        SUM(o.quantity * o.price) AS revenue,
        DENSE_RANK() OVER (PARTITION BY p.category ORDER BY COUNT(o.order_id) DESC) AS order_rank,
        DENSE_RANK() OVER (PARTITION BY p.category ORDER BY SUM(o.quantity) DESC) AS quantity_rank,
        DENSE_RANK() OVER (PARTITION BY p.category ORDER BY SUM(o.quantity * o.price) DESC) AS revenue_rank
    FROM products p
    LEFT JOIN orders o ON p.product_id = o.product_id
    GROUP BY p.product_id, p.product_name, p.category
)
SELECT 
    category,
    product_name,
    order_count,
    total_quantity,
    ROUND(revenue, 2) AS revenue,
    order_rank,
    quantity_rank,
    revenue_rank,
    CASE 
        WHEN order_rank <= 3 AND quantity_rank <= 3 AND revenue_rank <= 3 
        THEN 'Star Product'
        WHEN order_rank <= 3 OR quantity_rank <= 3 OR revenue_rank <= 3 
        THEN 'Top Performer'
        ELSE 'Regular'
    END AS product_category
FROM product_rankings
WHERE order_rank <= 5 OR quantity_rank <= 5 OR revenue_rank <= 5
ORDER BY category, revenue DESC;
```

---

### 4️⃣ NTILE(n) - Divide into Buckets

Data-কে n সংখ্যক equal buckets/groups-এ ভাগ করে।

**Easy Example 1: Quartiles (4 groups)**
```sql
SELECT 
    name,
    salary,
    NTILE(4) OVER (ORDER BY salary) AS salary_quartile
FROM employees;
-- 1=bottom 25%, 2=25-50%, 3=50-75%, 4=top 25%
```

**Easy Example 2: Divide students into 3 performance groups**
```sql
SELECT 
    name,
    total_marks,
    NTILE(3) OVER (ORDER BY total_marks DESC) AS performance_group,
    CASE NTILE(3) OVER (ORDER BY total_marks DESC)
        WHEN 1 THEN 'High'
        WHEN 2 THEN 'Medium'
        WHEN 3 THEN 'Low'
    END AS performance_label
FROM students;
```

**Complex Example: Portfolio analysis with deciles**
```sql
-- Categorize customers into 10 segments based on lifetime value
WITH customer_analysis AS (
    SELECT 
        c.customer_id,
        c.customer_name,
        c.join_date,
        COUNT(DISTINCT o.order_id) AS total_orders,
        SUM(o.order_total) AS lifetime_value,
        AVG(o.order_total) AS avg_order_value,
        DATEDIFF(CURDATE(), MAX(o.order_date)) AS days_since_last_order,
        NTILE(10) OVER (ORDER BY SUM(o.order_total) DESC) AS value_decile,
        NTILE(4) OVER (ORDER BY COUNT(DISTINCT o.order_id) DESC) AS frequency_quartile
    FROM customers c
    LEFT JOIN orders o ON c.customer_id = o.customer_id
    GROUP BY c.customer_id, c.customer_name, c.join_date
)
SELECT 
    value_decile,
    COUNT(*) AS customer_count,
    ROUND(AVG(lifetime_value), 2) AS avg_lifetime_value,
    ROUND(MIN(lifetime_value), 2) AS min_value,
    ROUND(MAX(lifetime_value), 2) AS max_value,
    ROUND(AVG(total_orders), 1) AS avg_orders,
    CASE 
        WHEN value_decile = 1 THEN 'VIP - Top 10%'
        WHEN value_decile <= 3 THEN 'High Value'
        WHEN value_decile <= 7 THEN 'Medium Value'
        ELSE 'Low Value'
    END AS segment_label,
    CASE 
        WHEN value_decile = 1 THEN 'Personal account manager, exclusive offers'
        WHEN value_decile <= 3 THEN 'Premium rewards, early access'
        WHEN value_decile <= 7 THEN 'Standard rewards program'
        ELSE 'Re-engagement campaigns'
    END AS recommended_action
FROM customer_analysis
GROUP BY value_decile
ORDER BY value_decile;
```

---

### 5️⃣ LAG() - Access Previous Row

Current row-এর আগের row-এর value access করতে।

**Easy Example 1: Previous month sales**
```sql
SELECT 
    month,
    revenue,
    LAG(revenue) OVER (ORDER BY month) AS previous_month_revenue
FROM monthly_sales;
```

**Easy Example 2: Price change**
```sql
SELECT 
    product_id,
    price_date,
    price,
    LAG(price) OVER (PARTITION BY product_id ORDER BY price_date) AS previous_price,
    price - LAG(price) OVER (PARTITION BY product_id ORDER BY price_date) AS price_change
FROM product_prices;
```

**Complex Example: Calculate growth trends**
```sql
-- Advanced sales analysis with multiple lags
WITH sales_data AS (
    SELECT 
        DATE_FORMAT(order_date, '%Y-%m') AS month,
        SUM(order_total) AS monthly_revenue,
        COUNT(DISTINCT customer_id) AS customer_count,
        COUNT(order_id) AS order_count
    FROM orders
    GROUP BY DATE_FORMAT(order_date, '%Y-%m')
)
SELECT 
    month,
    monthly_revenue,
    customer_count,
    order_count,
    LAG(monthly_revenue, 1) OVER (ORDER BY month) AS prev_month_revenue,
    LAG(monthly_revenue, 12) OVER (ORDER BY month) AS same_month_last_year,
    ROUND(
        ((monthly_revenue - LAG(monthly_revenue, 1) OVER (ORDER BY month)) / 
        LAG(monthly_revenue, 1) OVER (ORDER BY month)) * 100, 
        2
    ) AS mom_growth_percent,
    ROUND(
        ((monthly_revenue - LAG(monthly_revenue, 12) OVER (ORDER BY month)) / 
        LAG(monthly_revenue, 12) OVER (ORDER BY month)) * 100, 
        2
    ) AS yoy_growth_percent,
    AVG(monthly_revenue) OVER (
        ORDER BY month 
        ROWS BETWEEN 2 PRECEDING AND CURRENT ROW
    ) AS three_month_avg,
    CASE 
        WHEN monthly_revenue > LAG(monthly_revenue, 1) OVER (ORDER BY month) THEN 'Growing'
        WHEN monthly_revenue = LAG(monthly_revenue, 1) OVER (ORDER BY month) THEN 'Stable'
        ELSE 'Declining'
    END AS trend
FROM sales_data
ORDER BY month;
```

---

### 6️⃣ LEAD() - Access Next Row

Current row-এর পরের row-এর value access করতে।

**Easy Example 1: Next day temperature**
```sql
SELECT 
    date,
    temperature,
    LEAD(temperature) OVER (ORDER BY date) AS next_day_temp,
    LEAD(temperature) OVER (ORDER BY date) - temperature AS temp_change
FROM weather_data;
```

**Easy Example 2: Project timeline**
```sql
SELECT 
    task_name,
    start_date,
    end_date,
    LEAD(start_date) OVER (ORDER BY start_date) AS next_task_start,
    DATEDIFF(
        LEAD(start_date) OVER (ORDER BY start_date), 
        end_date
    ) AS gap_days
FROM project_tasks;
```

**Complex Example: Customer journey analysis**
```sql
-- Analyze customer purchase patterns
WITH customer_purchases AS (
    SELECT 
        customer_id,
        order_id,
        order_date,
        order_total,
        product_category
    FROM orders
    WHERE order_date >= DATE_SUB(CURDATE(), INTERVAL 1 YEAR)
),
purchase_flow AS (
    SELECT 
        customer_id,
        order_date,
        order_total,
        product_category,
        LEAD(order_date) OVER (PARTITION BY customer_id ORDER BY order_date) AS next_purchase_date,
        LEAD(product_category) OVER (PARTITION BY customer_id ORDER BY order_date) AS next_category,
        LEAD(order_total) OVER (PARTITION BY customer_id ORDER BY order_date) AS next_order_total,
        ROW_NUMBER() OVER (PARTITION BY customer_id ORDER BY order_date) AS purchase_number
    FROM customer_purchases
)
SELECT 
    customer_id,
    product_category AS current_category,
    next_category,
    CONCAT(product_category, ' → ', COALESCE(next_category, 'No Next')) AS purchase_pattern,
    COUNT(*) AS pattern_count,
    ROUND(AVG(DATEDIFF(next_purchase_date, order_date)), 1) AS avg_days_between_purchases,
    ROUND(AVG(order_total), 2) AS avg_current_order,
    ROUND(AVG(next_order_total), 2) AS avg_next_order,
    ROUND(AVG(next_order_total - order_total), 2) AS avg_order_growth
FROM purchase_flow
WHERE next_purchase_date IS NOT NULL
GROUP BY customer_id, product_category, next_category
HAVING pattern_count >= 2
ORDER BY customer_id, pattern_count DESC;
```

---

### 7️⃣ FIRST_VALUE() - First Value in Window

Window-এর প্রথম value return করে।

**Easy Example 1: Highest salary in department**
```sql
SELECT DISTINCT
    department,
    FIRST_VALUE(name) OVER (
        PARTITION BY department 
        ORDER BY salary DESC
    ) AS highest_paid_employee,
    FIRST_VALUE(salary) OVER (
        PARTITION BY department 
        ORDER BY salary DESC
    ) AS highest_salary
FROM employees;
```

**Easy Example 2: First order of each customer**
```sql
SELECT 
    customer_id,
    order_date,
    order_total,
    FIRST_VALUE(order_date) OVER (
        PARTITION BY customer_id 
        ORDER BY order_date
    ) AS first_order_date
FROM orders;
```

**Complex Example: Benchmark comparison**
```sql
-- Compare each product against category leader
WITH product_metrics AS (
    SELECT 
        p.product_id,
        p.product_name,
        p.category,
        p.price AS current_price,
        COUNT(o.order_id) AS total_orders,
        SUM(o.quantity) AS total_quantity,
        SUM(o.quantity * o.price) AS total_revenue,
        AVG(r.rating) AS avg_rating
    FROM products p
    LEFT JOIN orders o ON p.product_id = o.product_id
    LEFT JOIN reviews r ON p.product_id = r.product_id
    GROUP BY p.product_id, p.product_name, p.category, p.price
)
SELECT 
    category,
    product_name,
    current_price,
    total_orders,
    total_revenue,
    ROUND(avg_rating, 2) AS rating,
    FIRST_VALUE(product_name) OVER (
        PARTITION BY category 
        ORDER BY total_revenue DESC
    ) AS category_leader,
    FIRST_VALUE(total_revenue) OVER (
        PARTITION BY category 
        ORDER BY total_revenue DESC
    ) AS leader_revenue,
    ROUND(
        (total_revenue / FIRST_VALUE(total_revenue) OVER (
            PARTITION BY category 
            ORDER BY total_revenue DESC
        )) * 100, 
        2
    ) AS percent_of_leader,
    CASE 
        WHEN product_name = FIRST_VALUE(product_name) OVER (
            PARTITION BY category ORDER BY total_revenue DESC
        ) THEN 'Category Leader'
        WHEN total_revenue >= FIRST_VALUE(total_revenue) OVER (
            PARTITION BY category ORDER BY total_revenue DESC
        ) * 0.7 THEN 'Strong Competitor'
        WHEN total_revenue >= FIRST_VALUE(total_revenue) OVER (
            PARTITION BY category ORDER BY total_revenue DESC
        ) * 0.3 THEN 'Average Performer'
        ELSE 'Needs Improvement'
    END AS performance_tier
FROM product_metrics
ORDER BY category, total_revenue DESC;
```

---

### 8️⃣ LAST_VALUE() - Last Value in Window

Window-এর শেষ value return করে।

**Easy Example 1: Latest salary in department**
```sql
SELECT DISTINCT
    department,
    LAST_VALUE(name) OVER (
        PARTITION BY department 
        ORDER BY join_date
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS latest_hire
FROM employees;
```

**Easy Example 2: Latest status**
```sql
SELECT 
    order_id,
    status_date,
    status,
    LAST_VALUE(status) OVER (
        PARTITION BY order_id 
        ORDER BY status_date
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS current_status
FROM order_status_history;
```

**Complex Example: Trend analysis with first and last**
```sql
-- Compare first day vs last day performance of each month
WITH daily_metrics AS (
    SELECT 
        DATE_FORMAT(order_date, '%Y-%m') AS month,
        DATE(order_date) AS day,
        SUM(order_total) AS daily_revenue,
        COUNT(order_id) AS daily_orders,
        COUNT(DISTINCT customer_id) AS daily_customers
    FROM orders
    GROUP BY DATE_FORMAT(order_date, '%Y-%m'), DATE(order_date)
)
SELECT DISTINCT
    month,
    FIRST_VALUE(day) OVER (
        PARTITION BY month ORDER BY day
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS first_day,
    FIRST_VALUE(daily_revenue) OVER (
        PARTITION BY month ORDER BY day
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS first_day_revenue,
    LAST_VALUE(day) OVER (
        PARTITION BY month ORDER BY day
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS last_day,
    LAST_VALUE(daily_revenue) OVER (
        PARTITION BY month ORDER BY day
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS last_day_revenue,
    ROUND(AVG(daily_revenue) OVER (PARTITION BY month), 2) AS month_avg_daily_revenue,
    SUM(daily_revenue) OVER (PARTITION BY month) AS month_total_revenue,
    COUNT(day) OVER (PARTITION BY month) AS trading_days,
    ROUND(
        ((LAST_VALUE(daily_revenue) OVER (
            PARTITION BY month ORDER BY day
            ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
        ) - FIRST_VALUE(daily_revenue) OVER (
            PARTITION BY month ORDER BY day
            ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
        )) / FIRST_VALUE(daily_revenue) OVER (
            PARTITION BY month ORDER BY day
            ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
        )) * 100,
        2
    ) AS first_to_last_growth_percent
FROM daily_metrics
ORDER BY month;
```

---

### 9️⃣ NTH_VALUE() - Nth Value in Window

Window-এর n-তম value return করে।

**Easy Example 1: Second highest salary**
```sql
SELECT DISTINCT
    department,
    NTH_VALUE(name, 2) OVER (
        PARTITION BY department 
        ORDER BY salary DESC
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS second_highest_earner,
    NTH_VALUE(salary, 2) OVER (
        PARTITION BY department 
        ORDER BY salary DESC
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS second_highest_salary
FROM employees;
```

**Easy Example 2: Third best-selling product**
```sql
SELECT DISTINCT
    category,
    NTH_VALUE(product_name, 3) OVER (
        PARTITION BY category 
        ORDER BY sales_count DESC
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS third_best_seller
FROM product_sales;
```

**Complex Example: Percentile analysis**
```sql
-- Get specific percentile values (25th, 50th, 75th)
WITH ranked_salaries AS (
    SELECT 
        department,
        name,
        salary,
        ROW_NUMBER() OVER (PARTITION BY department ORDER BY salary) AS rn,
        COUNT(*) OVER (PARTITION BY department) AS dept_count
    FROM employees
)
SELECT DISTINCT
    department,
    dept_count AS employee_count,
    NTH_VALUE(salary, CAST(dept_count * 0.25 AS UNSIGNED)) OVER (
        PARTITION BY department 
        ORDER BY salary
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS percentile_25,
    NTH_VALUE(salary, CAST(dept_count * 0.50 AS UNSIGNED)) OVER (
        PARTITION BY department 
        ORDER BY salary
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS median_salary,
    NTH_VALUE(salary, CAST(dept_count * 0.75 AS UNSIGNED)) OVER (
        PARTITION BY department 
        ORDER BY salary
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS percentile_75,
    NTH_VALUE(salary, 1) OVER (
        PARTITION BY department 
        ORDER BY salary DESC
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS max_salary,
    NTH_VALUE(salary, 1) OVER (
        PARTITION BY department 
        ORDER BY salary
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS min_salary
FROM ranked_salaries
ORDER BY department;
```

---

### 🔟 SUM/AVG/COUNT with OVER - Running Totals

Aggregate functions-কে window functions হিসেবে ব্যবহার করা।

**Easy Example 1: Running total**
```sql
SELECT 
    order_date,
    order_total,
    SUM(order_total) OVER (ORDER BY order_date) AS running_total
FROM orders;
```

**Easy Example 2: Moving average**
```sql
SELECT 
    date,
    temperature,
    AVG(temperature) OVER (
        ORDER BY date 
        ROWS BETWEEN 6 PRECEDING AND CURRENT ROW
    ) AS seven_day_avg
FROM weather;
```

**Complex Example: Financial dashboard**
```sql
-- Comprehensive financial analysis with multiple window calculations
WITH daily_transactions AS (
    SELECT 
        DATE(transaction_date) AS trans_date,
        transaction_type,
        SUM(CASE WHEN transaction_type = 'Income' THEN amount ELSE 0 END) AS daily_income,
        SUM(CASE WHEN transaction_type = 'Expense' THEN amount ELSE 0 END) AS daily_expense,
        SUM(CASE WHEN transaction_type = 'Income' THEN amount ELSE -amount END) AS daily_net
    FROM transactions
    GROUP BY DATE(transaction_date), transaction_type
)
SELECT 
    trans_date,
    daily_income,
    daily_expense,
    daily_net,
    -- Running totals
    SUM(daily_income) OVER (ORDER BY trans_date) AS cumulative_income,
    SUM(daily_expense) OVER (ORDER BY trans_date) AS cumulative_expense,
    SUM(daily_net) OVER (ORDER BY trans_date) AS account_balance,
    -- Moving averages (7-day)
    ROUND(AVG(daily_income) OVER (
        ORDER BY trans_date 
        ROWS BETWEEN 6 PRECEDING AND CURRENT ROW
    ), 2) AS income_7day_avg,
    ROUND(AVG(daily_expense) OVER (
        ORDER BY trans_date 
        ROWS BETWEEN 6 PRECEDING AND CURRENT ROW
    ), 2) AS expense_7day_avg,
    -- Moving averages (30-day)
    ROUND(AVG(daily_net) OVER (
        ORDER BY trans_date 
        ROWS BETWEEN 29 PRECEDING AND CURRENT ROW
    ), 2) AS net_30day_avg,
    -- Count of transactions
    COUNT(*) OVER (
        ORDER BY trans_date 
        ROWS BETWEEN 6 PRECEDING AND CURRENT ROW
    ) AS transactions_last_7days,
    -- Percentage of total
    ROUND(
        (daily_income / SUM(daily_income) OVER ()) * 100,
        2
    ) AS pct_of_total_income,
    -- Comparison with average
    ROUND(
        ((daily_net - AVG(daily_net) OVER ()) / AVG(daily_net) OVER ()) * 100,
        2
    ) AS variance_from_avg_pct
FROM daily_transactions
ORDER BY trans_date;
```

---

### 🎯 Window Function Frame Clauses

Window frame নির্ধারণ করে কোন rows-এ calculation করা হবে।

```sql
-- ROWS: Physical rows
ROWS BETWEEN 1 PRECEDING AND 1 FOLLOWING
ROWS BETWEEN UNBOUNDED PRECEDING AND CURRENT ROW
ROWS BETWEEN CURRENT ROW AND UNBOUNDED FOLLOWING
ROWS BETWEEN 3 PRECEDING AND 3 FOLLOWING

-- RANGE: Logical range based on values
RANGE BETWEEN INTERVAL 1 DAY PRECEDING AND INTERVAL 1 DAY FOLLOWING
```

**Example: Different frame types**
```sql
SELECT 
    order_date,
    order_total,
    -- Default: RANGE BETWEEN UNBOUNDED PRECEDING AND CURRENT ROW
    SUM(order_total) OVER (ORDER BY order_date) AS cumulative_sum,
    -- Last 3 days including today
    SUM(order_total) OVER (
        ORDER BY order_date 
        ROWS BETWEEN 2 PRECEDING AND CURRENT ROW
    ) AS last_3_days_sum,
    -- Last 3 rows + current + next 3 rows (7 total)
    AVG(order_total) OVER (
        ORDER BY order_date 
        ROWS BETWEEN 3 PRECEDING AND 3 FOLLOWING
    ) AS centered_7day_avg,
    -- All rows in partition
    AVG(order_total) OVER (
        ORDER BY order_date 
        ROWS BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING
    ) AS overall_avg
FROM orders;
```

---

### 🎯 Real-World Window Function Examples

**Example 1: E-commerce Product Performance**
```sql
WITH product_performance AS (
    SELECT 
        p.product_id,
        p.product_name,
        p.category,
        COUNT(o.order_id) AS order_count,
        SUM(o.quantity) AS total_sold,
        SUM(o.quantity * o.price) AS revenue,
        AVG(r.rating) AS avg_rating
    FROM products p
    LEFT JOIN order_items o ON p.product_id = o.product_id
    LEFT JOIN reviews r ON p.product_id = r.product_id
    GROUP BY p.product_id, p.product_name, p.category
)
SELECT 
    product_name,
    category,
    revenue,
    ROW_NUMBER() OVER (PARTITION BY category ORDER BY revenue DESC) AS category_rank,
    RANK() OVER (ORDER BY revenue DESC) AS overall_rank,
    NTILE(4) OVER (ORDER BY revenue DESC) AS revenue_quartile,
    ROUND(revenue / SUM(revenue) OVER (PARTITION BY category) * 100, 2) AS pct_category_revenue,
    ROUND(revenue / SUM(revenue) OVER () * 100, 2) AS pct_total_revenue,
    ROUND(avg_rating, 2) AS rating,
    CASE 
        WHEN ROW_NUMBER() OVER (PARTITION BY category ORDER BY revenue DESC) = 1 
        THEN 'Category Leader'
        WHEN NTILE(4) OVER (ORDER BY revenue DESC) = 1 
        THEN 'Top Performer'
        ELSE 'Regular'
    END AS performance_label
FROM product_performance
ORDER BY revenue DESC;
```

---

## 🔄 Pivot and Unpivot Operations

**Pivot** operations rows-কে columns-এ transform করে, আর **Unpivot** columns-কে rows-এ transform করে। MySQL-এ built-in PIVOT syntax নেই, তাই CASE statements এবং aggregations ব্যবহার করতে হয়।

### 📖 Pivot Operations

**Pivot** করলে row data column headers হয়ে যায়।

**Easy Example 1: Monthly sales pivot**
```sql
SELECT 
    product_name,
    SUM(CASE WHEN MONTH(order_date) = 1 THEN quantity ELSE 0 END) AS Jan,
    SUM(CASE WHEN MONTH(order_date) = 2 THEN quantity ELSE 0 END) AS Feb,
    SUM(CASE WHEN MONTH(order_date) = 3 THEN quantity ELSE 0 END) AS Mar,
    SUM(CASE WHEN MONTH(order_date) = 4 THEN quantity ELSE 0 END) AS Apr
FROM orders
WHERE YEAR(order_date) = 2024
GROUP BY product_name;
```

**Easy Example 2: Department headcount by location**
```sql
SELECT 
    department,
    SUM(CASE WHEN location = 'Dhaka' THEN 1 ELSE 0 END) AS Dhaka,
    SUM(CASE WHEN location = 'Chittagong' THEN 1 ELSE 0 END) AS Chittagong,
    SUM(CASE WHEN location = 'Sylhet' THEN 1 ELSE 0 END) AS Sylhet,
    COUNT(*) AS Total
FROM employees
GROUP BY department;
```

**Complex Example: Multi-dimensional pivot**
```sql
-- Comprehensive sales analysis: Products × Quarters × Metrics
WITH quarterly_sales AS (
    SELECT 
        p.category,
        p.product_name,
        CONCAT('Q', QUARTER(o.order_date)) AS quarter,
        YEAR(o.order_date) AS year,
        SUM(oi.quantity) AS units_sold,
        SUM(oi.quantity * oi.price) AS revenue,
        COUNT(DISTINCT o.customer_id) AS unique_customers
    FROM products p
    JOIN order_items oi ON p.product_id = oi.product_id
    JOIN orders o ON oi.order_id = o.order_id
    WHERE o.order_date >= DATE_SUB(CURDATE(), INTERVAL 1 YEAR)
    GROUP BY p.category, p.product_name, QUARTER(o.order_date), YEAR(o.order_date)
)
SELECT 
    category,
    product_name,
    -- Q1 Metrics
    SUM(CASE WHEN quarter = 'Q1' THEN revenue ELSE 0 END) AS Q1_Revenue,
    SUM(CASE WHEN quarter = 'Q1' THEN units_sold ELSE 0 END) AS Q1_Units,
    SUM(CASE WHEN quarter = 'Q1' THEN unique_customers ELSE 0 END) AS Q1_Customers,
    -- Q2 Metrics
    SUM(CASE WHEN quarter = 'Q2' THEN revenue ELSE 0 END) AS Q2_Revenue,
    SUM(CASE WHEN quarter = 'Q2' THEN units_sold ELSE 0 END) AS Q2_Units,
    SUM(CASE WHEN quarter = 'Q2' THEN unique_customers ELSE 0 END) AS Q2_Customers,
    -- Q3 Metrics
    SUM(CASE WHEN quarter = 'Q3' THEN revenue ELSE 0 END) AS Q3_Revenue,
    SUM(CASE WHEN quarter = 'Q3' THEN units_sold ELSE 0 END) AS Q3_Units,
    SUM(CASE WHEN quarter = 'Q3' THEN unique_customers ELSE 0 END) AS Q3_Customers,
    -- Q4 Metrics
    SUM(CASE WHEN quarter = 'Q4' THEN revenue ELSE 0 END) AS Q4_Revenue,
    SUM(CASE WHEN quarter = 'Q4' THEN units_sold ELSE 0 END) AS Q4_Units,
    SUM(CASE WHEN quarter = 'Q4' THEN unique_customers ELSE 0 END) AS Q4_Customers,
    -- Totals and Analytics
    SUM(revenue) AS Total_Revenue,
    SUM(units_sold) AS Total_Units,
    ROUND(AVG(revenue), 2) AS Avg_Quarterly_Revenue,
    -- Growth calculations
    ROUND(
        ((SUM(CASE WHEN quarter = 'Q4' THEN revenue ELSE 0 END) - 
          SUM(CASE WHEN quarter = 'Q1' THEN revenue ELSE 0 END)) /
         NULLIF(SUM(CASE WHEN quarter = 'Q1' THEN revenue ELSE 0 END), 0)) * 100,
        2
    ) AS YoY_Growth_Pct,
    -- Identify best quarter
    CASE 
        WHEN SUM(CASE WHEN quarter = 'Q1' THEN revenue ELSE 0 END) >= 
             GREATEST(
                 SUM(CASE WHEN quarter = 'Q2' THEN revenue ELSE 0 END),
                 SUM(CASE WHEN quarter = 'Q3' THEN revenue ELSE 0 END),
                 SUM(CASE WHEN quarter = 'Q4' THEN revenue ELSE 0 END)
             ) THEN 'Q1'
        WHEN SUM(CASE WHEN quarter = 'Q2' THEN revenue ELSE 0 END) >= 
             GREATEST(
                 SUM(CASE WHEN quarter = 'Q1' THEN revenue ELSE 0 END),
                 SUM(CASE WHEN quarter = 'Q3' THEN revenue ELSE 0 END),
                 SUM(CASE WHEN quarter = 'Q4' THEN revenue ELSE 0 END)
             ) THEN 'Q2'
        WHEN SUM(CASE WHEN quarter = 'Q3' THEN revenue ELSE 0 END) >= 
             GREATEST(
                 SUM(CASE WHEN quarter = 'Q1' THEN revenue ELSE 0 END),
                 SUM(CASE WHEN quarter = 'Q2' THEN revenue ELSE 0 END),
                 SUM(CASE WHEN quarter = 'Q4' THEN revenue ELSE 0 END)
             ) THEN 'Q3'
        ELSE 'Q4'
    END AS Best_Quarter
FROM quarterly_sales
GROUP BY category, product_name
HAVING Total_Revenue > 0
ORDER BY category, Total_Revenue DESC;
```

---

### 📖 Unpivot Operations

**Unpivot** করলে column headers row data হয়ে যায়।

**Easy Example 1: Quarterly scores to rows**
```sql
-- Original table: student_id, Q1, Q2, Q3, Q4
-- Target: student_id, quarter, score
SELECT student_id, 'Q1' AS quarter, Q1 AS score FROM student_scores WHERE Q1 IS NOT NULL
UNION ALL
SELECT student_id, 'Q2' AS quarter, Q2 AS score FROM student_scores WHERE Q2 IS NOT NULL
UNION ALL
SELECT student_id, 'Q3' AS quarter, Q3 AS score FROM student_scores WHERE Q3 IS NOT NULL
UNION ALL
SELECT student_id, 'Q4' AS quarter, Q4 AS score FROM student_scores WHERE Q4 IS NOT NULL
ORDER BY student_id, quarter;
```

**Easy Example 2: Monthly sales columns to rows**
```sql
-- Transform: product_id, jan_sales, feb_sales, mar_sales
-- To: product_id, month, sales
SELECT product_id, 'January' AS month, jan_sales AS sales FROM monthly_sales
UNION ALL
SELECT product_id, 'February' AS month, feb_sales AS sales FROM monthly_sales
UNION ALL
SELECT product_id, 'March' AS month, mar_sales AS sales FROM monthly_sales
ORDER BY product_id, 
    CASE month
        WHEN 'January' THEN 1
        WHEN 'February' THEN 2
        WHEN 'March' THEN 3
    END;
```

**Complex Example: Multi-metric unpivot**
```sql
-- Complex unpivoting with multiple metrics
-- Source: Wide format with multiple measure columns
-- Target: Long format (entity, metric_name, metric_value, period)

WITH sales_data AS (
    SELECT 
        'Product A' AS product,
        1000 AS Q1_Revenue, 50 AS Q1_Units, 20 AS Q1_Orders,
        1200 AS Q2_Revenue, 60 AS Q2_Units, 25 AS Q2_Orders,
        1500 AS Q3_Revenue, 75 AS Q3_Units, 30 AS Q3_Orders,
        1800 AS Q4_Revenue, 90 AS Q4_Units, 35 AS Q4_Orders
),
unpivoted AS (
    -- Q1 metrics
    SELECT product, 'Q1' AS quarter, 'Revenue' AS metric, Q1_Revenue AS value FROM sales_data
    UNION ALL
    SELECT product, 'Q1' AS quarter, 'Units' AS metric, Q1_Units AS value FROM sales_data
    UNION ALL
    SELECT product, 'Q1' AS quarter, 'Orders' AS metric, Q1_Orders AS value FROM sales_data
    UNION ALL
    -- Q2 metrics
    SELECT product, 'Q2' AS quarter, 'Revenue' AS metric, Q2_Revenue AS value FROM sales_data
    UNION ALL
    SELECT product, 'Q2' AS quarter, 'Units' AS metric, Q2_Units AS value FROM sales_data
    UNION ALL
    SELECT product, 'Q2' AS quarter, 'Orders' AS metric, Q2_Orders AS value FROM sales_data
    UNION ALL
    -- Q3 metrics
    SELECT product, 'Q3' AS quarter, 'Revenue' AS metric, Q3_Revenue AS value FROM sales_data
    UNION ALL
    SELECT product, 'Q3' AS quarter, 'Units' AS metric, Q3_Units AS value FROM sales_data
    UNION ALL
    SELECT product, 'Q3' AS quarter, 'Orders' AS metric, Q3_Orders AS value FROM sales_data
    UNION ALL
    -- Q4 metrics
    SELECT product, 'Q4' AS quarter, 'Revenue' AS metric, Q4_Revenue AS value FROM sales_data
    UNION ALL
    SELECT product, 'Q4' AS quarter, 'Units' AS metric, Q4_Units AS value FROM sales_data
    UNION ALL
    SELECT product, 'Q4' AS quarter, 'Orders' AS metric, Q4_Orders AS value FROM sales_data
)
SELECT 
    product,
    quarter,
    metric,
    value,
    -- Add period ordering
    CASE quarter
        WHEN 'Q1' THEN 1
        WHEN 'Q2' THEN 2
        WHEN 'Q3' THEN 3
        WHEN 'Q4' THEN 4
    END AS quarter_num,
    -- Calculate quarter-over-quarter growth
    ROUND(
        ((value - LAG(value) OVER (PARTITION BY product, metric ORDER BY quarter)) /
         NULLIF(LAG(value) OVER (PARTITION BY product, metric ORDER BY quarter), 0)) * 100,
        2
    ) AS qoq_growth_pct,
    -- Running total per metric
    SUM(value) OVER (PARTITION BY product, metric ORDER BY quarter) AS running_total,
    -- Average per metric
    ROUND(AVG(value) OVER (PARTITION BY product, metric), 2) AS metric_avg
FROM unpivoted
ORDER BY product, metric, quarter;
```

---

## 🔧 Dynamic SQL

**Dynamic SQL** allows you to build and execute SQL statements at runtime. এটি flexible queries তৈরি করতে, table/column names dynamically নির্ধারণ করতে এবং conditional logic implement করতে ব্যবহৃত হয়।

### 📖 PREPARE, EXECUTE, DEALLOCATE

**Easy Example 1: Simple dynamic query**
```sql
-- Prepare a statement
SET @table_name = 'employees';
SET @query = CONCAT('SELECT COUNT(*) FROM ', @table_name);
PREPARE stmt FROM @query;
EXECUTE stmt;
DEALLOCATE PREPARE stmt;
```

**Easy Example 2: Dynamic WHERE clause**
```sql
SET @min_salary = 50000;
SET @department = 'IT';
SET @sql = CONCAT(
    'SELECT name, salary, department FROM employees WHERE salary > ',
    @min_salary,
    ' AND department = ''',
    @department,
    ''''
);
PREPARE stmt FROM @sql;
EXECUTE stmt;
DEALLOCATE PREPARE stmt;
```

**Complex Example: Dynamic report generator**
```sql
DELIMITER //

CREATE PROCEDURE generate_dynamic_report(
    IN p_table_name VARCHAR(64),
    IN p_group_column VARCHAR(64),
    IN p_aggregate_column VARCHAR(64),
    IN p_filter_column VARCHAR(64),
    IN p_filter_value VARCHAR(255)
)
BEGIN
    SET @sql = CONCAT(
        'SELECT ',
        p_group_column, ' AS Category, ',
        'COUNT(*) AS Record_Count, ',
        'SUM(', p_aggregate_column, ') AS Total, ',
        'AVG(', p_aggregate_column, ') AS Average, ',
        'MIN(', p_aggregate_column, ') AS Minimum, ',
        'MAX(', p_aggregate_column, ') AS Maximum ',
        'FROM ', p_table_name, ' '
    );
    
    -- Add WHERE clause if filter provided
    IF p_filter_column IS NOT NULL AND p_filter_value IS NOT NULL THEN
        SET @sql = CONCAT(@sql, 
            'WHERE ', p_filter_column, ' = ''', p_filter_value, ''' '
        );
    END IF;
    
    -- Add GROUP BY
    SET @sql = CONCAT(@sql, 
        'GROUP BY ', p_group_column, ' ',
        'ORDER BY Total DESC'
    );
    
    -- Execute
    PREPARE stmt FROM @sql;
    EXECUTE stmt;
    DEALLOCATE PREPARE stmt;
END //

DELIMITER ;

-- Usage
CALL generate_dynamic_report('orders', 'customer_id', 'order_total', 'status', 'Completed');
```

---

### 📖 Dynamic Table Operations

**Easy Example 1: Create table dynamically**
```sql
SET @table_name = 'temp_report_2025';
SET @sql = CONCAT(
    'CREATE TABLE IF NOT EXISTS ', @table_name, ' (',
    'id INT PRIMARY KEY AUTO_INCREMENT, ',
    'report_date DATE, ',
    'metric_value DECIMAL(10,2), ',
    'created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP',
    ')'
);
PREPARE stmt FROM @sql;
EXECUTE stmt;
DEALLOCATE PREPARE stmt;
```

**Easy Example 2: Dynamic INSERT**
```sql
SET @table_name = 'audit_log';
SET @user_name = 'john_doe';
SET @action = 'LOGIN';
SET @sql = CONCAT(
    'INSERT INTO ', @table_name, ' (username, action, timestamp) ',
    'VALUES (''', @user_name, ''', ''', @action, ''', NOW())'
);
PREPARE stmt FROM @sql;
EXECUTE stmt;
DEALLOCATE PREPARE stmt;
```

**Complex Example: Dynamic pivot query builder**
```sql
DELIMITER //

CREATE PROCEDURE create_pivot_report(
    IN p_source_table VARCHAR(64),
    IN p_row_field VARCHAR(64),
    IN p_column_field VARCHAR(64),
    IN p_value_field VARCHAR(64)
)
BEGIN
    DECLARE done INT DEFAULT FALSE;
    DECLARE col_name VARCHAR(255);
    DECLARE pivot_columns TEXT DEFAULT '';
    DECLARE cur CURSOR FOR 
        SELECT DISTINCT CONCAT('`', p_column_field, '`') AS col
        FROM (
            SELECT * FROM information_schema.tables WHERE 1=1
        ) t;
    DECLARE CONTINUE HANDLER FOR NOT FOUND SET done = TRUE;
    
    -- Build dynamic column list
    SET @get_columns = CONCAT(
        'SELECT DISTINCT ', p_column_field, ' INTO @cols ',
        'FROM ', p_source_table, ' ',
        'ORDER BY ', p_column_field
    );
    
    -- Build CASE statements for each column
    SET @sql = CONCAT(
        'SELECT ', p_row_field, ', '
    );
    
    -- This is simplified - in practice, you'd need to fetch distinct values first
    SET @sql = CONCAT(@sql,
        'SUM(CASE WHEN ', p_column_field, ' = ''Value1'' THEN ', p_value_field, ' ELSE 0 END) AS Value1, ',
        'SUM(CASE WHEN ', p_column_field, ' = ''Value2'' THEN ', p_value_field, ' ELSE 0 END) AS Value2 ',
        'FROM ', p_source_table, ' ',
        'GROUP BY ', p_row_field
    );
    
    PREPARE stmt FROM @sql;
    EXECUTE stmt;
    DEALLOCATE PREPARE stmt;
END //

DELIMITER ;
```

---

### 📖 Dynamic Stored Procedures

**Easy Example 1: Conditional column selection**
```sql
DELIMITER //

CREATE PROCEDURE get_employee_data(
    IN p_include_salary BOOLEAN,
    IN p_include_bonus BOOLEAN
)
BEGIN
    SET @sql = 'SELECT id, name, department';
    
    IF p_include_salary THEN
        SET @sql = CONCAT(@sql, ', salary');
    END IF;
    
    IF p_include_bonus THEN
        SET @sql = CONCAT(@sql, ', bonus');
    END IF;
    
    SET @sql = CONCAT(@sql, ' FROM employees');
    
    PREPARE stmt FROM @sql;
    EXECUTE stmt;
    DEALLOCATE PREPARE stmt;
END //

DELIMITER ;

CALL get_employee_data(TRUE, FALSE);  -- Include salary, exclude bonus
```

**Easy Example 2: Dynamic sorting**
```sql
DELIMITER //

CREATE PROCEDURE get_sorted_data(
    IN p_sort_column VARCHAR(64),
    IN p_sort_direction VARCHAR(4)
)
BEGIN
    SET @allowed_columns = 'name,salary,department,join_date';
    
    -- Validate sort column
    IF FIND_IN_SET(p_sort_column, @allowed_columns) = 0 THEN
        SIGNAL SQLSTATE '45000'
        SET MESSAGE_TEXT = 'Invalid sort column';
    END IF;
    
    -- Validate sort direction
    IF p_sort_direction NOT IN ('ASC', 'DESC') THEN
        SET p_sort_direction = 'ASC';
    END IF;
    
    SET @sql = CONCAT(
        'SELECT * FROM employees ORDER BY ',
        p_sort_column, ' ', p_sort_direction
    );
    
    PREPARE stmt FROM @sql;
    EXECUTE stmt;
    DEALLOCATE PREPARE stmt;
END //

DELIMITER ;

CALL get_sorted_data('salary', 'DESC');
```

**Complex Example: Advanced dynamic query builder**
```sql
DELIMITER //

CREATE PROCEDURE advanced_search(
    IN p_search_table VARCHAR(64),
    IN p_search_fields TEXT,        -- Comma-separated: 'field1,field2,field3'
    IN p_filter_conditions TEXT,     -- JSON format or special syntax
    IN p_sort_by VARCHAR(64),
    IN p_sort_order VARCHAR(4),
    IN p_limit INT
)
BEGIN
    DECLARE v_sql TEXT;
    DECLARE v_where_clause TEXT DEFAULT '';
    
    -- Build SELECT clause
    IF p_search_fields IS NULL OR p_search_fields = '' THEN
        SET v_sql = CONCAT('SELECT * FROM ', p_search_table);
    ELSE
        SET v_sql = CONCAT('SELECT ', p_search_fields, ' FROM ', p_search_table);
    END IF;
    
    -- Build WHERE clause (simplified - in production, parse JSON properly)
    IF p_filter_conditions IS NOT NULL AND p_filter_conditions != '' THEN
        SET v_where_clause = CONCAT(' WHERE ', p_filter_conditions);
        SET v_sql = CONCAT(v_sql, v_where_clause);
    END IF;
    
    -- Add ORDER BY
    IF p_sort_by IS NOT NULL THEN
        SET v_sql = CONCAT(v_sql, ' ORDER BY ', p_sort_by);
        
        IF p_sort_order IN ('ASC', 'DESC') THEN
            SET v_sql = CONCAT(v_sql, ' ', p_sort_order);
        END IF;
    END IF;
    
    -- Add LIMIT
    IF p_limit IS NOT NULL AND p_limit > 0 THEN
        SET v_sql = CONCAT(v_sql, ' LIMIT ', p_limit);
    END IF;
    
    -- Log the query (for debugging)
    SELECT v_sql AS generated_query;
    
    -- Execute
    SET @final_sql = v_sql;
    PREPARE stmt FROM @final_sql;
    EXECUTE stmt;
    DEALLOCATE PREPARE stmt;
END //

DELIMITER ;

-- Usage examples
CALL advanced_search('employees', 'id,name,salary,department', 'salary > 50000 AND department = ''IT''', 'salary', 'DESC', 10);
CALL advanced_search('orders', 'order_id,customer_id,order_total', 'order_date >= ''2024-01-01''', 'order_date', 'DESC', 50);
```

---

### ⚠️ Dynamic SQL Security Considerations

**SQL Injection Prevention:**

```sql
-- ❌ BAD: Vulnerable to SQL injection
SET @user_input = "'; DROP TABLE users; --";
SET @sql = CONCAT('SELECT * FROM users WHERE name = ''', @user_input, '''');

-- ✅ GOOD: Use prepared statements with parameters
PREPARE stmt FROM 'SELECT * FROM users WHERE name = ?';
SET @safe_input = @user_input;
EXECUTE stmt USING @safe_input;
DEALLOCATE PREPARE stmt;

-- ✅ GOOD: Validate and sanitize inputs
DELIMITER //

CREATE PROCEDURE safe_dynamic_query(IN p_table_name VARCHAR(64))
BEGIN
    DECLARE v_allowed_tables TEXT DEFAULT 'employees,orders,products,customers';
    
    -- Whitelist validation
    IF FIND_IN_SET(p_table_name, v_allowed_tables) = 0 THEN
        SIGNAL SQLSTATE '45000'
        SET MESSAGE_TEXT = 'Table not allowed';
    END IF;
    
    -- Now safe to use
    SET @sql = CONCAT('SELECT COUNT(*) FROM ', p_table_name);
    PREPARE stmt FROM @sql;
    EXECUTE stmt;
    DEALLOCATE PREPARE stmt;
END //

DELIMITER ;
```

---

## 🎓 Interview Questions {#interview-questions}

### 📊 SQL Interview Questions - Basic Level

#### 1️⃣ What is SQL?
**SQL (Structured Query Language)** is a standard language for managing and manipulating relational databases. It's used for querying, updating, and managing data.

#### 2️⃣ Differentiate between SQL and NoSQL databases

| Feature | SQL | NoSQL |
|---------|-----|-------|
| Structure | Relational, structured data | Non-relational, flexible schemas |
| Schema | Fixed schema | Dynamic schema |
| Examples | MySQL, PostgreSQL, Oracle | MongoDB, Cassandra, Redis |
| Best for | Complex queries, transactions | Large-scale data, flexibility |

#### 3️⃣ What are the different types of SQL commands?

- **DDL (Data Definition Language)** - CREATE, ALTER, DROP, TRUNCATE
- **DML (Data Manipulation Language)** - INSERT, UPDATE, DELETE
- **DQL (Data Query Language)** - SELECT
- **DCL (Data Control Language)** - GRANT, REVOKE
- **TCL (Transaction Control Language)** - COMMIT, ROLLBACK, SAVEPOINT

#### 4️⃣ What is a JOIN? Explain different types of JOINs

```sql
-- INNER JOIN - Returns matching rows from both tables
SELECT e.name, d.department_name
FROM employees e
INNER JOIN departments d ON e.department_id = d.id;

-- LEFT JOIN - All rows from left table + matching from right
SELECT e.name, d.department_name
FROM employees e
LEFT JOIN departments d ON e.department_id = d.id;

-- RIGHT JOIN - All rows from right table + matching from left
SELECT e.name, d.department_name
FROM employees e
RIGHT JOIN departments d ON e.department_id = d.id;

-- FULL OUTER JOIN - All rows from both tables
SELECT e.name, d.department_name
FROM employees e
LEFT JOIN departments d ON e.department_id = d.id
UNION
SELECT e.name, d.department_name
FROM employees e
RIGHT JOIN departments d ON e.department_id = d.id;

-- SELF JOIN - Table joined with itself
SELECT e1.name AS employee, e2.name AS manager
FROM employees e1
INNER JOIN employees e2 ON e1.manager_id = e2.id;

-- CROSS JOIN - Cartesian product of both tables
SELECT e.name, d.department_name
FROM employees e
CROSS JOIN departments d;
```

#### 5️⃣ Write a query to find the second highest salary

```sql
-- Method 1: Using MAX with subquery
SELECT MAX(salary) AS second_highest
FROM employees 
WHERE salary < (SELECT MAX(salary) FROM employees);

-- Method 2: Using LIMIT and OFFSET
SELECT DISTINCT salary
FROM employees
ORDER BY salary DESC
LIMIT 1 OFFSET 1;

-- Method 3: Using DENSE_RANK()
SELECT salary
FROM (
    SELECT salary, DENSE_RANK() OVER (ORDER BY salary DESC) AS rnk
    FROM employees
) ranked
WHERE rnk = 2;
```

#### 6️⃣ Explain the difference between WHERE and HAVING

```sql
-- WHERE: Filters rows before grouping
SELECT department, COUNT(*) AS emp_count
FROM employees
WHERE salary > 50000
GROUP BY department;

-- HAVING: Filters groups after grouping
SELECT department, AVG(salary) AS avg_salary
FROM employees
GROUP BY department
HAVING AVG(salary) > 60000;

-- Using both together
SELECT department, AVG(salary) AS avg_salary
FROM employees
WHERE age > 25
GROUP BY department
HAVING AVG(salary) > 55000;
```

#### 7️⃣ What is a primary key? What is a foreign key?

```sql
-- Primary Key Example
CREATE TABLE departments (
    id INT PRIMARY KEY AUTO_INCREMENT,
    department_name VARCHAR(50) NOT NULL
);

-- Foreign Key Example
CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    department_id INT,
    FOREIGN KEY (department_id) REFERENCES departments(id)
        ON DELETE CASCADE
        ON UPDATE CASCADE
);
```

**Primary Key:**
- Uniquely identifies each record
- Cannot contain NULL values
- Only one per table
- Automatically creates an index

**Foreign Key:**
- Links two tables together
- References primary key in another table
- Can contain NULL values
- Can have multiple foreign keys

#### 8️⃣ What are indexes? Explain clustered and non-clustered indexes

```sql
-- Creating an index
CREATE INDEX idx_salary ON employees(salary);

-- Unique index
CREATE UNIQUE INDEX idx_email ON employees(email);

-- Composite index
CREATE INDEX idx_dept_salary ON employees(department, salary);

-- Viewing indexes
SHOW INDEX FROM employees;

-- Dropping an index
DROP INDEX idx_salary ON employees;
```

**Clustered Index:**
- Physical order of data matches index order
- Only one per table
- Primary key creates clustered index by default

**Non-Clustered Index:**
- Separate structure from data
- Multiple non-clustered indexes per table
- Points to actual data location

#### 9️⃣ Write a query to fetch the top 5 records

```sql
-- Top 5 employees by salary
SELECT * FROM employees
ORDER BY salary DESC
LIMIT 5;

-- Top 5 products by revenue
SELECT product_id, SUM(amount) AS total_revenue
FROM sales
GROUP BY product_id
ORDER BY total_revenue DESC
LIMIT 5;

-- Top 5 customers by number of orders
SELECT customer_id, COUNT(*) AS order_count
FROM orders
GROUP BY customer_id
ORDER BY order_count DESC
LIMIT 5;
```

#### 🔟 What is a subquery? Give examples

```sql
-- Simple Subquery
SELECT name, salary
FROM employees
WHERE salary > (SELECT AVG(salary) FROM employees);

-- Subquery in FROM clause
SELECT dept, avg_sal
FROM (
    SELECT department AS dept, AVG(salary) AS avg_sal
    FROM employees
    GROUP BY department
) AS dept_avg
WHERE avg_sal > 60000;

-- Correlated Subquery
SELECT e1.name, e1.salary, e1.department
FROM employees e1
WHERE salary > (
    SELECT AVG(salary)
    FROM employees e2
    WHERE e2.department = e1.department
);

-- Subquery with IN
SELECT name
FROM employees
WHERE department_id IN (
    SELECT id FROM departments WHERE location = 'Dhaka'
);

-- Subquery with EXISTS
SELECT name
FROM employees e
WHERE EXISTS (
    SELECT 1 FROM departments d 
    WHERE d.id = e.department_id AND d.budget > 100000
);
```

---

### 📊 SQL Interview Questions - Intermediate Level

#### 1️⃣ Explain normalization and its types

**Normalization** reduces data redundancy and improves integrity by organizing fields and tables.

**First Normal Form (1NF):**
- Each column contains atomic values
- Each row is unique
- No repeating groups

```sql
-- Before 1NF
CREATE TABLE orders_bad (
    order_id INT,
    products VARCHAR(200)  -- 'Apple, Banana, Orange'
);

-- After 1NF
CREATE TABLE orders (
    order_id INT,
    product VARCHAR(50)
);
```

**Second Normal Form (2NF):**
- Must be in 1NF
- No partial dependencies
- All non-key attributes depend on entire primary key

**Third Normal Form (3NF):**
- Must be in 2NF
- No transitive dependencies
- Non-key attributes depend only on primary key

#### 2️⃣ What is denormalization? When is it used?

**Denormalization** intentionally introduces redundancy to improve read performance.

```sql
-- Normalized (3NF)
CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    department_id INT
);

CREATE TABLE departments (
    id INT PRIMARY KEY,
    department_name VARCHAR(50)
);

-- Denormalized (for performance)
CREATE TABLE employees_denorm (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    department_id INT,
    department_name VARCHAR(50)  -- Redundant but faster
);
```

**When to use:**
- Read-heavy applications
- Reporting and analytics
- When JOIN performance is poor
- Data warehousing scenarios

#### 3️⃣ Describe transactions and their properties (ACID)

```sql
-- Transaction Example
START TRANSACTION;

UPDATE accounts SET balance = balance - 1000 WHERE account_id = 1;
UPDATE accounts SET balance = balance + 1000 WHERE account_id = 2;

-- If all successful
COMMIT;

-- If any error occurs
ROLLBACK;
```

**ACID Properties:**

- **Atomicity** - All operations succeed or all fail
- **Consistency** - Database remains in valid state
- **Isolation** - Concurrent transactions don't interfere
- **Durability** - Committed data is permanently saved

#### 4️⃣ How do you handle NULL values in SQL?

```sql
-- Check for NULL
SELECT * FROM employees WHERE department IS NULL;

-- Replace NULL with default value
SELECT name, COALESCE(department, 'Not Assigned') AS dept
FROM employees;

-- Count non-NULL values
SELECT COUNT(department) FROM employees;

-- Update NULL values
UPDATE employees
SET department = 'General'
WHERE department IS NULL;

-- Use IFNULL (MySQL)
SELECT name, IFNULL(salary, 0) AS salary
FROM employees;

-- Use CASE for complex logic
SELECT name,
    CASE 
        WHEN department IS NULL THEN 'No Department'
        ELSE department
    END AS dept
FROM employees;
```

#### 5️⃣ What is the difference between DELETE, TRUNCATE, and DROP?

```sql
-- DELETE - Removes specific rows
DELETE FROM employees WHERE salary < 30000;
-- ✅ Can use WHERE
-- ✅ Can rollback
-- ✅ Triggers fire
-- ❌ Slower

-- TRUNCATE - Removes all rows
TRUNCATE TABLE employees;
-- ❌ Cannot use WHERE
-- ❌ Cannot rollback (in most cases)
-- ❌ Triggers don't fire
-- ✅ Much faster

-- DROP - Removes entire table
DROP TABLE employees;
-- Deletes table structure and data
-- Cannot be rolled back
```

#### 6️⃣ Write a query to get average salary department-wise

```sql
-- Basic average
SELECT department, AVG(salary) AS avg_salary
FROM employees
GROUP BY department;

-- With employee count
SELECT 
    department,
    COUNT(*) AS emp_count,
    AVG(salary) AS avg_salary,
    MIN(salary) AS min_salary,
    MAX(salary) AS max_salary
FROM employees
GROUP BY department
ORDER BY avg_salary DESC;

-- Filter departments with avg salary > 60000
SELECT department, AVG(salary) AS avg_salary
FROM employees
GROUP BY department
HAVING AVG(salary) > 60000;

-- With department names from another table
SELECT 
    d.department_name,
    COUNT(e.id) AS emp_count,
    ROUND(AVG(e.salary), 2) AS avg_salary
FROM employees e
INNER JOIN departments d ON e.department_id = d.id
GROUP BY d.department_name
ORDER BY avg_salary DESC;
```

#### 7️⃣ Use self-join to display employee with their manager's name

```sql
-- Self-join example
SELECT 
    e.name AS employee_name,
    m.name AS manager_name
FROM employees e
LEFT JOIN employees m ON e.manager_id = m.id;

-- With employee details
SELECT 
    e.id AS emp_id,
    e.name AS employee_name,
    e.department,
    e.salary,
    COALESCE(m.name, 'No Manager') AS manager_name
FROM employees e
LEFT JOIN employees m ON e.manager_id = m.id
ORDER BY e.department, e.name;

-- Count employees per manager
SELECT 
    m.name AS manager_name,
    COUNT(e.id) AS team_size
FROM employees e
INNER JOIN employees m ON e.manager_id = m.id
GROUP BY m.id, m.name
ORDER BY team_size DESC;
```

#### 8️⃣ Find the most recent joinee in each department

```sql
-- Using ROW_NUMBER()
SELECT department, name, join_date
FROM (
    SELECT 
        department,
        name,
        join_date,
        ROW_NUMBER() OVER (PARTITION BY department ORDER BY join_date DESC) AS rn
    FROM employees
) ranked
WHERE rn = 1;

-- Using MAX with subquery
SELECT e.department, e.name, e.join_date
FROM employees e
INNER JOIN (
    SELECT department, MAX(join_date) AS max_date
    FROM employees
    GROUP BY department
) latest ON e.department = latest.department AND e.join_date = latest.max_date;

-- Using FIRST_VALUE()
SELECT DISTINCT
    department,
    FIRST_VALUE(name) OVER (PARTITION BY department ORDER BY join_date DESC) AS latest_employee,
    FIRST_VALUE(join_date) OVER (PARTITION BY department ORDER BY join_date DESC) AS join_date
FROM employees;
```

#### 9️⃣ Top 3 products by revenue

```sql
-- Basic top 3
SELECT 
    product_id,
    product_name,
    SUM(quantity * price) AS total_revenue
FROM sales
GROUP BY product_id, product_name
ORDER BY total_revenue DESC
LIMIT 3;

-- With ranking
SELECT product_name, total_revenue, revenue_rank
FROM (
    SELECT 
        product_name,
        SUM(quantity * price) AS total_revenue,
        RANK() OVER (ORDER BY SUM(quantity * price) DESC) AS revenue_rank
    FROM sales
    GROUP BY product_name
) ranked
WHERE revenue_rank <= 3;

-- Top 3 per category
SELECT category, product_name, revenue
FROM (
    SELECT 
        category,
        product_name,
        SUM(quantity * price) AS revenue,
        ROW_NUMBER() OVER (PARTITION BY category ORDER BY SUM(quantity * price) DESC) AS rn
    FROM sales
    GROUP BY category, product_name
) ranked
WHERE rn <= 3;
```

#### 🔟 How to find duplicate records?

```sql
-- Find duplicate names
SELECT name, COUNT(*) AS duplicate_count
FROM employees
GROUP BY name
HAVING COUNT(*) > 1;

-- Show all duplicate records with details
SELECT e.*
FROM employees e
INNER JOIN (
    SELECT name
    FROM employees
    GROUP BY name
    HAVING COUNT(*) > 1
) dups ON e.name = dups.name
ORDER BY e.name;

-- Find duplicates based on multiple columns
SELECT email, phone, COUNT(*) AS count
FROM customers
GROUP BY email, phone
HAVING COUNT(*) > 1;

-- Delete duplicates keeping first occurrence
DELETE e1 FROM employees e1
INNER JOIN employees e2
WHERE e1.id > e2.id 
AND e1.name = e2.name 
AND e1.email = e2.email;
```

---

### 📊 SQL Interview Questions - Advanced Level

#### 1️⃣ Difference between RANK(), ROW_NUMBER(), and DENSE_RANK()

```sql
SELECT 
    name,
    salary,
    department,
    ROW_NUMBER() OVER (ORDER BY salary DESC) AS row_num,
    RANK() OVER (ORDER BY salary DESC) AS rank_num,
    DENSE_RANK() OVER (ORDER BY salary DESC) AS dense_rank_num
FROM employees;
```

**Example Output:**

| name | salary | row_num | rank_num | dense_rank_num |
|------|--------|---------|----------|----------------|
| Abdul Kadir | 76000 | 1 | 1 | 1 |
| Nasima Khatun | 74000 | 2 | 2 | 2 |
| Md. Hasan | 72000 | 3 | 3 | 3 |
| Sharmin Akter | 71000 | 4 | 4 | 4 |
| Dilruba Akhter | 70000 | 5 | 5 | 5 |
| Rafiq Uddin | 68000 | 6 | 6 | 6 |

**Differences:**
- **ROW_NUMBER()** - Unique sequential number (1,2,3,4...)
- **RANK()** - Same rank for ties, skips numbers (1,2,2,4...)
- **DENSE_RANK()** - Same rank for ties, no gaps (1,2,2,3...)

#### 2️⃣ Find employees earning more than average in their department

```sql
-- Using correlated subquery
SELECT 
    e1.name,
    e1.department,
    e1.salary,
    (SELECT ROUND(AVG(salary), 2) 
     FROM employees e2 
     WHERE e2.department = e1.department) AS dept_avg
FROM employees e1
WHERE salary > (
    SELECT AVG(salary)
    FROM employees e2
    WHERE e2.department = e1.department
)
ORDER BY department, salary DESC;

-- Using window function
SELECT name, department, salary, dept_avg
FROM (
    SELECT 
        name,
        department,
        salary,
        AVG(salary) OVER (PARTITION BY department) AS dept_avg
    FROM employees
) emp_with_avg
WHERE salary > dept_avg
ORDER BY department, salary DESC;

-- With percentage above average
SELECT 
    name,
    department,
    salary,
    dept_avg,
    ROUND(((salary - dept_avg) / dept_avg) * 100, 2) AS pct_above_avg
FROM (
    SELECT 
        name,
        department,
        salary,
        AVG(salary) OVER (PARTITION BY department) AS dept_avg
    FROM employees
) emp_stats
WHERE salary > dept_avg
ORDER BY pct_above_avg DESC;
```

#### 3️⃣ Top 3 highest-paid employees per department

```sql
-- Using ROW_NUMBER()
SELECT department, name, salary
FROM (
    SELECT 
        department,
        name,
        salary,
        ROW_NUMBER() OVER (PARTITION BY department ORDER BY salary DESC) AS rn
    FROM employees
) ranked
WHERE rn <= 3
ORDER BY department, salary DESC;

-- Using DENSE_RANK() (handles ties better)
SELECT department, name, salary, salary_rank
FROM (
    SELECT 
        department,
        name,
        salary,
        DENSE_RANK() OVER (PARTITION BY department ORDER BY salary DESC) AS salary_rank
    FROM employees
) ranked
WHERE salary_rank <= 3
ORDER BY department, salary_rank;

-- With additional employee details
SELECT 
    department,
    name,
    age,
    salary,
    join_date,
    salary_rank
FROM (
    SELECT 
        department,
        name,
        age,
        salary,
        join_date,
        RANK() OVER (PARTITION BY department ORDER BY salary DESC) AS salary_rank
    FROM employees
) ranked
WHERE salary_rank <= 3
ORDER BY department, salary DESC;
```

#### 4️⃣ Write a query with multiple JOINs

```sql
-- Complex JOIN example with 4 tables
SELECT 
    e.name AS employee_name,
    e.salary,
    d.department_name,
    l.city,
    l.country,
    p.project_name,
    p.budget
FROM employees e
INNER JOIN departments d ON e.department_id = d.id
LEFT JOIN locations l ON d.location_id = l.id
LEFT JOIN employee_projects ep ON e.id = ep.employee_id
LEFT JOIN projects p ON ep.project_id = p.id
WHERE e.salary > 50000
ORDER BY e.salary DESC;

-- Sales analysis with multiple joins
SELECT 
    c.customer_name,
    c.email,
    o.order_date,
    p.product_name,
    oi.quantity,
    oi.unit_price,
    (oi.quantity * oi.unit_price) AS line_total,
    cat.category_name
FROM customers c
INNER JOIN orders o ON c.customer_id = o.customer_id
INNER JOIN order_items oi ON o.order_id = oi.order_id
INNER JOIN products p ON oi.product_id = p.product_id
INNER JOIN categories cat ON p.category_id = cat.category_id
WHERE o.order_date >= '2024-01-01'
ORDER BY o.order_date DESC, c.customer_name;
```

#### 5️⃣ Difference between UNION and UNION ALL

```sql
-- UNION - Removes duplicates (slower)
SELECT name, department FROM employees WHERE department = 'IT'
UNION
SELECT name, department FROM employees WHERE department = 'Finance';

-- UNION ALL - Keeps duplicates (faster)
SELECT name, department FROM employees WHERE department = 'IT'
UNION ALL
SELECT name, department FROM employees WHERE department = 'Finance';

-- Practical example: Combining current and archived data
SELECT employee_id, name, 'Active' AS status
FROM employees
UNION ALL
SELECT employee_id, name, 'Archived' AS status
FROM employees_archive
ORDER BY name;

-- Multiple unions
SELECT 'High Earner' AS category, name, salary
FROM employees WHERE salary > 70000
UNION ALL
SELECT 'Medium Earner', name, salary
FROM employees WHERE salary BETWEEN 50000 AND 70000
UNION ALL
SELECT 'Entry Level', name, salary
FROM employees WHERE salary < 50000
ORDER BY salary DESC;
```

#### 6️⃣ What is a CTE (Common Table Expression)?

```sql
-- Simple CTE
WITH high_earners AS (
    SELECT * FROM employees WHERE salary > 60000
)
SELECT department, COUNT(*) AS count, AVG(salary) AS avg_salary
FROM high_earners
GROUP BY department;

-- Multiple CTEs
WITH 
dept_avg AS (
    SELECT department, AVG(salary) AS avg_salary
    FROM employees
    GROUP BY department
),
above_avg AS (
    SELECT e.*, da.avg_salary
    FROM employees e
    INNER JOIN dept_avg da ON e.department = da.department
    WHERE e.salary > da.avg_salary
)
SELECT * FROM above_avg ORDER BY salary DESC;

-- Recursive CTE (Employee Hierarchy)
WITH RECURSIVE employee_hierarchy AS (
    -- Base case: Top-level managers
    SELECT id, name, manager_id, 1 AS level, name AS path
    FROM employees
    WHERE manager_id IS NULL
    
    UNION ALL
    
    -- Recursive case: Employees under managers
    SELECT e.id, e.name, e.manager_id, eh.level + 1,
           CONCAT(eh.path, ' > ', e.name) AS path
    FROM employees e
    INNER JOIN employee_hierarchy eh ON e.manager_id = eh.id
)
SELECT * FROM employee_hierarchy ORDER BY level, name;
```

#### 7️⃣ Optimize slow-performing SQL queries

```sql
-- ❌ Bad: SELECT *
SELECT * FROM employees WHERE department = 'IT';

-- ✅ Good: Select only needed columns
SELECT name, salary, join_date FROM employees WHERE department = 'IT';

-- ❌ Bad: No index on WHERE clause column
SELECT * FROM employees WHERE email = 'test@example.com';

-- ✅ Good: Create index
CREATE INDEX idx_email ON employees(email);
SELECT * FROM employees WHERE email = 'test@example.com';

-- ❌ Bad: Using functions on indexed column
SELECT * FROM employees WHERE YEAR(join_date) = 2023;

-- ✅ Good: Use range
SELECT * FROM employees WHERE join_date >= '2023-01-01' AND join_date < '2024-01-01';

-- ❌ Bad: Subquery in SELECT
SELECT 
    name,
    (SELECT COUNT(*) FROM orders WHERE employee_id = e.id) AS order_count
FROM employees e;

-- ✅ Good: Use JOIN
SELECT 
    e.name,
    COUNT(o.id) AS order_count
FROM employees e
LEFT JOIN orders o ON e.id = o.employee_id
GROUP BY e.id, e.name;

-- Use EXPLAIN to analyze query performance
EXPLAIN SELECT * FROM employees WHERE salary > 50000;
```

#### 8️⃣ Find consecutive dates or numbers

```sql
-- Find employees who worked on consecutive days
WITH daily_attendance AS (
    SELECT 
        employee_id,
        attendance_date,
        LAG(attendance_date) OVER (PARTITION BY employee_id ORDER BY attendance_date) AS prev_date
    FROM attendance
)
SELECT 
    employee_id,
    attendance_date,
    prev_date
FROM daily_attendance
WHERE DATEDIFF(attendance_date, prev_date) = 1;

-- Find gaps in sequential IDs
SELECT 
    a.id + 1 AS gap_start,
    (SELECT MIN(id) - 1 FROM employees b WHERE b.id > a.id) AS gap_end
FROM employees a
WHERE NOT EXISTS (SELECT 1 FROM employees b WHERE b.id = a.id + 1)
ORDER BY gap_start;
```

#### 9️⃣ Running total and cumulative sum

```sql
-- Running total using window function
SELECT 
    order_date,
    amount,
    SUM(amount) OVER (ORDER BY order_date) AS running_total
FROM sales
ORDER BY order_date;

-- Running total per category
SELECT 
    category,
    order_date,
    amount,
    SUM(amount) OVER (PARTITION BY category ORDER BY order_date) AS category_running_total
FROM sales
ORDER BY category, order_date;

-- Moving average (last 3 days)
SELECT 
    order_date,
    amount,
    AVG(amount) OVER (
        ORDER BY order_date
        ROWS BETWEEN 2 PRECEDING AND CURRENT ROW
    ) AS moving_avg_3days
FROM sales;
```

#### 🔟 Calculate percentage and rank

```sql
-- Percentage of total sales per product
SELECT 
    product_name,
    sales_amount,
    ROUND(sales_amount * 100.0 / SUM(sales_amount) OVER (), 2) AS pct_of_total,
    RANK() OVER (ORDER BY sales_amount DESC) AS sales_rank
FROM product_sales;

-- Salary percentile
SELECT 
    name,
    salary,
    department,
    PERCENT_RANK() OVER (ORDER BY salary) AS salary_percentile,
    PERCENT_RANK() OVER (PARTITION BY department ORDER BY salary) AS dept_percentile
FROM employees;

-- Quartile distribution
SELECT 
    name,
    salary,
    NTILE(4) OVER (ORDER BY salary) AS salary_quartile
FROM employees;

---

### 💼 Real Company Interview Questions

#### 🏦 Goldman Sachs - Data Analyst Questions

**SQL Questions:**

1️⃣ **Average salary department-wise**
```sql
SELECT 
    department,
    COUNT(*) AS employee_count,
    ROUND(AVG(salary), 2) AS avg_salary,
    MIN(salary) AS min_salary,
    MAX(salary) AS max_salary
FROM employees
GROUP BY department
ORDER BY avg_salary DESC;
```

2️⃣ **Self-join: Employee with Manager name**
```sql
SELECT 
    e.id AS emp_id,
    e.name AS employee_name,
    e.department,
    e.salary,
    COALESCE(m.name, 'CEO/No Manager') AS manager_name,
    m.salary AS manager_salary
FROM employees e
LEFT JOIN employees m ON e.manager_id = m.id
ORDER BY e.department, e.name;
```

3️⃣ **Most recent joinee per department using ROW_NUMBER()**
```sql
SELECT department, name, join_date, days_since_joining
FROM (
    SELECT 
        department,
        name,
        join_date,
        DATEDIFF(CURDATE(), join_date) AS days_since_joining,
        ROW_NUMBER() OVER (PARTITION BY department ORDER BY join_date DESC) AS rn
    FROM employees
) recent_hires
WHERE rn = 1
ORDER BY join_date DESC;
```

4️⃣ **Using LAG/LEAD for comparison**
```sql
-- Compare current employee salary with previous employee in same department
SELECT 
    department,
    name,
    salary,
    LAG(salary) OVER (PARTITION BY department ORDER BY salary) AS prev_emp_salary,
    LEAD(salary) OVER (PARTITION BY department ORDER BY salary) AS next_emp_salary,
    salary - LAG(salary) OVER (PARTITION BY department ORDER BY salary) AS diff_from_prev
FROM employees
ORDER BY department, salary;
```

#### 📊 General Data Analyst Interview Questions

**5️⃣ Calculate year-over-year growth**
```sql
WITH yearly_sales AS (
    SELECT 
        YEAR(order_date) AS year,
        SUM(amount) AS total_sales
    FROM sales
    GROUP BY YEAR(order_date)
)
SELECT 
    year,
    total_sales,
    LAG(total_sales) OVER (ORDER BY year) AS prev_year_sales,
    ROUND(((total_sales - LAG(total_sales) OVER (ORDER BY year)) / 
           LAG(total_sales) OVER (ORDER BY year)) * 100, 2) AS yoy_growth_pct
FROM yearly_sales
ORDER BY year;
```

**6️⃣ Customer retention rate**
```sql
-- Find customers who purchased in consecutive years
WITH customer_years AS (
    SELECT DISTINCT
        customer_id,
        YEAR(order_date) AS order_year
    FROM orders
)
SELECT 
    cy1.order_year,
    COUNT(DISTINCT cy1.customer_id) AS customers_this_year,
    COUNT(DISTINCT cy2.customer_id) AS customers_retained,
    ROUND(COUNT(DISTINCT cy2.customer_id) * 100.0 / COUNT(DISTINCT cy1.customer_id), 2) AS retention_rate
FROM customer_years cy1
LEFT JOIN customer_years cy2 
    ON cy1.customer_id = cy2.customer_id 
    AND cy2.order_year = cy1.order_year + 1
GROUP BY cy1.order_year
ORDER BY cy1.order_year;
```

**7️⃣ Cohort analysis**
```sql
WITH first_purchase AS (
    SELECT 
        customer_id,
        DATE_FORMAT(MIN(order_date), '%Y-%m') AS cohort_month
    FROM orders
    GROUP BY customer_id
),
customer_orders AS (
    SELECT 
        o.customer_id,
        fp.cohort_month,
        DATE_FORMAT(o.order_date, '%Y-%m') AS order_month,
        o.amount
    FROM orders o
    INNER JOIN first_purchase fp ON o.customer_id = fp.customer_id
)
SELECT 
    cohort_month,
    COUNT(DISTINCT customer_id) AS cohort_size,
    SUM(amount) AS total_revenue,
    ROUND(AVG(amount), 2) AS avg_order_value
FROM customer_orders
GROUP BY cohort_month
ORDER BY cohort_month;
```

**8️⃣ Find customers who never made a purchase**
```sql
SELECT 
    c.customer_id,
    c.customer_name,
    c.email,
    c.registration_date,
    DATEDIFF(CURDATE(), c.registration_date) AS days_since_registration
FROM customers c
LEFT JOIN orders o ON c.customer_id = o.customer_id
WHERE o.order_id IS NULL
ORDER BY c.registration_date;
```

**9️⃣ Product affinity analysis (items bought together)**
```sql
SELECT 
    oi1.product_id AS product_1,
    oi2.product_id AS product_2,
    COUNT(DISTINCT oi1.order_id) AS times_bought_together
FROM order_items oi1
INNER JOIN order_items oi2 
    ON oi1.order_id = oi2.order_id 
    AND oi1.product_id < oi2.product_id
GROUP BY oi1.product_id, oi2.product_id
HAVING COUNT(DISTINCT oi1.order_id) >= 5
ORDER BY times_bought_together DESC
LIMIT 10;
```

**🔟 Monthly active users (MAU)**
```sql
SELECT 
    DATE_FORMAT(activity_date, '%Y-%m') AS month,
    COUNT(DISTINCT user_id) AS monthly_active_users
FROM user_activity
WHERE activity_date >= DATE_SUB(CURDATE(), INTERVAL 12 MONTH)
GROUP BY DATE_FORMAT(activity_date, '%Y-%m')
ORDER BY month;
```

---

### 🎯 Top 50 Interview Questions Summary

#### Data Analysis Concepts

**1. What is the difference between Data Analysis and Data Analytics?**
- **Data Analysis:** Inspecting, cleaning, and summarizing data to extract insights
- **Data Analytics:** Broader field including collection, transformation, modeling, and algorithms for decision-making

**2. Explain your data cleaning process**
- Identify and handle missing values (impute or remove)
- Remove duplicate records
- Correct inconsistent data entries
- Standardize data formats (date/time)
- Validate data types and ranges
- Ensure data integrity and quality

**3. Different types of data: structured, semi-structured, unstructured**
- **Structured:** Organized in rows/columns (SQL tables)
- **Semi-structured:** Some structure but not tabular (JSON, XML)
- **Unstructured:** No predefined structure (images, videos, text)

**4. What is EDA (Exploratory Data Analysis)?**
- Understanding data structure and patterns using:
  - Descriptive statistics (mean, median, mode)
  - Visualizations (histograms, scatter plots, box plots)
  - Correlation analysis
  - Identifying outliers and anomalies

**5. What is Time Series Analysis?**
- Analyzing data points collected at time intervals
- Used for forecasting trends, seasonality, and cyclic patterns
- Examples: stock prices, sales data, weather data

**6. ETL vs ELT**
- **ETL (Extract, Transform, Load):** Transform data before loading
- **ELT (Extract, Load, Transform):** Load first, then transform (cloud-based)

**7. What is Data Warehousing?**
- Centralized repository storing integrated data from multiple sources
- Supports reporting, analysis, and decision-making
- Examples: Amazon Redshift, Google BigQuery, Snowflake

**8. Common BI Tools**
- Tableau, Power BI, QlikView, Looker, Google Data Studio

**9. Mean, Median, and Mode**
- **Mean:** Average value
- **Median:** Middle value when sorted
- **Mode:** Most frequent value

**10. Variance and Standard Deviation**
- **Variance:** Average of squared differences from mean
- **Standard Deviation:** Square root of variance (shows data spread)

#### Excel & Power BI Questions

**11. How do you clean messy data in Excel?**
- Use TRIM() to remove extra spaces
- Text to Columns for splitting data
- Find & Replace for corrections
- Data Validation for input control
- Remove Duplicates feature

**12. Pivot Table vs Power Pivot**
- **Pivot Table:** Summarizing single table data
- **Power Pivot:** Large data models, multiple tables, DAX formulas

**13. DAX Measures vs Calculated Columns**
- **Measures:** Calculated at query time (dynamic), used in visuals
- **Calculated Columns:** Computed when data loads, becomes new column

**14. Filter Context in DAX**
- Determines which rows are used in calculation
- Affected by: row context, filters, slicers

**15. Row-Level Security (RLS) in Power BI**
- Restricts data access at row level
- Based on user roles and filters
- Applied using DAX expressions

#### Python for Data Analysis

**16. Key Python libraries**
- **Pandas:** Data manipulation and analysis
- **NumPy:** Numerical computing
- **Matplotlib/Seaborn:** Data visualization
- **Scikit-learn:** Machine learning

**17. How to handle missing data in Pandas?**
```python
import pandas as pd

# Check for missing values
df.isnull().sum()

# Drop missing values
df.dropna()

# Fill missing values
df.fillna(df.mean())  # with mean
df.fillna(method='ffill')  # forward fill
df.fillna(0)  # with specific value
```

**18. Remove outliers using IQR**
```python
import numpy as np

def remove_outliers(data):
    q1 = np.percentile(data, 25)
    q3 = np.percentile(data, 75)
    iqr = q3 - q1
    lower = q1 - 1.5 * iqr
    upper = q3 + 1.5 * iqr
    return [x for x in data if lower <= x <= upper]
```

**19. Count unique values and frequencies**
```python
# Method 1: Using value_counts()
df['column'].value_counts()

# Method 2: Using Counter
from collections import Counter
data = [1, 2, 2, 3, 3, 3, 4, 4, 4, 4]
counter = Counter(data)
for value, count in counter.items():
    print(f"{value}: {count}")
```

**20. Read CSV and count null rows**
```python
import pandas as pd

df = pd.read_csv('data.csv')
null_rows = df.isnull().any(axis=1).sum()
print(f"Rows with nulls: {null_rows}")
```

---

### 📊 Data Visualization Questions

**21. What is Data Visualization?**
Graphical representation of data using charts, graphs, and maps to communicate insights clearly.

**22. Common types of visualizations**
- **Bar chart:** Comparing categories
- **Line graph:** Trends over time
- **Pie chart:** Parts of a whole
- **Scatter plot:** Relationships between variables
- **Heatmap:** Correlation matrix
- **Box plot:** Distribution and outliers

**23. Correlation vs Causation**
- **Correlation:** Two variables move together
- **Causation:** One variable directly affects the other

**24. What is a dashboard?**
Visual interface showing key metrics and KPIs in real-time, allowing users to monitor performance and make decisions.

---

### 🔥 Advanced SQL Scenarios

**25. Find employees who worked all days in a month**
```sql
WITH work_days AS (
    SELECT 22 AS expected_days  -- Working days in month
),
employee_attendance AS (
    SELECT 
        employee_id,
        COUNT(DISTINCT attendance_date) AS days_worked
    FROM attendance
    WHERE MONTH(attendance_date) = MONTH(CURDATE())
    GROUP BY employee_id
)
SELECT e.name, ea.days_worked
FROM employee_attendance ea
INNER JOIN employees e ON ea.employee_id = e.id
CROSS JOIN work_days wd
WHERE ea.days_worked = wd.expected_days;
```

**26. Calculate median salary**
```sql
-- MySQL 8.0+
WITH ordered_salaries AS (
    SELECT 
        salary,
        ROW_NUMBER() OVER (ORDER BY salary) AS row_num,
        COUNT(*) OVER () AS total_count
    FROM employees
)
SELECT AVG(salary) AS median_salary
FROM ordered_salaries
WHERE row_num IN (FLOOR((total_count + 1) / 2), CEIL((total_count + 1) / 2));
```

**27. Find the longest consecutive login streak**
```sql
WITH login_groups AS (
    SELECT 
        user_id,
        login_date,
        DATE_SUB(login_date, INTERVAL ROW_NUMBER() OVER (PARTITION BY user_id ORDER BY login_date) DAY) AS grp
    FROM user_logins
)
SELECT 
    user_id,
    MIN(login_date) AS streak_start,
    MAX(login_date) AS streak_end,
    COUNT(*) AS streak_length
FROM login_groups
GROUP BY user_id, grp
ORDER BY streak_length DESC
LIMIT 1;
```

**28. SQL query optimization techniques**
```sql
-- 1. Use indexes on frequently queried columns
CREATE INDEX idx_dept_salary ON employees(department, salary);

-- 2. Avoid SELECT *
SELECT id, name, salary FROM employees WHERE department = 'IT';

-- 3. Use EXISTS instead of IN for large datasets
SELECT name FROM employees e
WHERE EXISTS (SELECT 1 FROM departments d WHERE d.id = e.department_id);

-- 4. Limit result sets
SELECT * FROM employees ORDER BY salary DESC LIMIT 100;

-- 5. Use JOIN instead of subqueries when possible
-- Bad
SELECT name FROM employees 
WHERE department_id IN (SELECT id FROM departments WHERE location = 'Dhaka');

-- Good
SELECT e.name FROM employees e
INNER JOIN departments d ON e.department_id = d.id
WHERE d.location = 'Dhaka';
```

**29. Pivot data (transform rows to columns)**
```sql
SELECT 
    department,
    SUM(CASE WHEN YEAR(join_date) = 2021 THEN 1 ELSE 0 END) AS '2021',
    SUM(CASE WHEN YEAR(join_date) = 2022 THEN 1 ELSE 0 END) AS '2022',
    SUM(CASE WHEN YEAR(join_date) = 2023 THEN 1 ELSE 0 END) AS '2023'
FROM employees
GROUP BY department;
```

**30. Unpivot data (transform columns to rows)**
```sql
SELECT department, 2021 AS year, year_2021 AS employee_count
FROM department_summary
UNION ALL
SELECT department, 2022, year_2022
FROM department_summary
UNION ALL
SELECT department, 2023, year_2023
FROM department_summary
ORDER BY department, year;
```

---

## 📚 Advanced Topics

### Window Functions

```sql
-- ROW_NUMBER
SELECT name, salary, 
    ROW_NUMBER() OVER (ORDER BY salary DESC) AS row_num
FROM employees;

-- PARTITION BY
SELECT name, department, salary,
    RANK() OVER (PARTITION BY department ORDER BY salary DESC) AS dept_rank
FROM employees;

-- LAG and LEAD
SELECT name, salary,
    LAG(salary) OVER (ORDER BY salary) AS previous_salary,
    LEAD(salary) OVER (ORDER BY salary) AS next_salary
FROM employees;

-- NTILE - ডাটাকে N ভাগে ভাগ করা
SELECT name, salary,
    NTILE(4) OVER (ORDER BY salary DESC) AS quartile
FROM employees;
```

### Common Table Expressions (CTE)

```sql
WITH high_earners AS (
    SELECT * FROM employees WHERE salary > 50000
),
it_department AS (
    SELECT * FROM high_earners WHERE department = 'IT'
)
SELECT * FROM it_department;
```

### Recursive CTE

```sql
WITH RECURSIVE employee_hierarchy AS (
    -- Base case
    SELECT id, name, manager_id, 1 AS level
    FROM employees
    WHERE manager_id IS NULL
    
    UNION ALL
    
    -- Recursive case
    SELECT e.id, e.name, e.manager_id, eh.level + 1
    FROM employees e
    INNER JOIN employee_hierarchy eh ON e.manager_id = eh.id
)
SELECT * FROM employee_hierarchy;
```

### Pivot Table (MySQL 8.0+)

```sql
SELECT 
    department,
    SUM(CASE WHEN YEAR(join_date) = 2021 THEN 1 ELSE 0 END) AS '2021',
    SUM(CASE WHEN YEAR(join_date) = 2022 THEN 1 ELSE 0 END) AS '2022',
    SUM(CASE WHEN YEAR(join_date) = 2023 THEN 1 ELSE 0 END) AS '2023'
FROM employees
GROUP BY department;
```

### JSON Functions (MySQL 5.7+)

```sql
-- JSON কলাম তৈরি করা
CREATE TABLE products (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    attributes JSON
);

-- JSON ডাটা ইনসার্ট করা
INSERT INTO products VALUES
(1, 'Laptop', '{"brand": "Dell", "ram": "16GB", "storage": "512GB"}');

-- JSON ডাটা বের করা
SELECT 
    name,
    JSON_EXTRACT(attributes, '$.brand') AS brand,
    attributes->>'$.ram' AS ram
FROM products;

-- JSON কী আছে কিনা চেক করা
SELECT * FROM products
WHERE JSON_CONTAINS_PATH(attributes, 'one', '$.brand');
```

### Full-Text Search

```sql
-- Full-Text Index তৈরি করা
CREATE FULLTEXT INDEX idx_name_fulltext ON employees(name);

-- Full-Text Search
SELECT * FROM employees
WHERE MATCH(name) AGAINST('Ahmad');

-- Boolean Mode
SELECT * FROM employees
WHERE MATCH(name) AGAINST('+Ahmad -Reduan' IN BOOLEAN MODE);
```

---

## 🛠️ Database Design Best Practices

### Normalization

#### First Normal Form (1NF)
- প্রতিটি কলামে একটি মাত্র মান থাকবে
- প্রতিটি রো ইউনিক হবে

#### Second Normal Form (2NF)
- 1NF মেনে চলবে
- Partial dependency থাকবে না

#### Third Normal Form (3NF)
- 2NF মেনে চলবে
- Transitive dependency থাকবে না

### Entity-Relationship (ER) Diagram

**One-to-One (1:1)**
```sql
CREATE TABLE users (
    id INT PRIMARY KEY,
    name VARCHAR(100)
);

CREATE TABLE user_profiles (
    user_id INT PRIMARY KEY,
    bio TEXT,
    FOREIGN KEY (user_id) REFERENCES users(id)
);
```

**One-to-Many (1:M)**
```sql
CREATE TABLE departments (
    id INT PRIMARY KEY,
    name VARCHAR(100)
);

CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    department_id INT,
    FOREIGN KEY (department_id) REFERENCES departments(id)
);
```

**Many-to-Many (M:N)**
```sql
CREATE TABLE students (
    id INT PRIMARY KEY,
    name VARCHAR(100)
);

CREATE TABLE courses (
    id INT PRIMARY KEY,
    name VARCHAR(100)
);

CREATE TABLE enrollments (
    student_id INT,
    course_id INT,
    PRIMARY KEY (student_id, course_id),
    FOREIGN KEY (student_id) REFERENCES students(id),
    FOREIGN KEY (course_id) REFERENCES courses(id)
);
```

---

## 🔐 Data Integrity & Security

### ✅ Data Integrity Constraints

**Data Integrity** নিশ্চিত করে যে database-এ সংরক্ষিত data সঠিক, সামঞ্জস্যপূর্ণ এবং নির্ভরযোগ্য।

#### Types of Data Integrity:

**1. Entity Integrity (PRIMARY KEY)**
```sql
-- Easy Example
CREATE TABLE students (
    student_id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) UNIQUE
);

-- Complex Example with composite primary key
CREATE TABLE enrollment (
    student_id INT,
    course_id INT,
    semester VARCHAR(20),
    grade CHAR(2),
    PRIMARY KEY (student_id, course_id, semester),
    FOREIGN KEY (student_id) REFERENCES students(student_id),
    FOREIGN KEY (course_id) REFERENCES courses(course_id)
);
```

**2. Referential Integrity (FOREIGN KEY)**
```sql
-- Easy Example
CREATE TABLE orders (
    order_id INT PRIMARY KEY,
    customer_id INT,
    order_date DATE,
    FOREIGN KEY (customer_id) REFERENCES customers(customer_id)
        ON DELETE RESTRICT
        ON UPDATE CASCADE
);

-- Complex Example with multiple foreign keys
CREATE TABLE order_items (
    item_id INT PRIMARY KEY AUTO_INCREMENT,
    order_id INT NOT NULL,
    product_id INT NOT NULL,
    quantity INT NOT NULL CHECK (quantity > 0),
    price DECIMAL(10,2) NOT NULL CHECK (price >= 0),
    discount_percent DECIMAL(5,2) DEFAULT 0 CHECK (discount_percent BETWEEN 0 AND 100),
    FOREIGN KEY (order_id) REFERENCES orders(order_id)
        ON DELETE CASCADE,
    FOREIGN KEY (product_id) REFERENCES products(product_id)
        ON DELETE RESTRICT,
    INDEX idx_order (order_id),
    INDEX idx_product (product_id)
);
```

**3. Domain Integrity (CHECK, NOT NULL, DEFAULT)**
```sql
-- Easy Example
CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    age INT CHECK (age BETWEEN 18 AND 65),
    salary DECIMAL(10,2) CHECK (salary > 0),
    status VARCHAR(20) DEFAULT 'Active' CHECK (status IN ('Active', 'Inactive', 'On Leave'))
);

-- Complex Example with multiple constraints
CREATE TABLE transactions (
    transaction_id INT PRIMARY KEY AUTO_INCREMENT,
    account_id VARCHAR(20) NOT NULL,
    transaction_type ENUM('Deposit', 'Withdrawal', 'Transfer') NOT NULL,
    amount DECIMAL(15,2) NOT NULL CHECK (amount > 0),
    balance_after DECIMAL(15,2) NOT NULL CHECK (balance_after >= 0),
    transaction_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    status ENUM('Pending', 'Completed', 'Failed', 'Cancelled') DEFAULT 'Pending',
    notes TEXT,
    created_by VARCHAR(50) NOT NULL,
    FOREIGN KEY (account_id) REFERENCES accounts(account_id),
    CHECK (
        (transaction_type = 'Withdrawal' AND amount <= balance_after + amount) OR
        (transaction_type != 'Withdrawal')
    )
);
```

**4. User-Defined Integrity (Custom Business Rules)**
```sql
-- Complex Example: Business rule enforcement
DELIMITER //

CREATE TRIGGER check_employee_salary
BEFORE INSERT ON employees
FOR EACH ROW
BEGIN
    DECLARE min_sal DECIMAL(10,2);
    DECLARE max_sal DECIMAL(10,2);
    
    -- Get salary range for department
    SELECT min_salary, max_salary INTO min_sal, max_sal
    FROM salary_ranges
    WHERE department = NEW.department;
    
    -- Enforce salary within range
    IF NEW.salary < min_sal OR NEW.salary > max_sal THEN
        SIGNAL SQLSTATE '45000'
        SET MESSAGE_TEXT = 'Salary outside allowed range for department';
    END IF;
    
    -- Enforce manager must earn more than subordinates
    IF NEW.manager_id IS NOT NULL THEN
        IF NEW.salary >= (SELECT salary FROM employees WHERE id = NEW.manager_id) THEN
            SIGNAL SQLSTATE '45000'
            SET MESSAGE_TEXT = 'Employee cannot earn more than their manager';
        END IF;
    END IF;
END //

DELIMITER ;
```

### ✅ GRANT and REVOKE - Access Control

#### GRANT - Giving Permissions

**Easy Example 1: Basic SELECT permission**
```sql
-- Create user
CREATE USER 'readonly_user'@'localhost' IDENTIFIED BY 'password123';

-- Grant SELECT only on specific database
GRANT SELECT ON company_db.* TO 'readonly_user'@'localhost';

-- Apply changes
FLUSH PRIVILEGES;
```

**Easy Example 2: Multiple permissions**
```sql
CREATE USER 'developer'@'localhost' IDENTIFIED BY 'dev_pass123';

-- Grant multiple permissions
GRANT SELECT, INSERT, UPDATE, DELETE ON company_db.* TO 'developer'@'localhost';

FLUSH PRIVILEGES;
```

**Complex Example: Granular permissions**
```sql
-- Create different user roles

-- 1. Data Entry User (can only INSERT and SELECT)
CREATE USER 'data_entry'@'%' IDENTIFIED BY 'entry_pass';
GRANT SELECT, INSERT ON company_db.employees TO 'data_entry'@'%';
GRANT SELECT ON company_db.departments TO 'data_entry'@'%';

-- 2. Analyst User (SELECT on all tables, can create views)
CREATE USER 'analyst'@'%' IDENTIFIED BY 'analyst_pass';
GRANT SELECT ON company_db.* TO 'analyst'@'%';
GRANT CREATE VIEW ON company_db.* TO 'analyst'@'%';

-- 3. Manager (SELECT, UPDATE salary but not delete)
CREATE USER 'manager'@'localhost' IDENTIFIED BY 'manager_pass';
GRANT SELECT, UPDATE (salary, department) ON company_db.employees TO 'manager'@'localhost';
GRANT SELECT ON company_db.* TO 'manager'@'localhost';

-- 4. DBA (all privileges)
CREATE USER 'admin'@'localhost' IDENTIFIED BY 'admin_strong_pass';
GRANT ALL PRIVILEGES ON company_db.* TO 'admin'@'localhost';
GRANT SUPER, PROCESS, RELOAD ON *.* TO 'admin'@'localhost';

-- 5. Application User (specific operations only)
CREATE USER 'app_user'@'192.168.1.%' IDENTIFIED BY 'app_secure_pass';
GRANT SELECT, INSERT, UPDATE, DELETE ON company_db.orders TO 'app_user'@'192.168.1.%';
GRANT SELECT, INSERT ON company_db.order_items TO 'app_user'@'192.168.1.%';
GRANT EXECUTE ON PROCEDURE company_db.process_order TO 'app_user'@'192.168.1.%';

FLUSH PRIVILEGES;
```

**GRANT Syntax Options:**
```sql
-- Grant on all databases
GRANT SELECT ON *.* TO 'user'@'host';

-- Grant on specific database
GRANT SELECT ON database_name.* TO 'user'@'host';

-- Grant on specific table
GRANT SELECT ON database_name.table_name TO 'user'@'host';

-- Grant specific columns
GRANT SELECT (id, name), UPDATE (salary) ON database_name.employees TO 'user'@'host';

-- Grant with GRANT OPTION (can grant to others)
GRANT SELECT ON database_name.* TO 'user'@'host' WITH GRANT OPTION;
```

#### REVOKE - Removing Permissions

**Easy Example 1: Remove specific permission**
```sql
-- Remove INSERT permission
REVOKE INSERT ON company_db.* FROM 'developer'@'localhost';

FLUSH PRIVILEGES;
```

**Easy Example 2: Remove all permissions**
```sql
-- Remove all privileges from user
REVOKE ALL PRIVILEGES ON company_db.* FROM 'developer'@'localhost';

FLUSH PRIVILEGES;
```

**Complex Example: Managing permissions**
```sql
-- Scenario: Developer promoted to Senior Developer

-- 1. Remove old restricted permissions
REVOKE ALL PRIVILEGES ON company_db.employees FROM 'developer'@'localhost';

-- 2. Grant new broader permissions
GRANT SELECT, INSERT, UPDATE, DELETE ON company_db.* TO 'developer'@'localhost';
GRANT CREATE, ALTER, DROP ON company_db.* TO 'developer'@'localhost';
GRANT EXECUTE ON company_db.* TO 'developer'@'localhost';

-- 3. But restrict access to sensitive tables
REVOKE ALL PRIVILEGES ON company_db.salary_history FROM 'developer'@'localhost';
REVOKE ALL PRIVILEGES ON company_db.audit_logs FROM 'developer'@'localhost';

FLUSH PRIVILEGES;

-- Verify permissions
SHOW GRANTS FOR 'developer'@'localhost';
```

#### View and Manage User Permissions

```sql
-- Show all users
SELECT User, Host FROM mysql.user;

-- Show specific user's permissions
SHOW GRANTS FOR 'username'@'localhost';

-- Show current user's permissions
SHOW GRANTS FOR CURRENT_USER();

-- Complex query: Audit all user permissions
SELECT 
    grantee,
    table_schema,
    privilege_type,
    is_grantable
FROM information_schema.schema_privileges
WHERE table_schema = 'company_db'
ORDER BY grantee, table_schema, privilege_type;
```

### ✅ Database Security Best Practices

#### 1. Strong Password Policies

```sql
-- Easy Example: Create user with strong password
CREATE USER 'secure_user'@'localhost' 
IDENTIFIED BY 'Str0ng!P@ssw0rd#2025'
PASSWORD EXPIRE INTERVAL 90 DAY
FAILED_LOGIN_ATTEMPTS 3
PASSWORD_LOCK_TIME 2;

-- Set password expiry for existing user
ALTER USER 'existing_user'@'localhost' PASSWORD EXPIRE;
```

#### 2. Principle of Least Privilege

```sql
-- Easy Example: Give minimum required permissions
CREATE USER 'report_user'@'localhost' IDENTIFIED BY 'report_pass';

-- Only SELECT on specific views (not raw tables)
GRANT SELECT ON company_db.employee_summary_view TO 'report_user'@'localhost';
GRANT SELECT ON company_db.sales_report_view TO 'report_user'@'localhost';

-- No access to sensitive data
-- No INSERT, UPDATE, DELETE, or administrative privileges
```

#### 3. IP Whitelisting

```sql
-- Easy Example: Restrict user to specific IP
CREATE USER 'remote_app'@'192.168.1.100' IDENTIFIED BY 'app_password';
GRANT SELECT, INSERT, UPDATE ON company_db.* TO 'remote_app'@'192.168.1.100';

-- Allow from subnet
CREATE USER 'office_user'@'192.168.1.%' IDENTIFIED BY 'office_pass';
GRANT SELECT ON company_db.* TO 'office_user'@'192.168.1.%';
```

#### 4. Audit Logging

```sql
-- Complex Example: Create audit trail
CREATE TABLE audit_log (
    log_id BIGINT PRIMARY KEY AUTO_INCREMENT,
    table_name VARCHAR(64),
    operation VARCHAR(10),
    user_name VARCHAR(100),
    ip_address VARCHAR(45),
    old_values JSON,
    new_values JSON,
    timestamp TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    INDEX idx_timestamp (timestamp),
    INDEX idx_table (table_name),
    INDEX idx_user (user_name)
);

-- Trigger for auditing employee changes
DELIMITER //

CREATE TRIGGER audit_employee_update
AFTER UPDATE ON employees
FOR EACH ROW
BEGIN
    INSERT INTO audit_log (table_name, operation, user_name, old_values, new_values)
    VALUES (
        'employees',
        'UPDATE',
        USER(),
        JSON_OBJECT(
            'id', OLD.id,
            'name', OLD.name,
            'salary', OLD.salary,
            'department', OLD.department
        ),
        JSON_OBJECT(
            'id', NEW.id,
            'name', NEW.name,
            'salary', NEW.salary,
            'department', NEW.department
        )
    );
END //

DELIMITER ;
```

#### 5. SQL Injection Prevention

```sql
-- ❌ BAD: Vulnerable to SQL Injection
-- Never concatenate user input directly into SQL
SELECT * FROM users WHERE username = '$username' AND password = '$password';
-- User could input: admin' OR '1'='1' --

-- ✅ GOOD: Use Prepared Statements
PREPARE stmt FROM 'SELECT * FROM users WHERE username = ? AND password = ?';
SET @username = 'john';
SET @password = 'secret';
EXECUTE stmt USING @username, @password;
DEALLOCATE PREPARE stmt;

-- ✅ GOOD: In stored procedures (automatic parameterization)
DELIMITER //

CREATE PROCEDURE authenticate_user(
    IN p_username VARCHAR(50),
    IN p_password VARCHAR(255)
)
BEGIN
    SELECT id, name, email
    FROM users
    WHERE username = p_username 
    AND password_hash = SHA2(p_password, 256)
    AND is_active = 1;
END //

DELIMITER ;
```

#### 6. Encryption

```sql
-- Easy Example: Encrypt sensitive data
CREATE TABLE user_credentials (
    user_id INT PRIMARY KEY,
    username VARCHAR(50) NOT NULL UNIQUE,
    password_hash VARCHAR(255) NOT NULL,  -- Never store plain text passwords
    email_encrypted VARBINARY(255),       -- Encrypted email
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

-- Insert with encryption
INSERT INTO user_credentials (user_id, username, password_hash, email_encrypted)
VALUES (
    1,
    'john_doe',
    SHA2('password123', 256),  -- Hash password
    AES_ENCRYPT('john@example.com', 'encryption_key')  -- Encrypt email
);

-- Retrieve with decryption
SELECT 
    user_id,
    username,
    AES_DECRYPT(email_encrypted, 'encryption_key') AS email
FROM user_credentials;
```

#### 7. Regular Security Audits

```sql
-- Complex Example: Security audit query
-- Check for users with excessive privileges
SELECT 
    User AS username,
    Host,
    Select_priv, Insert_priv, Update_priv, Delete_priv,
    Create_priv, Drop_priv, Grant_priv, Super_priv,
    CASE 
        WHEN Super_priv = 'Y' THEN 'CRITICAL: Has SUPER privilege'
        WHEN Grant_priv = 'Y' THEN 'WARNING: Can grant privileges'
        WHEN Drop_priv = 'Y' THEN 'WARNING: Can drop tables'
        ELSE 'Normal'
    END AS security_risk
FROM mysql.user
WHERE User != 'root'
ORDER BY Super_priv DESC, Grant_priv DESC;

-- Check for users without password
SELECT User, Host
FROM mysql.user
WHERE authentication_string = '' OR authentication_string IS NULL;

-- Check for users with wildcard host
SELECT User, Host
FROM mysql.user
WHERE Host = '%'
ORDER BY User;
```

---

## 📊 Backup & Recovery

### Database Backup (Command Line)

```bash
# পুরো ডাটাবেজ ব্যাকআপ
mysqldump -u username -p database_name > backup.sql

# নির্দিষ্ট টেবিল ব্যাকআপ
mysqldump -u username -p database_name table1 table2 > backup.sql

# সব ডাটাবেজ ব্যাকআপ
mysqldump -u username -p --all-databases > all_databases.sql
```

### Database Restore

```bash
# ব্যাকআপ থেকে রিস্টোর করা
mysql -u username -p database_name < backup.sql
```

---

## 💡 Tips & Tricks

### 1. Copy Table Structure

```sql
-- শুধু স্ট্রাকচার কপি
CREATE TABLE employees_copy LIKE employees;

-- স্ট্রাকচার ও ডাটা কপি
CREATE TABLE employees_backup AS SELECT * FROM employees;
```

### 2. Insert if Not Exists

```sql
INSERT INTO employees (id, name, department)
SELECT 1, 'John', 'IT'
WHERE NOT EXISTS (SELECT 1 FROM employees WHERE id = 1);
```

### 3. Update with Join

```sql
UPDATE employees e
INNER JOIN departments d ON e.department_id = d.id
SET e.department_name = d.name;
```

### 4. Delete with Join

```sql
DELETE e
FROM employees e
INNER JOIN departments d ON e.department_id = d.id
WHERE d.location = 'Closed';
```

### 5. Random Rows

```sql
SELECT * FROM employees ORDER BY RAND() LIMIT 5;
```

### 6. Find Second Highest Salary

```sql
SELECT MAX(salary) 
FROM employees 
WHERE salary < (SELECT MAX(salary) FROM employees);
```

### 7. Comma-Separated Values

```sql
SELECT GROUP_CONCAT(name SEPARATOR ', ') AS employee_names
FROM employees
WHERE department = 'IT';
```

### 8. Running Total

```sql
SELECT name, salary,
    SUM(salary) OVER (ORDER BY id) AS running_total
FROM employees;
```

---

## 📖 Learning Resources

### Online Resources
- [MySQL Official Documentation](https://dev.mysql.com/doc/)
- [W3Schools SQL Tutorial](https://www.w3schools.com/sql/)
- [SQLZoo](https://sqlzoo.net/)
- [LeetCode SQL Problems](https://leetcode.com/problemset/database/)

### Books
- "MySQL Cookbook" by Paul DuBois
- "Learning SQL" by Alan Beaulieu
- "High Performance MySQL" by Baron Schwartz

### Practice Platforms
- [HackerRank SQL](https://www.hackerrank.com/domains/sql)
- [StrataScratch](https://www.stratascratch.com/)
- [DataLemur](https://datalemur.com/)

---

## 🎯 SQL Checklist

### 📚 Foundations
- [ ] SQL & RDBMS বুঝা
- [ ] Data Types জানা
- [ ] Database তৈরি করা

### 🔍 Data Querying
- [ ] SELECT, WHERE, ORDER BY
- [ ] DISTINCT & LIMIT
- [ ] BETWEEN, IN, LIKE
- [ ] AND, OR, NOT

### 🧮 Data Aggregation
- [ ] COUNT, SUM, AVG, MIN, MAX
- [ ] GROUP BY & HAVING

### 🔗 Joins
- [ ] INNER JOIN
- [ ] LEFT JOIN
- [ ] RIGHT JOIN
- [ ] FULL OUTER JOIN
- [ ] SELF JOIN

### 🧱 Table Operations
- [ ] INSERT INTO
- [ ] UPDATE
- [ ] DELETE
- [ ] ALTER TABLE
- [ ] DROP TABLE

### ⚙️ Advanced SQL
- [ ] Subqueries
- [ ] CASE WHEN
- [ ] Window Functions
- [ ] CTEs
- [ ] Views
- [ ] Indexes
- [ ] Transactions
- [ ] Stored Procedures
- [ ] Triggers

---

## 💻 Practice Resources

### Sample Database
একটি complete sample database setup করতে:
```bash
# Coming soon: sample-database.sql
mysql -u root -p < examples/sample-database.sql
```

### Practice Exercises
প্রতিটি topic এর জন্য practice questions আছে। শুরু করুন:
1. Basic queries থেকে শুরু করুন
2. প্রতিদিন অন্তত 5টি query practice করুন
3. Complex queries তে move করুন
4. Real-world scenarios solve করুন

---

## 📈 Progress Tracking

নিচের checklist ব্যবহার করে আপনার progress track করুন:

- [ ] SQL Basics & Introduction
- [ ] Database Operations (CREATE, USE, DROP)
- [ ] Data Types mastered
- [ ] DDL Commands (CREATE TABLE, ALTER, DROP)
- [ ] DML Commands (INSERT, UPDATE, DELETE)
- [ ] SELECT queries with WHERE, ORDER BY
- [ ] GROUP BY and HAVING
- [ ] All types of JOINs
- [ ] Subqueries
- [ ] Views
- [ ] CTEs (Common Table Expressions)
- [ ] Window Functions
- [ ] Indexes and Performance
- [ ] Transactions
- [ ] Stored Procedures
- [ ] Triggers
- [ ] Interview Questions Practice

---

## 🤝 Contributing

এই repository কে আরও ভালো করতে আপনার contribution স্বাগতম!

### How to Contribute:

1. **Fork** this repository
2. Create a new **branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. Open a **Pull Request**

### Contribution Ideas:
- ✅ Add more examples
- ✅ Translate content to other languages
- ✅ Fix typos or errors
- ✅ Add practice exercises
- ✅ Improve documentation
- ✅ Add video tutorials links
- ✅ Share real-world use cases

---

## 📧 Contact & Support

### Questions or Feedback?
- **GitHub Issues:** [Create an issue](https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced/issues)
- **Discussions:** [Join discussions](https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced/discussions)

### Found this helpful?
- ⭐ **Star** this repository
- 🔀 **Fork** it for your own learning
- 📢 **Share** with others who might benefit

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

এর মানে আপনি freely:
- ✅ Use করতে পারবেন
- ✅ Modify করতে পারবেন
- ✅ Distribute করতে পারবেন
- ✅ Commercial purposes এ use করতে পারবেন

---

## 👨‍💻 Author

**Reduan Ahmad**
- 🌐 GitHub: [@Hazrat-Ali9](https://github.com/Hazrat-Ali9)
- 💼 LinkedIn: [Connect with me](https://www.linkedin.com/in/hazratali9/)
- 📧 Email: [Contact](programmer.hazratali@gmail.com)

---

## 🙏 Acknowledgments

ধন্যবাদ:
- All contributors যারা এই project কে improve করেছেন
- MySQL এবং PostgreSQL communities
- সকল developers যারা open source এ contribute করেন

---

## 🌟 Star History

যদি এই repository আপনার কাজে লাগে, তাহলে একটা ⭐ দিয়ে সাপোর্ট করুন!

[![Star History Chart](https://api.star-history.com/svg?repos=https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced&type=Date)](https://star-history.com/#https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced)

---

## 📊 Repository Stats

![GitHub repo size](https://img.shields.io/github/repo-size/https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced)
![GitHub language count](https://img.shields.io/github/languages/count/https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced)
![GitHub top language](https://img.shields.io/github/languages/top/https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced)
![GitHub last commit](https://img.shields.io/github/last-commit/https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced)

---

<div align="center">

### Made with ❤️ by [Hazrat Ali](https://github.com/Hazrat-Ali9/MySQL-Database-Basic-To-Advanced)

**Happy Learning! 🚀**

[⬆ Back to Top](#-all-about-mysql---complete-sql-learning-guide)

</div>
