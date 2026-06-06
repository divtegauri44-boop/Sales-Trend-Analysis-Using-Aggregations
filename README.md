# Task 6: Sales Trend Analysis Using Aggregations

## Objective

The objective of this task is to analyze sales trends by calculating monthly revenue and order volume using SQL aggregation functions. This analysis helps identify business performance trends over time and provides insights into sales patterns.

---

## Tools Used

* MySQL Workbench
* SQL
* Superstore Dataset

---

## Dataset Information

The Superstore dataset contains sales transaction records including order details, sales amount, profit, category, customer information, and regional data.

Key columns used in this analysis:

* Order ID
* Order Date
* Sales
* Category
* Sub-Category
* Region
* Profit

---

## SQL Concepts Used

* SELECT
* GROUP BY
* ORDER BY
* SUM()
* COUNT()
* COUNT(DISTINCT)
* Aggregate Functions
* Date Functions

## Analysis Performed

### 1. Monthly Revenue Analysis

Calculated total sales revenue for each month using the SUM() function and grouped the data by year and month.

### 2. Monthly Order Volume Analysis

Calculated the total number of unique orders placed each month using COUNT(DISTINCT Order ID).

### 3. Revenue and Order Volume Analysis

Combined monthly revenue and order volume into a single report for better trend analysis.

### 4. Top 3 Months by Sales

Identified the top-performing months based on total sales revenue.

### 5. Aggregate Functions Analysis

Applied aggregate functions such as:

* SUM()
* AVG()
* MAX()
* MIN()
* COUNT()

---

## Key Findings

* Monthly sales revenue varied significantly across different months.
* Certain months generated higher revenue and order volume compared to others.
* A small number of months contributed a large percentage of total sales.
* Some product categories generated significantly more revenue than others.
* Regional performance differed, indicating opportunities for targeted business strategies.

---

## Business Insights

* High-performing months can be used as benchmarks for future sales planning.
* Product categories with strong sales should receive additional marketing focus.
* Low-performing regions may require targeted promotional campaigns.
* Monitoring monthly order volume helps forecast future demand and inventory requirements.

---

## Conclusion

This project demonstrates how SQL aggregation functions can be used to analyze sales trends and business performance. By grouping data by month and year, calculating revenue, and measuring order volume, valuable business insights can be generated to support data-driven decision-making.

---

## Files Included

* superstore.csv
* README.md
* Screenshots Folder

---



Gauri Divte
Data Analyst Internship Task 6
