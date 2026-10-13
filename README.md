# 🛒 Retail Sales and Inventory Analytics System Using MySQL

## 📌 Project Overview

The **Retail Sales and Inventory Analytics System Using MySQL** is a SQL-based database project designed to manage and analyze retail business data. It organizes information about customers, products, stores, sales transactions, sale items, product categories, and purchase orders.

The project uses MySQL queries to generate meaningful business insights, monitor inventory levels, calculate sales revenue and estimated profit, analyze customer purchasing behavior, and track supplier orders.

## 🎯 Project Objectives

- Design a relational database for retail sales and inventory management.
- Store and manage customer, product, store, sales, and purchase order information.
- Analyze sales revenue, product performance, and customer spending.
- Identify low-stock and out-of-stock products.
- Track pending, partially received, and delayed purchase orders.
- Practice SQL queries for real-world business analysis and decision-making.

## 🛠️ Technologies Used

- **Database:** MySQL
- **Query Language:** SQL
- **Database Tool:** MySQL Workbench or another compatible MySQL client

## 🗄️ Database Structure

The project uses the database `RETAIL_ANALYTICS_DB` and includes seven main tables.

| Table | Description |
|---|---|
| `CUSTOMERS` | Stores customer IDs, names, contact details, cities, and registration dates. |
| `PRODUCTS` | Stores product names, categories, suppliers, cost prices, selling prices, stock quantities, and reorder levels. |
| `CATEGORIES` | Maintains product category IDs and unique category names. |
| `STORES` | Stores retail store names and their city and state. |
| `SALES` | Records customer transactions, store IDs, sale dates, sale statuses, and payment methods. |
| `SALEITEMS` | Stores the products sold in each transaction, quantities, unit prices, and discount percentages. |
| `PURCHASEORDERS` | Tracks product orders, expected and received dates, ordered and received quantities, and purchase statuses. |

Primary keys and foreign keys establish relationships between tables and help maintain data integrity.

## ✨ Key Features

### 1. Database Design and Data Management
- Create a database and relational tables.
- Define primary keys, foreign keys, unique constraints, default values, and check constraints.
- Insert sample customer, product, store, sales, and purchase order records.
- Perform `UPDATE` and `DELETE` operations with appropriate conditions.

### 2. Sales Analysis
- Calculate total revenue from completed sales after discounts.
- Identify the top five customers by spending.
- Find the highest-revenue products and product categories.
- Compare sales across stores and months.
- Analyze payment methods and sale statuses.

### 3. Inventory Management
- Identify products below their reorder levels.
- Find products that are out of stock.
- Calculate inventory value using cost price and stock quantity.
- Compare ordered quantities with received quantities.
- Identify products requiring reorder without pending purchase orders.

### 4. Customer Analysis
- Calculate total spending and average sale value.
- Find customers who have never placed a sale.
- Analyze customer activity and purchasing patterns.
- Identify customers who purchase products from multiple categories.

### 5. Purchase Order Analysis
- Track pending and partially received orders.
- Calculate the number of days taken to receive products.
- Identify purchase orders received later than expected.
- Compare ordered and received quantities.

## 📚 SQL Concepts Covered

The SQL script demonstrates practical use of the following concepts:

- **DDL:** `CREATE DATABASE`, `CREATE TABLE`, `ALTER TABLE`, `DROP VIEW`
- **DML:** `INSERT`, `UPDATE`, `DELETE`
- **DQL:** `SELECT`, `WHERE`, `DISTINCT`
- **Filtering and operators:** `AND`, `OR`, `IN`, `BETWEEN`, `LIKE`, `IS NULL`
- **Aggregate functions:** `COUNT()`, `SUM()`, `AVG()`, `MIN()`, `MAX()`
- **Grouping and sorting:** `GROUP BY`, `HAVING`, `ORDER BY`, `LIMIT`
- **Joins:** `INNER JOIN`, `LEFT JOIN`
- **Functions:** String, mathematical, date and time functions
- **Conditional logic:** `CASE WHEN`, `COALESCE()`
- **Advanced querying:** Subqueries, multi-table analysis, and business KPI queries
- **Views:** Creating, querying, replacing, and dropping views

## 📊 Business Questions Answered

The project includes queries designed to answer questions such as:

1. What is the total revenue generated from completed sales?
2. Who are the top five customers based on total spending?
3. Which product generates the highest revenue?
4. Which product category performs best in terms of revenue?
5. Which payment method is used most frequently?
6. Which products require restocking?
7. Which purchase orders are pending or delayed?
8. Which store generates the highest completed-sales revenue?
9. What is the estimated gross profit by product?
10. Which customers have never placed a sale?

## ⚙️ How to Run the Project

1. Install and open MySQL Workbench, or use another compatible MySQL client.
2. Download or clone this repository.
3. Open the provided `.sql` file in your SQL editor.
4. Connect to your MySQL server.
5. Execute the script in order to create the database, tables, and sample data.
6. Run individual analysis queries to explore the results.

**Note:** The SQL script contains database creation, data insertion, table alterations, analysis queries, and other database operations. Review the script before rerunning it against an existing database.



## 🎓 Learning Outcomes

Through this project, I practiced relational database design, data manipulation, SQL query writing, multi-table joins, aggregate analysis, subqueries, views, and business-oriented data analysis.

The project demonstrates how SQL can transform structured retail data into useful insights for sales performance evaluation, inventory control, and operational decision-making.

## 👨‍💻 Author

**Suraj Thange**

BE Computer Science Graduate | Aspiring Data Analyst

## ⭐ Support

If you find this project useful for learning MySQL and SQL-based data analytics, consider giving the repository a star!
