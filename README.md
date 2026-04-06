# 📊 Sales Analysis Dashboard (Excel Capstone Project)

## 🧹 Data Cleaning
- Standardized categorical fields such as **Region** and **Product Category** to remove inconsistencies  
- Verified and aligned keys across sheets:
  - `Product_Dim`
  - `Store_Dim`
  - `Sales_Fact`  
- Removed duplicate and inconsistent entries in transactional data  
- Ensured proper formatting of numeric columns (Revenue, Quantity, Price)  
- Cleaned text fields using:
  - `TRIM()` → removed extra spaces  
  - `PROPER()` → standardized text casing  

---

## 🔧 Data Preparation & Transformation
- Created structured relationships between dimension and fact tables  
- Aggregated data using **Pivot Tables** for analysis  
- Derived key metrics:
  - Total Revenue → `SUM(Total Amount)`  
  - Total Transactions → `COUNT(Total Amount)`  
- Grouped data by:
  - Region  
  - Category  
  - Year  

---

## 📈 Data Analysis
- Performed comparative analysis across:
  - Regions (North, South, East, West)  
  - Product Categories  
- Evaluated:
  - Revenue distribution  
  - Transaction volume distribution  
- Identified trends using **time-series (year-wise) analysis**  
- Cross-validated consistency between:
  - Revenue vs Transaction counts  

---

## 📊 Pivot Tables & Visualizations
- **Revenue by Region** (Column Chart)  
- **Transactions by Region** (Bar Chart)  
- **Yearly Revenue Trend** (Line Chart)  
- **Revenue by Product Category** (Bar Chart)  
- **KPI Cards**:
  - Total Revenue  
  - Total Transactions  
  - Top Region  
  - Top Store Type  
- Added **Slicers** for:
  - Region  
  - Category  

---

## 💡 Key Insights
- **Top Region:** North generates the highest revenue (~₹639K)  
- **Lowest Region:** West shows significantly lower performance  
- **Transaction Distribution:** South and East lead in order volume  
- **Top Category:** Sports and Electronics dominate revenue  
- **Trend Insight:** Revenue grows sharply initially and stabilizes after 2025  
- **Store Type:** Online channel contributes the highest sales  


---

## 🚀 Future Enhancements
- Add **Profit and Margin Analysis**  
- Include **Average Order Value (AOV)**  
- Introduce **Year-over-Year Growth %**  
- Add **Top 5 Products analysis**  
- Build an advanced version using **Power BI**  

---

## ✨ Project Summary
This project demonstrates **end-to-end Excel-based data analysis**, including data cleaning, transformation, visualization, and insight generation.

It highlights the ability to convert raw data into **structured dashboards and meaningful business insights** using Excel.

---

## 👨‍💻 Author
**Nitesh Raj R G**  
- Data Analyst | Big Data Enthusiast  
- Skills: Excel, SQL, PySpark, Data Visualization
