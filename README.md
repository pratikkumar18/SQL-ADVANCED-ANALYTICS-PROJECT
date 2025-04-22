
# 🧠 Advanced SQL Analytics Project – End-to-End Business Insight using Data Analytics Roadmap

## 📌 Overview

This project simulates a **real-world data analytics pipeline using SQL**, built upon a structured roadmap that covers both **Exploratory Data Analysis (EDA)** and **Advanced Analytics**. The goal is to uncover **actionable insights from structured retail and customer data** using only SQL, without any BI tools — showcasing strong business logic and technical command.

---

## 📊 Dataset Summary

The dataset is a relational model simulating data from a mid-sized retail company. It contains:

- `Customers`: customer information, location, income, tenure  
- `Orders`: purchase records with date, product ID, quantity, discount, and profit  
- `Products`: category, subcategory, and pricing  
- `Returns`: returned items  
- `Region`: mapping of customer location to state or region

---

## 🔍 Exploratory Data Analysis (EDA)

Following the EDA phase of the roadmap:

### 1. **Database Exploration**
- Mapped all foreign-key relationships
- Used `JOINs` to combine orders, products, and customer tables

### 2. **Dimension Exploration**
- Analyzed customer behavior by region, category, gender, and tenure band
- Used `GROUP BY`, `DISTINCT`, and filtering logic

### 3. **Date Exploration**
- Extracted monthly and quarterly insights using `DATE_TRUNC`, `MONTH()`, `YEAR()`
- Calculated customer tenure using `DATEDIFF`

### 4. **Measures Exploration**
- Aggregated KPIs like `Total Sales`, `Total Profit`, `Average Discount`
- Applied `SUM`, `AVG`, `MAX`, `COUNT`

### 5. **Magnitude**
- Identified top-selling and low-performing product categories
- Highlighted categories with high returns and low profit margins

### 6. **Ranking**
- Used `RANK()` and `ROW_NUMBER()` to identify:
  - Top 10 customers by sales
  - Bottom 10 products by profit
  - Most returned categories

---

## 📈 Advanced Analytics (Business-Driven SQL)

Following the Advanced Analytics section of the roadmap:

### 7. **Change-Over-Time (Trend Analysis)**
- Created a time-series sales trend using monthly and quarterly breakdowns  
- Compared year-over-year performance by product category

### 8. **Cumulative Analysis**
- Built running totals using `SUM() OVER(ORDER BY date)`  
- Analyzed customer cumulative purchase behavior

### 9. **Performance Analysis**
- Segmented product performance by profit, discount, and sales volume  
- Analyzed sales effectiveness by customer region and marketing segment

### 10. **Part-to-Whole**
- Used proportional analysis to show:
  - % contribution of each product category to total revenue  
  - % of returned orders in each segment

### 11. **Data Segmentation**
- Created customer bands based on total purchase value:
  - High Value, Moderate, Low  
- Applied `CASE` statements for dynamic segmentation

### 12. **Reporting Output**
- Designed final queries to be easily exported into dashboards or Excel  
- Generated clean SQL views for team reporting needs

---

## 🏁 Project Deliverables

- ✅ Fully annotated SQL script file (`advanced_sql_project.sql`)  
- ✅ Sample outputs in CSV and Excel format  
- ✅ Project walkthrough PDF with query summaries and visual roadmap alignment  
- ✅ Optional GitHub repo with `.sql` files + screenshots

---

## 💡 Key Learnings

- Combined exploratory and advanced analytics to simulate a complete data-to-insight lifecycle  
- Practiced clean, reusable SQL patterns for segmentation, trend analysis, and KPI reporting  
- Understood how structured logic directly translates to business impact and reporting quality

---

