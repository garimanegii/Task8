# 📊 Simple Sales Dashboard – Task 8

## 📌 Overview  
This project is part of my **Data Analyst Internship (Task 8)**, where the objective was to design and develop a **simple interactive sales dashboard** using **Power BI**.  
The dashboard provides insights into sales performance across **months, regions, and categories**, enabling better understanding of trends and top-performing areas.

---

## 🎯 Objective  
- Import and prepare the sales dataset.  
- Transform date fields into **Month-Year** format for time-series analysis.  
- Build 3 main visualizations:  
  1. **Line Chart:** Sales over Months  
  2. **Bar Chart:** Sales by Region  
  3. **Donut Chart:** Sales by Category  
- Add a slicer to filter results by **Region** or **Category**.  
- Highlight top-performing areas using color formatting.  
- Write 3–4 concise insights from the dashboard.

---

## 🛠 Tools Used  
- **Power BI Desktop** – Dashboard design and interactivity.  
- **Power Query** – Data cleaning and transformation with DAX.  
- **Microsoft Excel** – Initial review of the dataset.  

---

## 📂 Dataset  
**File Name:** `Excel__SuperstoreSales.xlsx`  
**Key Columns Used:**  
- `Order Date` – Converted to **Month-Year** format.  
- `Region` – For regional performance analysis.  
- `Category` – For category-based sales distribution.  
- `Sales` – Main performance metric.  
- `Profit` – For profitability analysis.

---

## 🔄 Data Preparation  
1. **Loaded dataset** into Power BI.  
2. Used **Power Query** to:  
   - Change `Order Date` to **Date** type.  
   - Extract Month and Year → merge into a new **Month-Year** column.  
   - Ensure chronological sorting by linking Month-Year to `Order Date`.  
3. Removed unnecessary columns for cleaner visuals.  

---

## 📊 Dashboard Visuals  
1. **Line Chart – Sales over Months**  
   - Axis: `Month-Year`  
   - Values: Sum of `Sales`  
   - Purpose: Show sales trends over time.  

2. **Bar Chart – Sales by Region**  
   - Axis: `Region`  
   - Values: Sum of `Sales`  
   - Purpose: Identify highest and lowest performing regions.  

3. **Donut Chart – Sales by Category**  
   - Legend: `Category`  
   - Values: Sum of `Sales`  
   - Purpose: Show proportion of total sales by category.  

4. **Slicer – Region**  
   - Field: `Region`  
   - Purpose: Filter all visuals interactively.  

---

## 🔍 Key Insights  
1. **Sales Trend:** Sales increased steadily throughout the year, peaking in **November and December**.  
2. **Regional Performance:** The **West** region generated the highest sales, while the **Central** region recorded the lowest.  
3. **Category Share:** **Technology** contributed the largest share of total sales, followed by Furniture and Office Supplies.  
4. **Year-End Spike:** The highest sales months coincided with year-end shopping periods.


---

## 📌 Author  
**Garima Negi**  
Data Analyst Intern  
📧 Email: *garimanegi243@gmail.com*  
