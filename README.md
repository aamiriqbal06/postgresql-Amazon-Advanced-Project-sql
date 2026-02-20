# 🛒 Amazon USA Sales Analysis using PostgreSQL

---

##  Project Overview

This project simulates real-world e-commerce analytics using a structured Amazon-like transactional dataset containing **20,000+ sales records**.

The objective was to analyze customer behavior, product performance, seller efficiency, logistics delays, and revenue trends using advanced PostgreSQL queries.

This project reflects how SQL is used in production environments to support business decision-making in retail and e-commerce operations.

---

##  Key Business Insights

- Top 10 products contributed a significant percentage of total platform revenue.
- High-margin categories generated the strongest profit performance.
- A measurable percentage of orders experienced shipping delays (> 3 days).
- Repeat customers generated a large share of total revenue (strong CLTV impact).
- Certain sellers showed higher cancellation and return ratios.
- Year-over-Year analysis identified products with declining revenue performance.

---

## 🏗 Database Design

The database was designed using a normalized relational schema including:

- **Customers**
- **Orders**
- **Order Items**
- **Products**
- **Categories**
- **Sellers**
- **Payments**
- **Shipping**
- **Inventory**

An **ERD diagram** is included in the repository to visualize relationships and foreign key dependencies.

---
![erd](https://github.com/aamiriqbal06/postgresql-Amazon-Advanced-Project-sql/blob/main/erd.png)

---

![TABLE_OVERVIEW](https://github.com/aamiriqbal06/postgresql-Amazon-Advanced-Project-sql/blob/main/Amazon_Schema.jpg)

---
## 🧠 SQL Concepts & Techniques Used

- Complex **JOIN** operations (INNER, LEFT)
- **Common Table Expressions (CTE)**
- **Window Functions** (LAG, DENSE_RANK, RANK)
- Aggregations & Conditional Aggregation
- Subqueries
- Date & Time Functions
- Profit Margin Calculation
- Customer Segmentation
- Year-over-Year Revenue Analysis
- Inventory Threshold Detection

---

## 🔍 Highlighted Analytical Problems Solved

### 1️⃣ Customer Lifetime Value (CLTV)
Ranked customers based on total lifetime purchase value using window functions.

### 2️⃣ Monthly Sales Trend Analysis
Used `LAG()` to compare current month revenue with previous month performance.

### 3️⃣ Shipping Delay Detection
Identified orders shipped more than 3 days after order date to monitor operational inefficiencies.

### 4️⃣ Profit Margin Ranking
Calculated product-level profit margins using COGS and total sales.

### 5️⃣ Revenue Contribution by Category
Determined percentage contribution of each product category to total revenue.

---

## 📦 Operational Analysis Performed

- High return-rate products identification  
- Inactive sellers (no sales in last 6 months)  
- Payment success rate breakdown  
- Inventory stock alerts (low-stock threshold detection)  
- Revenue handled by shipping providers  
- Year-over-Year revenue decline comparison  

---

## 📈 Business Impact Simulation

This project demonstrates how SQL can be used to:

- Monitor revenue performance
- Improve customer retention analysis
- Optimize inventory management
- Detect operational bottlenecks
- Support data-driven decision-making in e-commerce platforms

---

## 🛠 Tools Used

- PostgreSQL  
- SQL  
- Relational Database Design  

---

## 👤 Author

**Aamir Iqbal**  
Aspiring Data Analyst | SQL | PostgreSQL  

---

⭐ If you found this project interesting, feel free to connect or provide feedback!
