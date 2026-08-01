# Online-Book-Store-SQL-Project
This project simulates an online bookstore using SQL with three tables: Books, Customers, and Orders. It answers business questions by identifying bestselling books, calculating total revenue, tracking stock, finding top customers, and analyzing sales by genre and author to generate meaningful business insights.
# 📚 Online Book Store SQL Project

## Overview

The **Online Book Store SQL Project** is a database management and business analysis project developed using **PostgreSQL**. It simulates the operations of an online bookstore by storing and managing information about books, customers, and orders in a relational database. The project demonstrates how SQL can be used not only to create and manage databases but also to solve real-world business problems through data analysis.

The database consists of three interconnected tables: **Books**, **Customers**, and **Orders**. These tables are linked using primary and foreign keys, allowing efficient storage and retrieval of information. After designing the database, CSV files are imported into PostgreSQL, and multiple SQL queries are written to analyze sales, customer behavior, inventory, and revenue.

This project focuses on applying SQL concepts to practical business scenarios rather than simply storing data. Each query answers a meaningful business question that could help a bookstore make better decisions regarding inventory management, customer engagement, and sales performance.

---

## Project Objectives

The primary objective of this project is to strengthen SQL skills by building a complete relational database and performing business-oriented data analysis. The project covers the complete workflow of database development, including database creation, table design, data import, querying, and reporting.

The goals include:

* Designing a normalized relational database.
* Importing structured data from CSV files.
* Writing efficient SQL queries for data retrieval.
* Performing sales and customer analysis.
* Understanding relationships between multiple tables.
* Generating business insights from transactional data.

---

## Database Structure

The project contains three relational tables.

### Books

The **Books** table stores complete information about every book available in the bookstore.

It includes:

* Book ID
* Title
* Author
* Genre
* Published Year
* Price
* Stock Quantity

This table acts as the product catalog and helps monitor inventory, pricing, and book categories.

---

### Customers

The **Customers** table contains customer information required for order management.

It stores:

* Customer ID
* Customer Name
* Email Address
* Phone Number
* City
* Country

This information is useful for customer segmentation and geographical sales analysis.

---

### Orders

The **Orders** table records every purchase made by customers.

It contains:

* Order ID
* Customer ID
* Book ID
* Order Date
* Quantity Purchased
* Total Amount

Foreign keys connect the Orders table with both the Books and Customers tables, enabling complete transaction analysis.

---

## Database Relationships

The project uses relational database concepts to connect all tables.

* One customer can place multiple orders.
* One book can appear in multiple orders.
* Every order belongs to one customer.
* Every order references one book.

These relationships help maintain data integrity and avoid redundancy while enabling complex SQL queries through joins.

---

## Data Import

After creating the database schema, data is imported from CSV files using PostgreSQL's **COPY** command.

The imported datasets include:

* Books.csv
* Customers.csv
* Orders.csv

Using CSV files makes the project realistic because many real-world organizations import data from external systems in the same way.

---

## SQL Concepts Applied

The project demonstrates a wide variety of SQL concepts commonly used in industry.

These include:

* CREATE DATABASE
* CREATE TABLE
* PRIMARY KEY
* FOREIGN KEY
* COPY FROM CSV
* SELECT
* WHERE
* ORDER BY
* GROUP BY
* HAVING
* DISTINCT
* LIMIT
* INNER JOIN
* LEFT JOIN
* Aggregate Functions
* COALESCE()

Each concept is applied within practical business scenarios rather than isolated examples.

---

## Business Analysis

One of the main highlights of the project is solving business problems using SQL.

### Book Analysis

The project retrieves books based on genre, publication year, price, and availability.

Examples include:

* Finding all Fantasy books
* Listing books published after a certain year
* Identifying the most expensive book
* Finding books with the lowest stock
* Displaying available genres

These queries help understand product distribution and inventory.

---

### Customer Analysis

Customer data is analyzed to understand purchasing behavior.

Examples include:

* Listing customers from a specific country
* Identifying customers with multiple orders
* Finding customers with the highest spending
* Discovering cities generating the highest revenue

Such insights can support targeted marketing strategies.

---

### Sales Analysis

Sales-related SQL queries provide meaningful business metrics.

Examples include:

* Calculating total revenue
* Finding bestselling books
* Measuring total books sold by genre
* Measuring total books sold by author
* Identifying frequently ordered books
* Calculating average book prices
* Finding top-selling categories

These analyses help businesses understand which products contribute most to sales.

---

### Inventory Analysis

Inventory management is another important aspect covered in the project.

SQL queries calculate:

* Remaining stock after customer purchases
* Total stock available
* Low-stock books requiring restocking

Inventory analysis helps avoid stock shortages and improve supply planning.

---

## Business Questions Solved

The project answers several real-world business questions.

Some examples include:

* Which books sell the most?
* Which genre generates maximum sales?
* Which author has sold the highest number of books?
* Who are the highest-paying customers?
* Which cities contribute the most revenue?
* How much revenue has the bookstore generated?
* Which books require restocking?
* What is the average price of books in each category?
* Which customers have placed multiple orders?
* Which books are most frequently purchased?

These queries demonstrate how SQL can transform raw data into actionable business insights.

---

## Project Workflow

The complete project follows a structured workflow.

1. Create the PostgreSQL database.
2. Design relational tables.
3. Define primary and foreign keys.
4. Import CSV datasets.
5. Verify imported records.
6. Write SQL queries.
7. Perform joins between tables.
8. Apply aggregate functions.
9. Generate business reports.
10. Analyze customer, inventory, and sales data.

This workflow closely resembles how SQL is used in real business environments.

---

## Skills Demonstrated

Through this project, several important SQL and database management skills are demonstrated, including:

* Relational Database Design
* Data Modeling
* Data Import
* Query Optimization
* Data Filtering
* Data Aggregation
* Multi-table Joins
* Business Reporting
* Sales Analytics
* Inventory Analysis
* Customer Analytics
* PostgreSQL Database Management

These are essential skills expected from aspiring Data Analysts, Business Analysts, and SQL Developers.

---

## Real-World Applications

The techniques used in this project can be applied in many industries beyond bookstores.

Examples include:

* E-commerce platforms
* Retail management systems
* Library management
* Inventory management
* Customer relationship management (CRM)
* Sales reporting systems
* Business intelligence dashboards

The same SQL concepts can analyze products, customers, transactions, and revenue across different domains.

---

## Learning Outcomes

By completing this project, I gained practical experience in designing relational databases and solving business problems using SQL. I learned how to organize structured data efficiently, establish relationships between multiple tables, import datasets from CSV files, and write SQL queries to retrieve meaningful information. The project improved my understanding of joins, aggregate functions, grouping, filtering, and business-oriented reporting. It also strengthened my ability to analyze sales performance, customer behavior, inventory levels, and revenue trends using PostgreSQL. Overall, this project provided hands-on experience with real-world database operations and enhanced my problem-solving skills through practical SQL-based business analysis.
