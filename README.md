# 📊 Nestlé Sales Performance Dashboard: A Comprehensive Business Intelligence Solution

## 📘 Project Overview  
Nestlé, a global FMCG leader with a diverse portfolio of beverages, confectionery, dairy, and nutrition products, faced challenges in gaining a unified, real-time view of sales performance across the American region.  
This Power BI project delivers an **end-to-end Business Intelligence solution**, consolidating key KPIs such as revenue, profit, discounts, and churn rate to drive data-backed decision-making.

---

## 🎯 Business Objective  
- Build an **interactive Power BI dashboard** to monitor sales, profit, and expenditure.  
- Identify **top-performing products, categories, and regions**.  
- Analyze **YoY, QoQ, and MoM sales growth** and discount impact on profitability.  
- Track **customer churn rate** to improve retention strategies.  
- Provide **real-time insights** via filters (Region, State, Segment, Date).

---

## 📁 Dataset Overview  

| **Attribute** | **Description** |
|----------------|-----------------|
| **Domain** | FMCG / Retail Analytics |
| **Region** | America |
| **Time Period** | 2022–2024 |
| **Source** | Kaggle |


---

## ⚙️ Technical Approach  

### 🧩 ETL Process (Extract, Transform, Load)
**Extract:** Imported multiple datasets into Power BI.  
**Transform:**  
- Performed **data cleaning** using Power Query and M language.  
- Used **fuzzy matching** for consistent product, city, and state names.  
- Fixed datatypes for *Sales, Profit, Discount, Date*.  
- Removed nulls under 5% as per business rules.  

**Feature Engineering:**  
- `Expenditure = [Sales Amount] - [Profit]`  
- `Discount Amount = [Discount%] × [Sales Amount]`  
- `Net Profit = [Profit] - [Discount Amount]`  
- `Profit Margin% = ([Net Profit] / [Sales Amount]) × 100`  

**Load:** Loaded the clean, modeled dataset into Power BI for dashboard visualization.

---

## 📈 Key Findings  
- **Total Revenue:** $3.50M  
- **Net Profit:** $912.93K (26.1% Margin)  
- **Top Product:** *Gerber Gentle* ($0.14M Profit)  
- **Top Categories:** Nutrition (48%) and Beverages (39%)  
- **QTR Growth:** 19.26% | **MoM Growth:** 6.96%  
- **Customer Churn Rate:** 5.09% → 10.12% (2022–2024)  

---



## 💼 Business Impact  
✅ Provided a **unified, data-driven BI solution** for sales monitoring across the American region.  
✅ Improved **profitability tracking** and **customer retention insights**.  
✅ Enabled **strategic decisions** through real-time analytics and visual storytelling.  
✅ Ensured **data consistency and accuracy** via automated ETL and data modeling.

---

## 🧰 Tech Stack  

| **Category** | **Tools / Technologies Used** |
|---------------|------------------------------|
| **BI Tool** | Power BI |
| **Data Processing** | Power Query (M Language), DAX |
| **Database** | MySQL |
| **Data Source** | MySQL |
| **Modeling** | Star Schema (Fact & Dimension Tables) |
| **Visualization** | KPI Cards, Bar & Line Charts, Donut Charts, Maps, Slicers |
| **Techniques Used** | ETL Process, Fuzzy Matching, DAX Measures, Churn Analysis, Dynamic Filtering |

---

