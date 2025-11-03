## 🧾 Superstore Sales & Profitability Dashboard (Power BI Project)
### 3📊 Overview

This Power BI dashboard analyzes Superstore’s sales performance, profitability, and regional trends using interactive visuals and DAX measures.
It enables users to explore insights such as sales growth, profit distribution, category contribution, and profit margin across different time periods and regions.

### 🧠 Objectives

Visualize key business metrics such as Total Sales, Profit, and Profit Margin %.

Identify top-performing regions, categories, and products.

Provide interactive filters (slicers) to analyze data by Year, Category, and Region.

Enable data-driven decision making using clean, modern visuals.

### ⚙️ Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Excel (Superstore Dataset)

Data Cleaning & Transformation using Power Query

### 📈 Key Visuals & Insights
Visual Type	Description
Card Visuals	Displayed Total Sales, Total Profit, and Profit Margin %
Line Chart	Monthly Sales Trend
Column Chart	Regional Sales Comparison
Pie Chart	Category-wise Sales Share
Map Visual	Geographic distribution of Sales by State
Table Visual	Detailed breakdown by Category, Sub-Category, Product Name
### 🧮 DAX Measures
Total Sales = SUM(Orders[Sales])
Total Profit = SUM(Orders[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

### 🎨 Design Principles

    Consistent color theme (light gray background + white visuals)

    Simple typography (Segoe UI, Arial)

    Clear, interactive layout aligned for readability

    Conditional formatting for performance visualization

### 🧩 Project Highlights

✅ Built end-to-end interactive dashboard from raw Excel data
✅ Created calculated columns and DAX measures for business KPIs
✅ Used slicers and tooltips for dynamic data exploration
✅ Published a professional-quality Power BI report
### 🚀 How to Use

    Download the .pbix file from this repository.

    Open it in Power BI Desktop (latest version recommended).

    Explore visuals and slicers interactively.

## 🆕 Updates & Enhancements (November 2025)

This Power BI project has been enhanced for improved performance, data accuracy, and visual clarity.

### 🔍 Key Improvements
- 🧹 **Data Cleaning:** Removed blank and error rows; corrected data types (Date, Decimal, Text).  
- 🏷️ **Column Standardization:** Replaced spaces in column names with underscores (_) for consistency.  
- 🔗 **Data Transformation:** Used *Group By* and *Merge Queries* for cleaner relationships between tables.  
- 📊 **Visualization Optimization:** Improved layout, chart readability, and interactivity.  
- 🧮 **DAX Enhancements:** Added and optimized measures like *Profit Margin %*, *Total Sales*, *Total Profit*.  
- ⚙️ **Performance Optimization:** Removed unused columns and optimized relationships to improve refresh speed.  
- 💾 **Version Update:** Latest version uploaded to GitHub — ready for Power BI Service publishing.

📎 **Download the updated project:**  
[Superstore-Sales-Dashboard.pbix](Superstore-Sales-Dashboard.pbix)
