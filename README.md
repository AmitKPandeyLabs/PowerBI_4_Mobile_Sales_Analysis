# Mobile Sales Detailed Analysis

### An end-to-end Power BI dashboard analyzing sales, product performance, and customer behavior for a mobile retailer.

<a href="https://app.powerbi.com/view?r=eyJrIjoiNzg3MTUxOWYtMjVmYS00Y2UwLTg5MmEtZWZkMjRmOGVmOGQ3IiwidCI6ImIxMGVjNzYyLTA1NjEtNDVmZS1iN2NmLWFjMWI4MzZkZTI3NyIsImMiOjF9">
  <img src="https://github.com/AmitKPandeyLabs/PowerBI_4_Mobile_Sales_Analysis/raw/main/Project4_Mobile_Sales_Detailed_Analysis.png" alt="Mobile Sales Dashboard" width="800">
</a>

### [Click Here (Ctrl+Click opens new tab) to View the Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzg3MTUxOWYtMjVmYS00Y2UwLTg5MmEtZWZkMjRmOGVmOGQ3IiwidCI6ImIxMGVjNzYyLTA1NjEtNDVmZS1iN2NmLWFjMWI4MzZkZTI3NyIsImMiOjF9)

<br>

## 📈 Project Overview

This Power BI project provides a comprehensive, end-to-end analysis of sales data for a mobile phone retailer. The solution transforms a raw Excel dataset into a fully interactive, multi-faceted dashboard. This tool empowers stakeholders to track high-level performance, drill down into granular details, and uncover actionable insights on sales trends, top-performing products, customer ratings, and regional hotspots to optimize marketing, inventory, and sales strategies.

## 🎯 Objectives

-	Track and visualize key performance indicators (KPIs) including Total Sales, Total Quantity Sold, Total Transactions, and Average Price.
-	Analyze temporal patterns by monitoring sales/quantity trends by month and day of the week.
-	Identify top-performing brands and specific mobile models to understand product mix and popularity.
-	Analyze customer preferences by examining payment method breakdowns and customer satisfaction ratings.
-	Provide a geographical analysis of sales performance across different cities in India.
-	Enable dynamic filtering through a comprehensive set of slicers for granular, on-demand analysis.

## 🔍 Key Dashboard Features

**Key KPIs:**
- **Total Sales:** 769M
- **Total Quantity:** 19K
- **Transactions:** 4K
- **Average (Price per item):** 40K

**Time-Series Analysis:**
-	`Total Quantity by Month` (Line Chart): Tracks sales volume fluctuations throughout the year, identifying key seasonal peaks and dips.
-	`Total Sales by Day Name` (Area Chart): Visualizes which days of the week are most profitable (e.g., Saturday, Monday).

**Geospatial Analysis:**
-	`Total Sales by City` (Map): An interactive map of India with bubbles scaled by sales revenue, highlighting key urban markets like Mumbai, Delhi, and Bangalore.

**Product & Brand Performance:**
-	`Total Sales by Mobile Model` (Bar Chart): Identifies the top-revenue-generating products (e.g., iPhone SE, OnePlus Nord).
-	`Brand Performance` (Matrix): A detailed breakdown of Total Sales, Total Quantity, and Transactions for each major brand (Apple, Samsung, OnePlus, Vivo).

**Customer Behavior:**
-	`Customer Ratings` (Bar Chart): Displays the distribution of customer satisfaction ratings (1 to 5 stars).
-	`Transactions by Payment Method` (Donut Chart): Shows the split between different payment types (UPI, Debit Card, Cash, Credit Card).

**Interactive Filters & Slicers:**
-	A complete set of slicers for `Month`, `Mobile Model`, `Payment Method`, `Brand`, and `Day Name` allows for powerful and flexible data exploration.

## 💡 Notable Insights

-	**Apple is the top-performing brand** with 162M in Total Sales, closely followed by Samsung (160M) and OnePlus (154M), indicating a highly competitive market for premium brands.
-	**Sales peak strongly in July** (1,700 units) and **March** (1,696 units), with a noticeable dip in February (1,451 units). This insight is critical for inventory planning and targeted marketing campaigns.
-	Purchasing behavior is highest on **Saturday (115M in sales)** and **Monday (114M in sales)**, suggesting that customers are most active during the weekend and at the very beginning of the work week.
-	Payment methods are very evenly distributed, with **UPI (26.25%)**, **Debit Card (25.89%)**, and **Credit Card (25.03%)** being almost equally popular. This diverse payment landscape shows a healthy adoption of various digital payment technologies.
-	While customer ratings are generally positive (led by 5-star reviews), there is a significant number of 3-star and 2-star ratings, indicating a clear **opportunity to improve customer satisfaction**.

## 🛠️ Tools & Skills Demonstrated

-	**Power BI Desktop**: Data Import, Data Cleaning, Data Modeling, Visualization, and Report Building.
-	**Power Query (ETL)**: Imported and transformed the raw Excel data; performed extensive data cleaning (trimming text, handling nulls) and set correct data types for accurate analysis.
-	**DAX (Data Analysis Expressions)**: Created foundational measures from scratch:
    - `Total Sales = SUM(Sales[Total Price])`
    - `Total Quantity = SUM(Sales[Quantity])`
    - `Transactions = COUNT(Sales[Invoice ID])`
    - `Average = [Total Sales] / [Total Quantity]`
-	**Data Modeling**: Established a clean data model from the flat file to be used in the report.
-	**Advanced Visuals**: Configured and formatted KPI cards, line charts, area charts, donut charts, and an interactive geospatial map.
-	**Dashboard Design (UI/UX)**: Designed a visually compelling and intuitive dark-mode dashboard with logical layout and interactive slicers for a seamless user experience.
-	**Power BI Service**: Published the report to the Power BI service to be shared and accessed by stakeholders via a web link.

## 🚀 Usage

1. **[Launch (Ctrl+Click opens new tab) the interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzg3MTUxOWYtMjVmYS00Y2UwLTg5MmEtZWZkMjRmOGVmOGQ3IiwidCI6ImIxMGVjNzYyLTA1NjEtNDVmZS1iN2NmLWFjMWI4MzZkZTI3NyIsImMiOjF9)**.
2. Use the slicers on the left (Month) and top (Mobile Model, Payment Method, etc.) to filter the data.
3. Click any element on a chart (e.g., "Apple" in the table or "Mumbai" on the map) to cross-filter the entire dashboard.
4. Hover over any visual to see detailed tooltips and specific data points.
