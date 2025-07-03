# 🚗 Vehicle Sales Analysis Dashboard (Power BI)

This repository contains a Power BI dashboard built to explore and visualize global vehicle sales performance. The goal of this project was to identify patterns in sales quantity, revenue, product performance, and geographic trends using clean, interactive visuals.

---

## 📁 Dataset Overview

The dataset includes the following columns:
- `Product Name`
- `Order Number`
- `Order Line Item` (if applicable)
- `Date` and `Year`
- `Quantity`
- `Price Each`
- `Total` (Price Each × Quantity)
- `Country`
- `Order Status` (e.g., Shipped, Cancelled)
- `Deal Size` (Small, Medium, Large)

---

## 🧰 Tools & Techniques Used

- Power BI Desktop
- Power Query for data cleaning and shaping
- DAX calculated column: `Total = Price Each × Quantity`
- Visual hierarchy and interactivity with slicers and Q&A
- Multi-page layout with KPI cards, maps, bar charts, and pie charts
- GitHub Pages for live project hosting

---

## 📊 Dashboard Pages

### 📄 Page 1: **Sales Overview**
- KPIs: Total Revenue, Orders, Vehicles Sold, Countries
- Pie Chart: Deal Size Distribution
- Map: Sales by Country
- Line Chart: Revenue Over Time
- Slicers: Year, Country

### 📄 Page 2: **Product & Order Analysis**
- Bar Charts: Top-Selling Vehicles, Revenue by Product
- Stacked Bar: Deal Size per Product
- Bar Chart: Top Countries by Quantity
- Filters: Product Line, Deal Size, Order Status
- Q&A Box for natural language queries

---

## 💡 Key Insights

- Classic Cars generated the most revenue
- USA led in total vehicle quantity ordered
- Medium-sized deals made up the largest share
- Sales peaked in 2004
- Deal sizes and order statuses vary widely across product lines

---

## 📂 Repository Contents

| File Name            | Description                              |
|----------------------|------------------------------------------|
| `vehicle_sales.pbix` | Power BI file with full dashboard         |
| `vehicle_sales.csv`  | Cleaned data file (optional)              |
| `dashboard.png`      | Screenshot of the final dashboard         |
| `README.md`          | This documentation file                   |

---




