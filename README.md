# 📊 Regional Sales Bottleneck Analysis Dashboard

## 📌 Project Overview

This project analyzes regional sales performance to identify business bottlenecks, underperforming regions, revenue loss, and high-value opportunities using **SQL** and **Power BI**.

The analysis is based on a retail sales dataset containing **500+ sales transactions** across multiple regions, product categories, and sales agents.

---

## 🎯 Business Problem

A retail company is experiencing inconsistent sales performance across different regions. The objective is to identify:

- Underperforming regions
- Revenue loss due to cancelled and returned orders
- Best-performing sales agents
- Category-wise sales contribution
- Customer return patterns
- Monthly sales trends

---

## 🛠️ Tools & Technologies

- MySQL
- SQL
- Power BI
- CSV Dataset

---

## 📂 Dataset Information

**Dataset Name:** RegionalSales2025.csv

### Dataset Columns

| Column | Description |
|---------|-------------|
| OrderID | Unique Order ID |
| Date | Transaction Date |
| CustomerID | Customer Identifier |
| Region | Sales Region |
| ProductName | Product Name |
| Category | Product Category |
| Quantity | Quantity Sold |
| UnitPrice | Price Per Unit |
| TotalAmount | Total Sales Amount |
| OrderStatus | Completed / Cancelled / Returned |
| SalesAgent | Assigned Sales Agent |

---

# SQL Analysis

The following SQL analyses were performed:

### 1. Monthly Sales Trend
Analyzed monthly sales performance across all regions.

### 2. Cancelled & Returned Orders Percentage
Calculated cancellation and return percentages by region.

### 3. Revenue Loss Analysis
Identified the top regions with the highest revenue loss due to cancelled and returned orders.

### 4. Average Order Value
Calculated average order value for each product category.

### 5. Top 5 Sales Agents
Identified the highest-performing sales agents based on completed sales.

### 6. Category-wise Sales Contribution
Measured each category's contribution to total completed sales.

### 7. Customer Return Analysis
Listed customers with three or more returned orders.

---

# 📊 Dashboard Features

The Power BI dashboard includes:

- KPI Cards
  - Total Completed Sales
  - Total Cancelled Orders
  - Average Order Value
  - Most Returned Product
  - Total Orders

- Monthly Sales Trend (Line Chart)

- Order Status by Region (Stacked Column Chart)

- Sales Heatmap (Region vs Category)

- Top 5 Sales Agents

- Category-wise Sales Contribution (Donut Chart)

- Customers with Returned Orders Table

- Interactive Filters
  - Region
  - Category
  - Sales Agent

---

# 📈 Key Insights

- Identified regions with the highest cancellation and return rates.
- Analyzed monthly sales performance across all regions.
- Measured category contribution to overall revenue.
- Evaluated top-performing sales agents.
- Identified customers with frequent product returns.
- Highlighted revenue loss due to cancelled and returned orders.

---

# 📁 Project Structure

```
Regional-Sales-DashBoard/
│
├── .git/
├── Dashboard Image/
├── Data/
├── Images/
├── PoerBI Sales Dashboard/
├── sql code/
└── README.md
```

---

# 🚀 How to Run

1. Import the CSV dataset into MySQL.
2. Execute all SQL analysis queries.
3. Connect MySQL with Power BI.
4. Load the RegionalSales2025 table.
5. Build the dashboard using the provided visuals.
6. Explore insights using interactive filters.

---

# 💼 Skills Demonstrated

- SQL Query Writing
- Data Cleaning
- Data Aggregation
- Business Analysis
- KPI Development
- Dashboard Design
- Data Visualization
- Power BI
- MySQL
- Business Intelligence

---

## 👩‍💻 Author

**Riya Parmar**

GitHub:  
https://github.com/riyaa-parmar

⭐ If you find these projects useful, consider **starring the repository**!
