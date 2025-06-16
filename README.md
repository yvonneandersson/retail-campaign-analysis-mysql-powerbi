# Campaign Performance Analysis & Visualization

This repository contains the complete project for analyzing and visualizing campaign performance data for a retail company. The project uses MySQL for data analysis and Power BI for dashboard creation. It is designed to help management understand how different campaign elements (types, discounts, addons, and requirements) impact **activation** and **profit**.

---

## 🎯 Objective

The goal is to analyze historical order data to extract insights into campaign effectiveness and provide interactive dashboards for the management board. Each order in the dataset includes details such as campaign type, discount levels, addons, requirements, activation, and profit.

---

## 🗃️ Data Description

The data includes:

- **Time dimensions** (Year, Quarter, Month, Day, Week)
- **Campaign types** (e.g., `check`, `firstline`, `ladder`, `threeForTwo`, etc.)
- **Addons** (e.g., free gift, shipping, return)
- **Requirements** (e.g., min value, item types, brand selection)
- **Discount levels** (DisFirst, DisSecond, DisCheck)
- **Target metrics**: `activation`, `profit`

---

### ✅ SQL Analysis (MySQL Workbench)
- Import and merge `activation.csv` and `profit.csv` into a `CAMPAIGN` database
- Clean, rename, and enrich data
- Detect and remove invalid campaign records
- Create descriptive statistics, correlation views, and labeled categories (Good/Bad)
- Final dataset prepared for visualization

---

### 📊 Power BI Dashboard
Includes 4 interactive pages:

1. **Overview**: Summary by campaign types with filters by time
2. **Profit Analysis**: Trends and key influencers for profit
3. **Activation Analysis**: Effectiveness and impact factors
4. **Summary & Suggestions**: Insights, recommendations, and custom views

---

## 🧾 Results

📄 [View Report (PDF)](./documents/report-dataanalysis.pdf.pdf)

📄 [View Analysis (Code) (PDF)](./documents/dataanalysis-compl.pdf.pdf)

PowerBI:




---

_This project combines practical data engineering and business analytics skills to deliver actionable insights from real-world marketing data._
