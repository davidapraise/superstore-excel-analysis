# superstore-excel-analysis

# Superstore Excel Analysis Dashboard  
[View on GitHub](https://github.com/davidapraise/superstore-excel-analysis)
  
This project uses the _Superstore_ dataset to demonstrate end-to-end data analytics skills using Microsoft Excel. The deliverables include:  
  - A cleaned and transformed dataset  
  - PivotTables for in-depth analysis  
  - An interactive dashboard with charts & slicers  
  - Insights into retail business performance  

Tools Used  
  - Microsoft Excel (desktop)  
  - PivotTables, Charts, Slicers  
  - Data cleaning functions (TRIM, PROPER, TEXT, YEAR, MONTH, ROUNDUP)  
  - Dashboard design skills  

Dataset Description  
The source data is the “Sample – Superstore” dataset (available on Kaggle). It includes fields like:  
    - Order ID, Order Date, Ship Date, Customer Name  
    - Segment, Country, City, State, Region  
    - Category, Sub-Category, Product Name  
    - Sales, Quantity, Discount, Profit  

Data Cleaning & Transformation  
Key steps performed:  
  - Converted “Order Date” & “Ship Date” from MM/DD/YYYY to DD/MM/YYYY format  
  - Trimmed and standardised text fields for consistency (City, State, Category, Sub-Category, Customer Name)  
  - Added calculated fields:  
    - Profit Ratio = Profit ÷ Sales  
    - Year, Month Name, Month Number, Quarter  
  - Converted dataset into a structured Excel Table (named `SuperstoreData`) for easier referencing  

Analysis & PivotTables  
Seven PivotTables were created to slice and dice the data:  
  1. Sales by Category  
  2. Sales by Sub-Category  
  3. Sales by Region  
  4. Monthly Sales Trend (by Year & Month)  
  5. Profit by Category  
  6. Profit Ratio by Category  
  7. Top 10 Products by Sales  

Interactive Dashboard  
The dashboard sheet ties all the visuals together and uses slicers for dynamic filtering by:  
  - Year  
  - Category  
  - Segment  
  - Region  

Visuals included:  
  - Column chart for Sales by Category  
  - Horizontal bar chart for Top Sub-Categories  
  - Column chart for Sales by Region  
  - Line chart for Monthly Sales Trend (multiple years)  
  - Column chart for Profit by Category  
  - Bar chart for Profit Ratio by Category  
  - Horizontal bar chart for Top 10 Products  

Key Findings  
  - Phones are in the top 3 highest selling sub-categories every year, presumably due to constant demand and new releases.
  - The Technology category delivered the highest profit ratio.  
  - Sales peaked in Q4 of each year due to festive season demand.  
  - The Top 10 products accounted for ~30% of total sales, highlighting focus opportunities.  

1. Download or view the Excel file in the `/dashboard/` folder.  
2. Explore the “Dashboard” sheet for interactive analysis.  
3. View the `/visuals/` folder for static screenshots of charts.  
4. View the `/pivots/` folder for the overview of all PivotTables.  
5. Use this as a portfolio piece or a template for your own analytic work.  

About the Author  
**Davida Praise Sofela**  
Aspiring Data Analyst | Excel | SQL | Geospatial Analysis  
LinkedIn: www.linkedin.com/in/davidasofela
[GitHub](https://github.com/davidapraise)  

---
