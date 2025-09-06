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
