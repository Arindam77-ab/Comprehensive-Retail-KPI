 Project Title: Comprehensive-Retail-KPI

Tool Used: Power BI
Data Source: Excel file containing transactional sales data (over 12K rows)

Objective:
To build an interactive and insightful Power BI dashboard for analyzing sales, profit, quantity, and product distribution across various dimensions such as Region, Category, Market, and Time for a global superstore.

Key Steps & Workflow:
1. Data Preparation & Cleaning
   
Imported raw sales data from Excel.
Checked for and handled missing or inconsistent values.
Converted data types (e.g., dates, numeric fields).
Created new calculated columns like Year, Quarter, Month, Day, etc.

2. Data Modelling
   
Built a star schema with a central Orders fact table.
Applied relationships between dimensions like Region, Category, State, Segment, and Ship Mode.
Ensured relationships were correctly defined (one-to-many, single-direction).

3. DAX Measures
   
Created custom DAX measures for:
Total Sales, Total Profit, Total Quantity, Total Products
Year-wise and Category-wise breakdowns
Profit Margin by Segment and Market
Dynamic filtering using slicers

4. Dashboard Development
a. Executive Summary Page

KPIs for Total Sales (₹12.64M), Profit (₹1.47M), Quantity, Products
Donut charts for Sales and Profit by Category
Line chart for yearly sales trend
Bar charts for sub-category analysis
Sales vs. Profit by Segment

b. Customer Summary Page

Treemap for Sales by Region
Line chart for Profit by Year
Bar charts for Sales by State, Quantity by Segment
Pie chart for Sales by Ship Mode
Market-wise Profit Analysis

c. Raw Data Page

Tabular view of the original dataset for verification and transparency
Used for audit and validation purposes

5. Interactivity & UX

Slicers for Category, Sub-Category, Region, Country, State, Market, and Order Priority
Drill-down capabilities in visuals
Page-level filters to enable dynamic storytelling
Applied theme colors and consistent layout for better visual hierarchy

Outcomes:

Delivered an end-to-end, interactive dashboard for business insights.
Helped identify top-performing categories, customer segments, and regions.
Enabled business stakeholders to make data-driven decisions quickly.
