# 👟 Nike Sales Dashboard — Power BI

An end-to-end sales analytics project for Nike India, covering data cleaning of a raw dataset and an interactive Power BI dashboard for business insights.

---

## 📊 Dataset Overview

| Property | Value |
|----------|-------|
| Records | 2,500 orders |
| Columns | 13 |
| Source | Nike_Sales_Uncleaned.csv |

### Columns
Order_ID, Gender_Category, Product_Line, Product_Name, Size, Units_Sold, MRP, Discount_Applied, Revenue, Order_Date, Sales_Channel, Region, Profit

---

## 🧹 Data Cleaning Issues Found

| Column | Issue |
|--------|-------|
| Units_Sold | ~1,235 missing values |
| MRP | ~1,254 missing values |
| Discount_Applied | ~1,668 missing values |
| Order_Date | ~616 missing values + inconsistent formats (YYYY-MM-DD vs DD-MM-YYYY) |
| Size | ~510 missing values |
| Region | Inconsistent naming (bengaluru / Bangalore, Hyd / Hyderabad / hyderbad) |

---

## 📈 Dashboard Insights

- **Revenue & Profit** — Total and trend over time
- **Product Line Performance** — Training, Soccer, Lifestyle, Running, Basketball
- **Gender Category Analysis** — Men, Women, Kids
- **Sales Channel Comparison** — Online vs Retail
- **Regional Breakdown** — Bengaluru, Mumbai, Delhi, Hyderabad, Pune, Kolkata
- **Discount Impact** — Relationship between discount rates and profit

---

## 🗂️ Project Structure

Nike-Sales-Dashboard/
├── Nike_Sales_Uncleaned.csv     # Raw dataset with missing values and inconsistencies
└── Nike_Sales_Dashboard.pbix    # Power BI dashboard file

---

## 🛠️ Tech Stack

![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel/CSV](https://img.shields.io/badge/CSV-Data-green)

- Power BI Desktop — Dashboard and visualizations
- Power Query — Data cleaning and transformation
- DAX — Calculated measures and KPIs

---

## 🚀 How to Open

1. Download Power BI Desktop from https://powerbi.microsoft.com
2. Open Nike_Sales_Dashboard.pbix
3. If prompted, relink the data source to Nike_Sales_Uncleaned.csv

---

## 📌 Notes

- Data covers Nike India sales across 9 regions
- Sales channels: Online and Retail only
- All cleaning steps performed inside Power Query Editor
