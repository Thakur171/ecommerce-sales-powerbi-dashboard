# 📊 E-Commerce Sales Analysis Dashboard (Power BI)

## 📌 Project Overview

This project presents an interactive Power BI dashboard built to analyze e-commerce sales data. It provides insights into revenue trends, customer behavior, product performance, and regional sales distribution to support data-driven business decisions.

---

## 📂 Dataset

The dataset consists of three main tables:

* **Customers** – customer details such as location and demographics
* **Orders** – transaction-level data including order date, quantity, and delivery status
* **Products** – product information including category, price, and ratings

---

## 🧠 Data Model

* A **star schema** is implemented for efficient data analysis
* **Orders** acts as the fact table
* Connected with:

  * Customers (via CustomerID)
  * Products (via ProductID)

---

## 📊 Key KPIs

* **Total Revenue:** ₹1.25 Billion
* **Average Order Value (AOV):** ₹112.8K
* **Total Orders:** 15.7K
* **Cancellation Rate:** 29.72%
* **Revenue Lost due to Cancellation:** ₹525.4 Million

---

## 📈 Dashboard Features

* Revenue analysis by **product, category, and state**
* Time-based analysis using **year and quarter trends**
* Interactive filters for **category and purchase date**
* KPI cards for quick business understanding

---

## 🔍 Key Insights

* **Laptop and Mobile categories** generate the highest revenue
* **Maharashtra and Gujarat** are top-performing states
* Revenue shows a decline in later quarters of 2024
* High cancellation rate significantly impacts total revenue

---

## 💡 Business Recommendations

The following recommendations are derived from the insights observed in the dashboard:

* Focus on high-performing categories like **Laptops and Mobiles** to maximize revenue
* Reduce the **cancellation rate (29.72%)** by improving delivery efficiency and order management
* Invest more in high-performing regions such as **Maharashtra and Gujarat**
* Improve sales in low-performing states through targeted promotions and offers
* Optimize inventory for top-selling products to prevent stock shortages
* Identify root causes of cancellations to minimize revenue loss (₹525.4M)

---

## 🛠 Tools & Technologies Used

* Power BI
* Data Modeling
* DAX (Data Analysis Expressions)
* Data Visualization

---

## 📷 Dashboard Preview

![Dashboard](dashboard-overview,png)

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository
2. Open it using Power BI Desktop
3. Explore the interactive dashboard using filters and visuals

---

## 📌 Author

**Harsh Thakur**
