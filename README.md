# 📊 Merchandise Trade Report – Import/Export Analysis  

![Dashboard Preview](Merchandise%20Report.JPG)  

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?logo=python)](https://www.python.org/)  
[![Power BI](https://img.shields.io/badge/Visualized%20in-Power%20BI-yellow?logo=powerbi)](https://powerbi.microsoft.com/)  
[![Excel](https://img.shields.io/badge/Data%20Cleaned%20in-Excel-green?logo=microsoft-excel)](https://www.microsoft.com/en-us/microsoft-365/excel)  

---

## 🔎 Project Overview  
This project analyzes **global merchandise trade flows (1948–2024)** using annual import/export data.  
It uncovers **trade imbalances, sector contributions, and country-level insights**, presented in an **interactive Power BI dashboard**.  

---

## 📂 Dataset Details  
| Column | Description |  
|--------|-------------|  
| `Reporter` | Reporting country/region |  
| `Partner` | Partner country/region |  
| `Year` | Trade year (1948–2024) |  
| `Product` | Product classification (e.g., Manufactures, Fuels, Machinery) |  
| `Indicator` | Trade type (Imports/Exports) |  
| `Value` | Trade value (Million USD) |  

📌 **Source**: UNCTAD Merchandise Trade Values (Annual)  

---

## 🛠️ Workflow  
1. **Data Cleaning (Python + Excel)**  
   - Removed missing/inconsistent values (`ReporterISO3A`, `ValueFlag`)  
   - Standardized codes & product categories  
   - Exported cleaned dataset  

2. **Exploratory Data Analysis (Python)**  
   - Pivot tables by year, country, and product  
   - Trend analysis & trade balance calculation  

3. **Dashboarding (Power BI)**  
   - KPIs: Imports, Exports, Trade Balance  
   - Year-wise trade flow (line + bar combo)  
   - Country-wise surplus/deficit bar charts  
   - Product-wise exports (TreeMap)  

---

## 📈 Key Insights  
- **Top Export Sectors**: Manufactures, Machinery, Fuels  
- **Positive Trade Balance Leaders**: China, EU, Germany, Japan  
- **Negative Trade Balance Leaders**: India, WTO Members, USA  
- **Trend**: Strong export growth post-2000, dip in 2020 (COVID), recovery afterward  

---

## 📊 Dashboard Sneak Peek  
📌 **Interactive Dashboard Built in Power BI**  

![Trade Dashboard](Merchandise%20Report.JPG)  

---

## 🚀 Tech Stack  
- 🐍 **Python** → Pandas, NumPy, Matplotlib, Seaborn  
- 📊 **Power BI** → Dashboard & Visuals  
- 📑 **Excel** → Data validation & prep  

