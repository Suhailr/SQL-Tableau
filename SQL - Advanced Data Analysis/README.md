# 📊 SQL Data Analysis Portfolio Project
## 🧾 Overview

This project is a real-world SQL data analytics simulation inspired by industry-style reporting workflows. It demonstrates how raw sales data can be transformed into actionable business insights using SQL.

The project covers multiple analytical dimensions such as time trends, performance tracking, segmentation, and contribution analysis.

## 🎯 Objectives

This project demonstrates how to:

- Analyze business performance over time 📈
- Build cumulative and trend-based metrics 📊
- Evaluate product and customer performance 🚀
- Perform segmentation and part-to-whole analysis 🧩
- Create reusable SQL reporting views for BI dashboards 📋

## 🧱 Data Model

The project follows a star-schema-like structure:

### 📌 Fact Table
- gold.fact_sales → transactional sales data
### 📌 Dimension Tables
- gold.report_customers → customer attributes
- gold.report_products → product attributes

## 📂 Files

### `scripts/` — SQL Analysis & Reporting Scripts

| File                                  | Description                                        |
|---------------------------------------|----------------------------------------------------|
| `00_init_database.sql`               | Initializes database schema and tables             |
| `01_changes_over_time_analysis_month.sql` | Analyzes sales trends on a monthly basis     |
| `02_changes_over_time_analysis_year.sql`  | Analyzes sales trends on a yearly basis      |
| `03_cumulative_analysis.sql`         | Calculates cumulative metrics over time            |
| `04_performance_analysis.sql`        | Evaluates sales performance across dimensions      |
| `05_part_to_whole_analysis.sql`      | Analyzes sales contribution by segments            |
| `06_data_segmentation_cost.sql`      | Segments data based on cost-related criteria       |
| `07_data_segmentation_customer.sql`  | Segments data by customer characteristics          |
| `08_customer_report.sql`             | Constructs customer report logic                   |
| `09_report_customers_view.sql`       | Creates a view for the customer report             |
| `10_product_report.sql`              | Constructs and saves the product report as a view  |

### `dataset/` — Source Data Tables

| File                          | Description                                |
|-------------------------------|--------------------------------------------|
| `gold.fact_sales.csv`         | Fact table containing transactional sales data |
| `gold.report_customers.csv`   | Dimension table for customer information |
| `gold.report_products.csv`    | Dimension table for product information  |


  
## 🛠️ SQL Techniques Used
🟢 Basic SQL 
- SELECT, FROM, WHERE 
- GROUP BY, ORDER BY 
🟡 Intermediate SQL 
- JOIN operations 
- CASE WHEN logic 
- Aggregations 
🔴 Advanced SQL 
- Window Functions (OVER, PARTITION BY) 
- Common Table Expressions (CTEs) 
- Subqueries 
- Running totals & ranking logic 

The project produces two main analytical reporting views:

### 👤 Customer Report
- Customer-level revenue analysis
- Behavior segmentation
- Contribution insights
### 📦 Product Report
- Product performance tracking
- Revenue contribution
- Sales trends per product
  
## ⚙️ Tech Stack
SQL (PostgreSQL / MySQL compatible) <br>
Window Functions <br>
CTEs (Common Table Expressions) <br>
Data Modeling (Star Schema) <br>
Analytical SQL Techniques

## 💡 Key Learning Outcomes

By working on this project, you will learn:

How real-world SQL reporting systems are built <br>
How to structure analytical datasets for BI tools <br>
How to write scalable and reusable SQL queries <br>
How to derive business insights from raw transactional data <br>

## 📌 Project Inspiration

This project is inspired by the YouTube tutorial: SQL Data Analyst Portfolio Project 

## 🧑‍💻 Author
Mohamed Suhal Mohamad Haniff | Data Analytics Enthusiast















