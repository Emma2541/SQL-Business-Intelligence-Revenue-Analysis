# E-Commerce SQL Analysis Project

## 📌 Overview

This project focuses on analyzing an e-commerce database using SQL to extract valuable business insights. It covers a wide range of real-world analytical questions related to customers, sales, products, and revenue performance.

## 🎯 Objectives

* Analyze customer behavior and purchasing patterns
* Evaluate product and category performance
* Track sales trends over time
* Build reusable database objects (views & procedures)
* Apply advanced SQL techniques for data analysis

## 🛠️ Technologies

* MySQL
* SQL (Advanced Queries, Window Functions, CTEs)

## 📊 Key Analysis Areas

### 👤 Customer Analysis

* Customers with more than 5 orders per year
* Customers with highest total spending
* Customers with repeat purchases
* Customers inactive in the last 6 months
* New customers acquired per month

### 📦 Product & Category Analysis

* Top 5 best-selling products
* Products with low stock
* Products never sold
* Revenue by product category
* Multi-category orders analysis

### 📈 Sales & Trend Analysis

* Monthly sales and growth rate
* Average order value per month
* Sales by day of the week
* Monthly revenue (quarter analysis)
* Highest order activity by day of month

### 🔍 Advanced SQL Features Used

* **JOINs** (INNER, LEFT)
* **GROUP BY & HAVING**
* **Window Functions** (`LAG`, `DATEDIFF`)
* **Common Table Expressions (CTEs)**
* **Subqueries**
* **Aggregations & Calculations**

## 🧩 Database Objects

### 📌 Views

* `CustomerSalesSummary` → Customer-level sales metrics
* `Customer_Payments` → Payment tracking per customer
* `Month_Sales` → Monthly aggregated sales

### ⚙️ Stored Procedures

* `Get_Customer_Orders_With_Summary`
  → Returns order history and total spending for a customer

* `Get_High_Product`
  → Identifies top-performing products based on sales and revenue

## 📁 Project Structure

```id="v3k2pl"
├── graduation project.sql
└── README.md
```

## 🚀 How to Use

1. Create the database:

```sql
CREATE DATABASE ECommerceDB;
USE ECommerceDB;
```

2. Run the SQL script:

```sql
SOURCE graduation project.sql;
```

3. Execute queries or call procedures:

```sql
CALL Get_Customer_Orders_With_Summary(1);
```

## 📊 Key Insights

* Identified high-value customers and repeat buyers
* Detected sales growth trends over time
* Highlighted top-performing products and categories
* Measured customer acquisition and retention
* Analyzed multi-category purchasing behavior

## 🚀 Conclusion

This project demonstrates strong SQL skills in data analysis, including advanced querying, performance insights, and database design. It reflects the ability to solve real business problems using structured data.

---
