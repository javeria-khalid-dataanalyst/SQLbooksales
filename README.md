# SQLbooksales# 📚 Online Book Sales Analysis | MySQL

## 📊 Project Overview

This project analyzes an **online book sales dataset** using **MySQL** to explore book performance, customer behavior, sales activity, revenue, and inventory.

The analysis is structured around a series of **business questions**, starting with basic SQL queries and progressing to more advanced analytical questions.

The goal was not only to practice SQL syntax, but to understand how SQL can be used to transform raw sales data into meaningful business insights.

---

## 🎯 Business Objective

The objective of this project is to analyze an online bookstore's sales data and answer questions related to:

* 📖 Book and genre performance
* 👥 Customer purchasing behavior
* 🛒 Order and sales activity
* 💰 Revenue generation
* ✍️ Author performance
* 📦 Inventory levels

---

## 🗂️ Dataset

The project uses three main tables:

### 📖 Books

Contains information about the books available in the store.

Typical fields include:

* `book_id`
* `title`
* `author`
* `genre`
* `price`
* `stock`
* `publication_year`

### 👥 Customers

Contains customer information.

Typical fields include:

* `customer_id`
* `name`
* `country`
* `city`

### 🛒 Orders

Contains information about customer purchases.

Typical fields include:

* `order_id`
* `customer_id`
* `book_id`
* `order_date`
* `quantity`
* `total_amount`

---

# 🔎 Analysis Questions

## 🟢 Basic SQL Analysis

The first part of the project focuses on fundamental SQL operations.

### 1. Fiction Books

Retrieve all books belonging to the **Fiction** genre.

### 2. Books Published After 1950

Identify books published after the year **1950**.

### 3. Canadian Customers

List all customers from **Canada**.

### 4. November 2023 Orders

Retrieve orders placed during **November 2023**.

### 5. Total Book Stock

Calculate the total number of books currently available in stock.

### 6. Most Expensive Book

Find the details of the book with the highest price.

### 7. Multiple-Quantity Orders

Identify customers who ordered more than one quantity of a book.

### 8. High-Value Orders

Retrieve orders where the total amount exceeds **$20**.

### 9. Available Genres

List all unique genres available in the Books table.

### 10. Lowest Stock Book

Find the book with the lowest available stock.

### 11. Total Revenue

Calculate the total revenue generated from all orders.

---

# 🔵 Advanced SQL Analysis

The second part focuses on more analytical business questions.

### 1. Books Sold by Genre

Calculate the total number of books sold for each genre.

### 2. Average Fantasy Book Price

Calculate the average price of books belonging to the **Fantasy** genre.

### 3. Repeat Customers

Identify customers who have placed at least **2 orders**.

### 4. Most Frequently Ordered Book

Find the book that has been ordered most frequently.

### 5. Top 3 Fantasy Books by Price

Retrieve the **3 most expensive books** in the Fantasy genre.

### 6. Books Sold by Author

Calculate the total quantity of books sold by each author.

### 7. High-Spending Customer Cities

Identify the cities where customers who spent more than **$30** are located.

### 8. Highest-Spending Customer

Find the customer who spent the most across their orders.

### 9. Remaining Stock

Calculate the stock remaining after fulfilling all recorded orders.

---

# 🛠️ Tools & Technologies

**Database:** MySQL

**Tools:**

* MySQL Workbench
* GitHub

**SQL Concepts Used:**

* `SELECT`
* `WHERE`
* `DISTINCT`
* `ORDER BY`
* `LIMIT`
* `GROUP BY`
* `HAVING`
* Aggregate Functions
* `JOIN`
* Filtering and Sorting
* Business-oriented SQL Analysis

---

# 🧠 Key Learning Outcomes

Through this project, I practiced moving beyond individual SQL commands and applying SQL to practical analytical questions.

### I strengthened my ability to:

✔ Filter and sort data efficiently
✔ Perform aggregations and calculations
✔ Analyze customers and purchasing behavior
✔ Compare product and genre performance
✔ Work with dates and order information
✔ Use joins to connect related tables
---

# 📈 Analysis Approach

The project follows a simple analytical workflow:

**Raw Data**
↓
**Understand Tables & Relationships**
↓
**Define Business Questions**
↓
**Write SQL Queries**
↓
**Analyze Results**
↓
**Extract Business Insights**

---

# 💡 Business Value

An online bookstore could use this type of analysis to better understand:

* Which genres and books generate demand
* Which customers are repeat buyers
* Which customers contribute the most revenue
* Which authors sell the most books
* Which products may require inventory attention
* How sales are distributed across customers and products

---

# 📁 Repository Structure

# 🚀 Future Improvements

Possible next steps for this project include:

* Creating additional customer segmentation analysis
* Analyzing monthly sales trends
* Identifying best-selling books over time
* Adding profit analysis if cost data becomes available
* Connecting the cleaned SQL dataset to Power BI
* Building an interactive sales dashboard

---

## 👩‍💻 About

**Javeria Khalid**
Junior Data Analyst | SQL | Power BI | Data Cleaning

This project is part of my growing data analytics portfolio, where I focus on developing practical skills through hands-on projects.

---

⭐ **If you find this project useful, feel free to explore the SQL queries and analysis.**
