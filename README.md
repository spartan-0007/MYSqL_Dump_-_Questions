# 🗄️ SQL Practice Repository (Employee Database)

This repository contains:

* 📦 A MySQL database dump (`company_dump.sql`)
* ❓ A collection of SQL interview questions
* 🧠 Designed for practicing real-world SQL queries (joins, aggregations, window functions, etc.)

---

# 🚀 Getting Started

## 📥 1. Clone the Repository

```bash
git clone https://github.com/your-username/sql-practice.git
cd sql-practice
```

---

## 🧱 2. Create Database

Login to MySQL:

```bash
mysql -u root -p
```

Create database:

```sql
CREATE DATABASE company;
```

Exit MySQL:

```sql
exit;
```

---

## 📂 3. Import Database Dump

Run the following command from terminal:

```bash
mysql -u root -p company < company_dump.sql
```

✅ This will:

* Create all tables (`employees`, `departments`)
* Insert sample data (~500 records)

---

## 🔍 4. Verify Data

Login again:

```bash
mysql -u root -p
```

```sql
USE company;

SHOW TABLES;

SELECT COUNT(*) FROM employees;
```

---

# 🧠 SQL Practice Questions

All questions are available in:

```
questions.sql / questions.md
```

---

# 📌 Sample Questions

* Find top 3 salaries per department
* Get employees with highest salary in each department
* Find duplicate records
* Find employees earning above average salary
* Perform joins between employees and departments

---

# 🧪 How to Practice

1. Read a question
2. Write your SQL query
3. Execute on the `company` database
4. Validate results

---

# ⚡ Recommended Topics

* Joins (INNER, LEFT, RIGHT)
* Group By & Aggregations
* Subqueries
* Window Functions (`RANK`, `DENSE_RANK`)
* Indexing & Performance

---

# 🛠️ Requirements

* MySQL 5.7+ (or MySQL 8 recommended)
* Basic SQL knowledge

---

# 💡 Tips

* Use `EXPLAIN` to analyze queries
* Try optimizing queries with indexes
* Practice writing clean and readable SQL

---

# 🤝 Contributing

Feel free to:

* Add more questions
* Improve queries
* Optimize existing solutions

---

# ⭐ Support

If you find this useful, give it a ⭐ on GitHub!

---

Happy Learning 🚀
