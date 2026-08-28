# Retail Sales Analytics, SQL & Statistical Decision-Making

## 📌 Project Overview
This project presents an end-to-end data analytics workflow on retail and customer transactional data. It covers messy data wrangling, relational SQL extraction, regional revenue insights, and inferential hypothesis testing to evaluate performance impact.

---

## 🛠️ Tech Stack & Skills
- **Languages & Databases:** Python, SQL (SQLite).
- **Libraries:** Pandas, NumPy, SciPy (stats), Matplotlib, Seaborn.
- **Core Concepts:** Data Cleaning & Text Standardization, Outlier Detection (1.5x IQR), SQL Joins & Aggregations, Hypothesis Testing (Two-sample Welch's t-test, P-value Interpretation, Cohen's d Effect Size).

---

## 📂 Project Structure
- `01_orders_data_cleaning.ipynb`: String normalization, missing values handling, data type corrections, and duplicate removal.
- `02_sales_merging_and_outliers.ipynb`: Merging sales transactions, pivot table summarization, and IQR-based bulk order outlier analysis.
- `03_sql_and_hypothesis_testing.ipynb`: Relational SQL revenue queries and inferential statistical testing (Welch's t-test).

---

## 🔍 Key Findings & Insights
1. **Data Cleaning & Standardization:** Cleaned messy order inputs, standardized city representations down from 10 variations to 3 distinct categories, and handled invalid ratings.
2. **Regional Sales Performance:** Identified top revenue drivers via relational SQL queries, highlighting central regional sales dominance.
3. **Outlier Management:** Detected order outliers via IQR bounds and preserved valid bulk orders to maintain analytical integrity.
4. **Statistical Hypothesis Testing:**
   - Two-sample Welch's t-test confirmed a statistically significant improvement ($p = 0.0375 < 0.05$).
   - Measured a practical effect size with **Cohen's d = 0.39**, indicating meaningful positive impact.

