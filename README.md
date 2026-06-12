# 📊 Fashion Retail Sales Analysis Dashboard

## 📷 Dashboard Preview

![Fashion Retail Sales Dashboard](dashboard.png)

## 📌 Project Overview

This project analyzes fashion retail transactions using **Microsoft Excel** to uncover valuable business insights related to sales performance, product demand, customer satisfaction, and payment preferences. The objective was to transform raw retail transaction data into an interactive and visually appealing dashboard that supports data-driven decision-making.

---

## 📂 Dataset Information

- **Dataset Name:** Fashion Retail Sales Dataset
- **Source:** Kaggle
- **Total Records:** 3,400+
- **Cleaned Records:** 2,750
- **Number of Columns:** 6

### Dataset Fields

- Customer ID
- Item Purchased
- Purchase Amount (USD)
- Date Purchase
- Review Rating
- Payment Method

---

# 🔄 ETL & Data Cleaning Process

## Data Cleaning

- Checked for duplicate records.
- Identified missing values using `COUNTBLANK()`.
- Found **650 missing Purchase Amount records (19.1%)**.
- Removed transactions with missing Purchase Amount values.
- Found **324 missing Review Ratings (9.5%)**.
- Replaced missing ratings with **"Not Rated"**.
- Verified no missing values in Customer ID, Item Purchased, Date Purchase, and Payment Method.
- Standardized date formats.
- Created a Month field for trend analysis.
- Validated data consistency across all columns.

---

## Missing Value Analysis

| Column | Null Values |
|----------|------------:|
| Customer ID | 0 |
| Item Purchased | 0 |
| Purchase Amount | 650 |
| Date Purchase | 0 |
| Review Rating | 324 |
| Payment Method | 0 |

---

# 📈 Key Performance Indicators (KPIs)

| KPI | Value |
|------|------:|
| Total Revenue | $431K |
| Total Orders | 2,750 |
| Average Order Value | $157 |
| Average Rating | 3.0 / 5 |

---

# 📊 Dashboard Components

### KPI Cards
- Total Revenue
- Total Orders
- Average Order Value
- Average Customer Rating

### Interactive Filters
- Payment Method
- Purchase Month
- Item Purchased

### Visualizations
- Monthly Sales Trend
- Top 10 Products by Revenue
- Payment Method Distribution

---

# 🔍 Executive Summary

- **Total Revenue Generated:** $431K
- **Total Orders Processed:** 2,750
- **Average Order Value:** $157
- **Average Customer Rating:** 3.0 / 5

The dashboard highlights key retail performance metrics and provides insights into customer purchasing behavior, product performance, and payment preferences.

---

# 📈 Key Insights

## 💰 Sales Performance

- Total revenue generated was **$430,952**.
- Average customer spending per transaction was **$156.71**.
- Revenue remained relatively stable throughout the year.

---

## 📅 Monthly Sales Trends

- **December** recorded the highest monthly revenue (**~$47K**).
- **September** recorded the lowest monthly revenue (**~$24K**).
- Revenue showed strong recovery during **Q4**.

---

## 🛍 Product Performance

- **Tunic** generated the highest revenue (**~$17.3K**).
- **Jeans** and **Pajamas** were among the top-performing products.
- Revenue was distributed across multiple product categories, indicating diversified customer demand.
- No single product category dominated total sales.

---

## 💳 Payment Analysis

- **Credit Card** transactions accounted for approximately **52%** of total purchases.
- **Cash** transactions accounted for approximately **48%** of total purchases.
- Customers showed a nearly equal preference for both payment methods.

---

# 🛠 Tools & Techniques Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting
- Data Cleaning
- ETL Process
- Dashboard Design
- Data Visualization

---

# 📁 Workbook Structure

The Excel workbook contains four worksheets:

### 1. Raw_Data
- Original dataset imported from Kaggle.

### 2. Cleaned_Data
- Data cleaning and transformation.
- Missing value handling.
- Date formatting.

### 3. Pivot_Tables
- KPI calculations.
- Revenue analysis.
- Product performance analysis.

### 4. Dashboard
- Interactive Excel dashboard.
- KPI cards.
- Pivot charts.
- Slicers and filters.

---

# 🎯 Business Value

This dashboard enables stakeholders to:

- Monitor overall sales performance.
- Track monthly revenue trends.
- Identify top-performing products.
- Understand customer payment preferences.
- Evaluate customer satisfaction levels.
- Support data-driven business decisions.

---

# ✅ Conclusion

The Fashion Retail Sales Analysis Dashboard provides a comprehensive overview of retail performance by tracking revenue, transaction volume, product demand, customer satisfaction, and payment behavior.

Through effective data cleaning, transformation, analysis, and visualization, the project demonstrates how Microsoft Excel can be leveraged to convert raw transactional data into actionable business insights.

This project showcases core Data Analyst skills including:

- Data Cleaning
- ETL
- Data Analysis
- KPI Reporting
- Dashboard Development
- Business Intelligence
- Data Visualization

---

## 👨‍💻 Author

**Yash Prajapati**

Aspiring Data Analyst | Excel | SQL | Data Visualization | Business Intelligence

---
⭐ If you found this project useful, feel free to star the repository.
