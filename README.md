# 📊 Sales Performance Analysis & Excel Dashboard

An end-to-end **Sales Performance Analysis project** built using Microsoft Excel, based on a real-world business problem provided by a client.  
The project analyzes historical sales data (from 2014 onwards) to uncover insights related to **sales trends, profitability, customer contribution, and product performance**, and presents them through an interactive Excel dashboard.

---

## 📑 Table of Contents

- [Overview](#overview)
- [Business Context](#business-context)
- [Business Objectives](#business-objectives)
- [Dataset Overview](#dataset-overview)
- [Analytical Approach](#analytical-approach)
- [Project Structure](#project-structure)
- [Excel Workbook Structure](#excel-workbook-structure)
- [Dashboard Overview](#dashboard-overview)
- [Key Outcomes](#key-outcomes)
- [How to Use This Project](#how-to-use-this-project)
- [Author](#author)

---

## Overview

This project transforms raw sales data into **actionable business insights** using Excel-based analytics and visualization techniques.  
It demonstrates an end-to-end analytics workflow — from understanding the business problem to delivering insights through an interactive dashboard.

---

## Business Context

The dataset was provided by a client to evaluate the **sales and profitability performance** of a company operating across multiple product categories and sub-categories.

The data includes:
- Time-series sales data starting from **2014**
- Customer-level transaction data
- Product categories and sub-categories
- Sales and profit metrics

The goal is to support **strategic decision-making** related to product strategy, pricing, customer focus, and overall sales performance.

---

## Business Objectives

This analysis aims to answer the following key business questions:

- What is the **total sales** generated across all years?
- How have **sales changed year-over-year** since 2014?
- How has **profit evolved over time**, and are there noticeable growth or decline patterns?
- Which **customers contribute the most to overall profit**?
- Who are the **top customers based on profit contribution**?
- Which **product categories generate the highest sales**?
- What is the **sales difference between major product categories**?
- Which **sub-categories are the highest-selling** within each category?
- Are specific categories or sub-categories **driving the majority of revenue**?
- How does **customer purchasing behavior** impact profitability over time?

---

## Dataset Overview

- **Time Period:** 2014 onwards  
- **Granularity:** Transaction-level sales data  
- **Key Fields:**
  - Order Date
  - Customer Name
  - Category
  - Sub-Category
  - Sales
  - Profit
  - Region / State

The dataset is used strictly for **analytical and portfolio purposes**.

---

## Analytical Approach

The project follows a structured analytics workflow:

1. **Data Understanding & Cleaning**
   - Validation of raw data
   - Handling missing and inconsistent values
   - Standardizing date, category, and sub-category fields

2. **Data Transformation**
   - Creating analysis-ready data
   - Deriving time-based fields (Year, Month)

3. **Exploratory & Descriptive Analysis**
   - Sales and profit trend analysis
   - Category and sub-category performance comparison
   - Customer-level profitability analysis

4. **Visualization & Reporting**
   - Pivot tables and pivot charts
   - Interactive slicers (Year, Category)
   - Final Excel dashboard for stakeholder consumption

---

## Project Structure

```text
sales data/
├── data/
│   └── salesdata_.csv
├── dashboard/
│   └── sales_data_dashboard.xlsx
│
├── screenshots/
│   └── sales_dashboard_preview.png
│
├── docs/
│   └── sheet_structure.md
│
└── README.md
└── Business_Problem_Sales_Analysis.pdf

---

## 📘 Excel Workbook Structure


| Sheet           | Description                  |
| --------------- | ---------------------------- |
| salesdata       | Original dataset             |
| Cleaned_Data    | Cleaned and transformed data |
| ProfitGainedOverTime  |    Pivot table analysis
|  MonthlySales   | Pivot table analysis |
|  Top5Customers  | Pivot table analysis |
|  SalesByState   | Pivot table analysis |
|  CustomerCount  | Pivot table analysis |
|  SalesByCategory | Pivot table analysis |
| Dashboard       | Final interactive dashboard  |

---

## 🔍 Dashboard Overview

The Excel dashboard provides insights into:

- Sales by Category and Sub-Category
- Profit Trends Over Time
- Sales Performance by State
- Top Customers by Profit
- Customer Count Over Time
- Monthly Sales Trends
Interactive slicers allow filtering by Year and Category for deeper analysis.

---

## 📈 Key Outcomes

Insights from this project help the client to:
- Identify high-performing categories and sub-categories
- Recognize high-value customers driving profitability
- Understand sales and profit trends over time
- Detect seasonality and regional performance patterns
- Enable data-driven strategic decisions

---

## 🚀 How to Use This Project

1.Clone the repository:
git clone https://github.com/skartikeya-2811/sales-dashboard-excel.git

2. Open the Excel dashboard:
dashboard/sales_dashboard.xlsx

3. Use slicers to explore insights by:
- Year
- Category

---

## 👤 Author

Kartikeya Sharma
  

