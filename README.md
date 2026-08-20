# Walmart Sales Analytics: End-to-End Business Performance Study

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<YOUR_USERNAME>/walmart-sales-analytics/blob/main/walmart_sales_analytics.ipynb)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-Analysis-orange?logo=sqlite)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

An end-to-end exploratory data analysis and business intelligence project evaluating historical weekly sales performance across 45 Walmart retail locations (2010–2012). This project bridges **SQL data querying** and **Python analytics** to identify revenue drivers, evaluate seasonal demand spikes, and deliver commercial recommendations for inventory planning.

---

## 📌 Business Objective & Core Questions
The primary objective is to understand Walmart's sales patterns and identify key factors associated with revenue fluctuations to guide demand planning and store-level resource allocation.

The analysis investigates five central business questions:
1. **Store Performance:** Which stores generate the highest and lowest total revenue?
2. **Temporal Trends:** How do weekly sales fluctuate over time and across seasonal quarters?
3. **Holiday Impact:** What is the quantifiable revenue lift during major holiday weeks compared to non-holiday baseline weeks?
4. **Macro & Environmental Factors:** Are external variables (CPI, Unemployment, Temperature, Fuel Price) correlated with changes in sales?
5. **Sales Volatility:** Which stores exhibit the highest sales variance, and what drives their inconsistency?

---

## 🛠️ Tech Stack & Analytical Toolkit
* **Languages & Querying:** Python (`pandas`, `numpy`), SQL (`duckdb` / `sqlite3` in-notebook querying with CTEs, aggregations, and window functions)
* **Data Visualization:** `matplotlib`, `seaborn`
* **Environment:** Google Colab, Jupyter Notebook

---

## 🔄 Project Workflow
```text
Business Objective ➔ Data Ingestion ➔ Data Quality Audit & Cleaning ➔ Exploratory Data Analysis (EDA) 
➔ Hypothesis Definition ➔ Dual-Layer SQL & Python Deep Dive ➔ Visualizations ➔ Insights & Commercial Recommendations
