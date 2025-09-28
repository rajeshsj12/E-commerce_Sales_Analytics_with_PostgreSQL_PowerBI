# 🛒 E-commerce Sales Analytics (PostgreSQL + Power BI)

## 📌 Project Overview

This project demonstrates a complete **end-to-end Business Intelligence pipeline** for an E-commerce company.

It simulates **customer, product, inventory, and order data** using Python, stores it in **PostgreSQL**, and builds interactive **Power BI dashboards** for insights into:

* Daily & monthly **sales trends**
* **Top-selling products** by sales & quantity
* **Customer purchase behavior** by region, gender, and age
* **Inventory alerts** for low-stock products

---

## ⚙️ Tech Stack

* **PostgreSQL** → Database (schema, constraints, queries)
* **Power BI** → Visualization & Dashboarding
* **Jupyter Notebook** → Development & Execution Environment and Load CSV data into SQL

---


## 🗂️ Database Schema (ERD)

The database follows a **star-schema style** with 4 core tables:

![alt text](ERD.png)




## 🚀 Workflow

2️⃣ **Database Schema** (PostgreSQL)

* Define tables with **primary keys, foreign keys, and constraints**
* Import generated CSVs using `\copy` command
* Validate data with SQL queries

3️⃣ **Business Intelligence** (Power BI)

* Connect Power BI → PostgreSQL
* Build reports & dashboards

---

## 📊 Dashboards (Power BI)

The dashboard provides insights such as:

* **Sales Trends** → Yearly, Monthly
* **Top Products** → By sales revenue & quantity
* **Inventory Alerts** → Products with stock < 200
* **Customer Insights** → By region, gender, and age category
* **Key KPIs**:

  * 📈 Total Sales: **1.79M**
  * 📦 Total Quantity: **7276**
  * 👥 Customers: **500**

📌 Full Dashboard: [E-Commerce Sales Dashboard.pdf](./E-Commerce%20Sales%20Dashboard.pdf)

---

## 📈 Results & Insights

* Sales peaked during **festive months (Nov–Dec)**
* **Home & Electronics** categories contributed the highest revenue
* **South & West regions** showed stronger sales performance
* Majority of purchases made by customers aged **26–45**
* Inventory alerts identified **10+ products** running low on stock

---

## 🎯 Future Enhancements

* Extend dashboard with **profitability & marketing analysis**
* Deploy dashboards to **Power BI Service** for collaboration