# Pizza-Sales-Sql-Analysis-and-Power-BI-Dashboard
Pizza Sales SQL Analysis is a collection of SQL queries designed to analyze pizza sales data. The queries cover key performance indicators (KPIs), sales trends, and product performance metrics. This project is useful for anyone learning SQL, practicing data analysis, or building dashboards in tools like Power BI or Tableau.
# 🍕 Pizza Sales SQL Analysis

This repository contains SQL queries to analyze pizza sales data.  
It includes KPIs, trends, and top/bottom pizza performance metrics.

## 📊 Key Features
- Total Revenue, Average Order Value
- Daily & Monthly Order Trends
- Sales % by Category & Size
- Top/Bottom 5 Pizzas by Revenue, Quantity, Orders

## 📂 Files
- `queries/pizza_sales_queries.sql` → All SQL queries
- `docs/PIZZA_SALES_SQL_QUERIES.docx` → Original document

## ▶️ Usage
Run queries on your database:
```sql
SELECT SUM(total_price) AS Total_Revenue FROM pizza_sales;
