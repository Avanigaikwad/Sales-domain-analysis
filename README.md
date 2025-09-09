# ☕ Coffee Shop Sales Analysis  

This project demonstrates how to analyze a **Coffee Shop Sales dataset** using **MySQL queries** and validate the results with a **Power BI visualization dashboard**.  

The goal is to:  
1. Import raw sales data into MySQL.  
2. Clean and transform data (fix schema, convert dates/times).  
3. Write SQL queries to calculate KPIs such as total sales, orders, and product performance.  
4. Cross-check query outputs with **Power BI visuals** to ensure accuracy and reliability.  

---
## 📂 Project Structure
```
coffee-shop-sales-analysis/
│── README.md                   # Project documentation  
│── coffee_shop_sales.sql       # All SQL queries for analysis  
│── schema.sql                  # Database schema & cleaning scripts  
│── data/                       # Sample dataset(s)  
│    └── coffee_shop_sales_sample.csv  
│── images/                     # Dashboard screenshots  
│    └── dashboard.png  
```

---

## 🗄️ Database Setup (MySQL)
1. Create the database:
   ```sql
   create database coffee_shop_sales_db;
   use coffee_shop_sales_db;
   ```
2. Import the dataset into MySQL.  
3. Run `schema.sql` to:  
   - Fix column names  
   - Convert `transaction_date` and `transaction_time` to proper data types  
   - Prepare table for analysis  

4. Run queries from `coffee_shop_sales.sql` for analysis and KPI calculation.  

---

## 📊 Analysis Performed
The following analyses are carried out in **MySQL** and validated against **Power BI visuals**:

### 🔹 Sales Trends
- Total sales by month  
- Difference & % increase between consecutive months  
- Daily sales with average line analysis  

### 🔹 Orders & Quantities
- Monthly orders and quantity sold  
- Difference & % increase in orders month-over-month  
- Daily order vs sales analysis  

### 🔹 Store Performance
- Sales by store location  
- Weekday vs weekend sales  

### 🔹 Product Insights
- Sales by product category  
- Top 10 products by revenue  

### 🔹 Hourly & Daily Patterns
- Sales by hour of the day  
- Sales by day of the week  
- Day-Hour heatmap analysis  

---
## 📈 Dashboard Preview (Power BI)
A Power BI dashboard was created on the same dataset, and its KPIs were **cross-checked with MySQL queries** to validate correctness.  

![Coffee Shop Sales Dashboard](images/dashboard.png)

---

## 🚀 Tools Used
- **MySQL** – Data cleaning, transformations, KPI calculation  
- **Power BI** – Interactive dashboard creation & reporting  
- **GitHub** – Project hosting & version control  

---

## 🔮 Future Scope
- Automate SQL-to-Power BI validation using Python  
- Add advanced KPIs (profit margin, customer segmentation)  
- Build more interactive Power BI dashboards with drill-through and bookmarks  

---

👉 This project highlights how **SQL analysis supports Power BI dashboards** by validating calculations and ensuring business reports are accurate.  
