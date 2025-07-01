# 📦 Retail and Warehouse Sales Analysis Project

This project performs comprehensive data analysis and business intelligence on a multi-year retail and warehouse sales dataset. It integrates **Python for data preprocessing and EDA** and **Power BI for building interactive dashboards** that deliver actionable insights.

---

## 📌 Objective

To analyze and visualize sales trends, product performance, inventory movement, and supplier efficiency using real-world retail data. The project aims to help business decision-makers identify patterns, optimize stock levels, and monitor KPIs across time.

---

## 📁 Dataset Overview

- **Source:** [Original Company Dataset - Warehouse and Retail Sales]
- **File:** `Cleaned_Warehouse_and_Retail_Sales.csv`
- **Size:** ~305K rows
- **Fields Include:**
  - `YEAR`, `MONTH`, `DATE`
  - `SUPPLIER`, `ITEM CODE`, `ITEM DESCRIPTION`, `ITEM TYPE`
  - `RETAIL SALES`, `RETAIL TRANSFERS`, `WAREHOUSE SALES`
  - `INVENTORY_EFFICIENCY` (calculated)

---

## ⚙️ Tools & Technologies

- 🐍 **Python** (Pandas, Matplotlib): Data cleaning, feature engineering, and EDA
- 📊 **Power BI**: KPI dashboard development and visual reporting

---

## 🧹 Data Cleaning (Python)

- Removed rows with missing or invalid sales/supplier/item values
- Removed negative sales/transfer values (considered data issues)
- Added a unified `DATE` column for time-series analysis
- Calculated `INVENTORY_EFFICIENCY = RETAIL SALES / (RETAIL TRANSFERS + 1)`

All cleaning steps are reproducible via `data_cleaning.py` or Jupyter Notebook.

---

## 📈 Power BI Dashboard Features

- 📅 **Retail Sales Over Time** (Line Chart)
- 🏷️ **Sales by Item Type** (Bar Chart)
- 🧾 **Top 10 Products** by Total Retail Sales
- 🚚 **Retail vs Warehouse Sales by Supplier**
- 📊 **KPI Cards**:
  - Total Retail Sales
  - Total Warehouse Sales
  - Average Inventory Efficiency
  - Top Performing Product
- 🔍 **Interactive Filters**:
  - Year
  - Item Type

---

## ✅ Key Insights

- Wine and beer dominate retail sales across most months
- Certain suppliers consistently outperform others in warehouse delivery and efficiency
- Inventory efficiency varies significantly by item type
- Sales peaked during specific months (seasonality trends detected)

---

## 🧠 Future Improvements

- Add regional/geographic dimension for location-based insights
- Integrate cost/profit fields for margin analysis
- Forecasting retail demand using ML in Python

---

## 💡 Author

**Harini Sruthi T S**  
_Data Analyst | Python Developer | BI Enthusiast_

---

