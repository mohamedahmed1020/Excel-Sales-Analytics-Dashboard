# Excel-Sales-Analytics-Dashboard
<img width="1521" height="564" alt="Screenshot 2026-11-24 202615_edited" src="https://github.com/user-attachments/assets/521684dd-4632-4c63-ad13-663eec375876" />
<img width="1382" height="733" alt="Screenshot 2026-11-24 202515_edited" src="https://github.com/user-attachments/assets/80b59e4c-1490-4928-b405-e6523e206c46" />
# 📊 Global Sales Performance & Executive Analytics Dashboard

An end-to-end data analytics workbook built in **Microsoft Excel**, transforming **10,000+ raw global sales records** into actionable business intelligence, statistical insights, and an executive KPI dashboard.

---

## 🎯 Business Objective
Analyze global sales transactions across regions, countries, product categories, and sales channels to evaluate revenue drivers, profit margins, fulfillment efficiency, and statistical anomalies.

---

## 🗂️ Workbook Architecture (11 Structured Sheets)
1. **Executive Dashboard:** High-level KPI cards, core business findings, and dataset scope overview.
2. **Raw Data:** Original untouched dataset (`10,000 Sales Records.csv`) preserved for auditability.
3. **Cleaned Data:** Standardized dates, trimmed text fields, engineered KPIs (`Shipping Days`, `Profit Margin %`, `Order Year/Month`), and outlier flags.
4. **Data Quality Report:** Automated validation checks confirming zero missing values, zero duplicate Order IDs, and valid date logic.
5. **Data Dictionary:** Complete schema documentation defining column types, meanings, and analytical roles.
6. **Descriptive Statistics:** Numerical distribution summary (Mean, Median, Std Dev, Min, Q1, Q3, Max) across key financial and operational metrics.
7. **Pivot Analysis:** Multi-dimensional performance breakdowns by **Region**, **Item Type**, **Sales Channel**, and **Order Priority**.
8. **Time Trend:** Monthly revenue, cost, profit, and margin progression over time.
9. **Correlation & Outliers:** Pearson correlation matrix and Interquartile Range (IQR) anomaly detection without distorting raw totals.
10. **Methodology & Limitations:** Documentation of data preparation rules, grain definitions, and analytical assumptions.
11. **Formula Audit:** Dynamic Excel verification checks ensuring 100% calculation accuracy across Revenue, Cost, and Profit fields.

---

## 📈 Key Findings & Executive KPIs
* **Total Orders Analyzed:** `10,000` transactions (`50,028,559` total units sold)
* **Total Revenue:** `$13,333,551,314.32`
* **Total Profit:** `$3,950,893,471.93`
* **Overall Profit Margin:** `29.63%`
* **Average Fulfillment Time:** `25.06 days`
* **Top Revenue Region:** **Europe** (`$3.48B` revenue across `2,633` orders)
* **Highest Margin Region:** **Australia and Oceania** (`30.87%` profit margin)
* **Top Product Category:** **Household** (highest revenue) | **Clothes** (highest profit margin)
* **Sales Channel Split:** **Offline** leads in total revenue volume compared to Online channels.

---

## 🛠️ Tools & Analytical Techniques Used
* **Microsoft Excel:** Advanced Formulas (`SUMIFS`, `AVERAGEIFS`, `IF`, `MEDIAN`, `PERCENTILE.INC`, `CORREL`), Pivot Tables, Conditional Formatting, Data Validation.
* **Data Cleaning & Auditing:** Whitespace trimming, date standardization, automated error/mismatch auditing.
* **Statistical Analysis:** Descriptive distribution profiling, Pearson correlation analysis, and IQR outlier detection.

---

## 🚀 How to Use This Repository
1. Download `Sales_Analytics_Dashboard.xlsx` and `10000 Sales Records.csv`.
2. Open the `.xlsx` file in **Microsoft Excel** (enable editing/recalculation if prompted so `Formula Audit` checks update dynamically).
3. Start with the **`Executive Dashboard`** tab for the summary view, or explore **`Pivot Analysis`** and **`Descriptive Statistics`** for granular breakdowns.

---

## 👤 Author
**Mohamed Ahmed Hassan** — Data Analyst  
* **LinkedIn:** [linkedin.com/in/mohamed-ahmed-hassan-](https://www.linkedin.com/in/mohamed-ahmed-hassan-/)  
* **GitHub:** [github.com/mohamedahmed1020](https://github.com/mohamedahmed1020)
