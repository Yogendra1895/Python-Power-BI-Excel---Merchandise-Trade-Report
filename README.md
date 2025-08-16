# 📊 Merchandise Trade Report – Import/Export Analysis  

## 🔎 Dashboard Preview
![Merchandise Report](https://github.com/user-attachments/assets/ff042bd5-719b-4e45-9b82-db976dc6db17)


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

## 🚀 Tech Stack  
- 🐍 **Python** → Pandas, NumPy, Matplotlib, Seaborn  
- 📊 **Power BI** → Dashboard & Visuals  
- 📑 **Excel** → Data validation & prep  

