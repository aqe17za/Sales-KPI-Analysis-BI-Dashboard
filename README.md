# 📊 E-Commerce Sales KPI Dashboard

An end-to-end business intelligence (BI) project focused on analyzing sales performance of an e-commerce company using **SQL**, **Power BI**, and **Looker Studio**. The project tracks critical KPIs such as revenue trends, profit margins, category-wise performance, and monthly targets to assist stakeholders in data-driven decision-making.

---

## 🚀 Project Objectives

- To **analyze sales performance** across various product categories.
- To identify **top-selling products**, **high-performing categories**, and **profit-driving segments**.
- To monitor actual sales vs **target KPIs** for better business tracking.
- To **visualize insights** with intuitive dashboards using **Power BI** and **Looker Studio**.

---

## 🧰 Tools & Technologies Used

| Tool/Tech        | Purpose                                    |
|------------------|--------------------------------------------|
| **SQL**          | Data cleaning, joining datasets, KPI extraction |
| **Power BI**     | Building interactive dashboard             |
| **Looker Studio**| Web-based stakeholder dashboard            |
| **Alteryx (optional)** | RFM analysis and customer segmentation |
| **Excel**        | Initial data exploration and formatting    |

---

## 📂 Project Structure

├── SQL_Queries/ # SQL queries used for all analysis

├── PowerBI_Dashboard/ # .pbix file for Power BI dashboard

├── LookerStudio_Report/ # Link or assets from Looker Studio

├── Dataset/ # Raw input CSV files

└── README.md # Project documentation



---

## 📊 Dataset Overview

The dataset simulates the performance of an Indian e-commerce platform and contains the following CSVs:

1. **List of Orders**  
   - Fields: `Order ID`, `Customer ID`, `Purchase Date`, `City`, etc.
2. **Order Details**  
   - Fields: `Order ID`, `Product ID`, `Price`, `Quantity`, `Category`, `Sub-Category`, `Profit`
3. **Sales Target**  
   - Fields: `Target Month`, `Category`, `Target Revenue`

---

## 🔍 Data Analysis Summary

Using SQL, we:

- Merged order and product data to analyze complete transactions.
- Created KPIs:
  - **Total Revenue**
  - **Total Profit**
  - **Profit Margins**
  - **Monthly Sales Trend**
  - **Category & Subcategory-wise Performance**
- Joined with the **Sales Target** table to calculate:
  - Target achievement %
  - Gap between actuals and targets

---

## 📈 Dashboard Features

### 📌 Power BI Dashboard

- **Interactive filters**: Category, Month, Region
- **KPI Cards**: Revenue, Profit, Quantity Sold
- **Trends**: Monthly performance comparison
- **Category Insights**: Top-performing and low-performing segments

### 🌐 Looker Studio Report

- Designed for **executive-level presentation**
- Hosted on the web for quick access
- Responsive visuals with clear annotations

---

## 🧠 Key Insights

- Some sub-categories consistently underperform despite high sales—highlighting **low profit margins**.
- Certain product categories consistently **exceed targets**, making them candidates for expansion.
- Seasonal spikes observed in November and December, suggesting **holiday season campaigns** can be beneficial.

---



