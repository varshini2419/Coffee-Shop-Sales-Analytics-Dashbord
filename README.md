# Coffee-Shop-Sales-Analytics-Dashbord

# ☕ Coffee Shop Sales Analytics Dashboard

## 📖 Project Description

The Coffee Shop Sales Analytics Dashboard is an interactive Business Intelligence (BI) solution built using Microsoft Power BI to analyze and visualize coffee shop sales performance. This dashboard transforms raw transaction data into meaningful insights, helping businesses understand sales trends, customer purchasing behavior, product performance, and store-level performance.

The project focuses on delivering actionable insights through interactive visualizations, KPI tracking, and data-driven reporting. Users can explore sales performance across different months, product categories, store locations, and weekday/weekend periods using dynamic filters and slicers.

This dashboard demonstrates practical skills in data cleaning, data modeling, DAX calculations, dashboard design, and business analytics, making it an excellent portfolio project for aspiring Data Analysts and Business Intelligence professionals.

---

## 🎯 Objectives

- Analyze overall sales performance.
- Monitor total orders and quantity sold.
- Identify monthly sales trends.
- Compare weekday and weekend sales.
- Evaluate store-wise sales performance.
- Analyze product and category performance.
- Build an interactive dashboard for business decision-making.

---

## 📊 Dashboard Features

### Dashboard 1: Sales Overview

- Total Sales KPI
- Total Orders KPI
- Quantity Sold KPI
- Monthly Sales Trend Analysis
- Weekday vs Weekend Sales Analysis

### Dashboard 2: Product & Store Analysis

- Sales by Store Location
- Orders by Store Location
- Top Products by Sales
- Product Category Performance
- Interactive Slicers and Filters

---

## 🛠️ Technologies Used

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel

---

## 📂 Dataset Information

The dataset contains coffee shop transaction records, including:

- Transaction ID
- Transaction Date
- Store Location
- Product Category
- Product Details
- Quantity Sold
- Unit Price
- Sales Amount

---

## 📈 Key Performance Indicators (KPIs)

### Total Sales
Measures the overall revenue generated from all transactions.

### Total Orders
Tracks the total number of customer transactions.

### Quantity Sold
Measures the total number of products sold.

### Monthly Sales Trend
Analyzes revenue performance across different months.

### Store Performance
Compares sales across various store locations.

### Product Performance
Identifies best-selling products and categories.

---

## 🧮 DAX Measures

### Total Sales

```DAX
Total Sales =
SUMX(
    coffee_shop_sales,
    coffee_shop_sales[transaction_qty] *
    coffee_shop_sales[unit_price]
)
```

### Total Orders

```DAX
Total Orders =
DISTINCTCOUNT(coffee_shop_sales[transaction_id])
```

### Quantity Sold

```DAX
Quantity Sold =
SUM(coffee_shop_sales[transaction_qty])
```

---

## 📌 Key Insights

- Identified top-performing months based on sales revenue.
- Compared weekday and weekend purchasing behavior.
- Determined the best-performing store locations.
- Analyzed top-selling products and categories.
- Monitored order distribution across multiple stores.

---

## 💼 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Dashboard Development
- Data Visualization
- Business Analytics
- KPI Reporting
- Business Intelligence
- Data Storytelling

---

## 🚀 Project Outcomes

This project helped strengthen practical knowledge in Power BI by applying real-world business analytics techniques. The dashboard enables stakeholders to quickly monitor performance, identify trends, and make informed business decisions using data-driven insights.

---

## 👨‍💻 Author

**Varshini M**

B.Tech (CSIT) | Aspiring Data Analyst

### Skills
- Power BI
- SQL
- Excel
- Data Visualization
- React.js
- Node.js
- Business Analytics

### GitHub
Add Your GitHub Profile Link

### LinkedIn
Add Your LinkedIn Profile Link

---

⭐ If you found this project useful, feel free to star the repository and connect with me on LinkedIn.
