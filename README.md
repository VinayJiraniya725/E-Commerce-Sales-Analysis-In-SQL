# 📊 E-Commerce Sales Analysis (SQL + Power BI)

An end-to-end data analysis project on an e-commerce sales dataset — using **MySQL** to extract business insights through SQL queries, and **Power BI** to visualize them in an interactive dashboard.

---

## 📌 Project Overview

This project analyzes e-commerce sales data to answer key business questions around **revenue, customers, products, cities, and time trends**. It moves from basic exploration to advanced SQL (window functions, subqueries) and finishes with a Power BI dashboard summarizing all findings.

---

## 🗂️ Dataset

The dataset contains e-commerce order-level records with fields such as:

`order_id`, `order_date`, `customer_name`, `city`, `category`, `product`, `quantity`, `sales`

---

## 🛠️ Tools & Skills Used

- **MySQL** — data querying and analysis
- **SQL Concepts:** Aggregations (SUM, AVG, COUNT), GROUP BY / HAVING, Subqueries, Window Functions (`DENSE_RANK()`, `ROW_NUMBER()`), CASE statements
- **Power BI** — dashboard design and data visualization

---

## 🔍 Analysis Performed

1. **Core Sales Metrics** — Total Sales, Total Orders, Average Order Value (AOV)
2. **Category-Level Analysis** — Revenue, order count, and quantity by category; % contribution to total sales
3. **City-Level Analysis** — Revenue and orders by city; top cities; top customers and top category per city
4. **Product-Level Analysis** — Top/bottom products by revenue and quantity; top products per category
5. **Customer-Level Analysis** — Top customers by spend and orders; customer segmentation (**One-Time / Regular / Frequent**)
6. **Time-Based Trends** — Monthly revenue, order volume, and AOV trends
7. **Advanced Analysis** — Window-function-based rankings (top N per group), highest single-order value per customer

📄 Full SQL script: [`E-Commerce_Sales_Analysis.sql`]https://github.com/VinayJiraniya725/E-Commerce-Sales-Analysis-In-SQL/blob/main/E-Commerce%20Sales%20Analysis.sql

---

## 📈 Power BI Dashboard

An interactive dashboard built on the analysis results.

![Dashboard]https://github.com/VinayJiraniya725/E-Commerce-Sales-Analysis-In-SQL/blob/main/E-Commerce%20Sales%20Dashboard.png

**Includes:**
- KPI cards — Total Orders, Total Quantity, Total Revenue, Total Profit, Total Discount
- Sales Target Achievement gauge
- Top Products by Sales
- Sales by City, Category, and Profit by Category
- Monthly Sales Trend
- Sales by Payment Mode
- Filters: City, Month, Category, Payment Mode

---

## 💡 Key Insights

- A small set of cities and categories drive a disproportionate share of total revenue.
- Electronics and Furniture are the top-performing categories by revenue.
- Sales show clear monthly seasonality with identifiable peak and low months.
- A core group of "Frequent" customers contributes significantly more than one-time buyers.

---

## 📁 Repository Contents

| File | Description |
|---|---|
| https://github.com/VinayJiraniya725/E-Commerce-Sales-Analysis-In-SQL/blob/main/E-Commerce%20Sales%20Analysis.sql | Full set of SQL queries used for analysis |
| https://github.com/VinayJiraniya725/E-Commerce-Sales-Analysis-In-SQL/blob/main/E-Commerce%20Sales%20Dashboard.png | Power BI dashboard screenshot |
| https://github.com/VinayJiraniya725/E-Commerce-Sales-Analysis-In-SQL/blob/main/E-Commerce%20Sales%20Analysis%20Changelog.docx | Version-wise log of analysis stages |


- **GitHub:** https://github.com/VinayJiraniya725
- **LinkedIn:** https://www.linkedin.com/in/vinay-kumar-a304b931a/
