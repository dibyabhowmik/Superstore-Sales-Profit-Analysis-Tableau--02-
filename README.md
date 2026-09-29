Project Overview:
Super Market Sales Analysis is a Tableau-based sales and profitability analysis using the Superstore dataset. The project examines sales performance across categories, sub-categories, regions, customer segments, and time while also analyzing discounts and their relationship with profitability.

The dataset contains 9,994 order-level records and was used to create two business-focused dashboards: Sales Performance and Profitability & Business Insights.

Objectives:
Measure overall sales and profit performance.
Identify high-performing categories and sub-categories.
Compare sales and profitability across regions.
Analyze customer segment performance.
Understand monthly and yearly sales trends.
Examine discount patterns across categories.
Compare average sales and profit.
Analyze the relationship between Sales and Profit.
Identify areas of strong and weak profitability.
Tools & Techniques Used
Tableau Public
Superstore dataset
Data cleaning and numeric conversion
Calculated fields
Aggregation and grouping
Sorting
Filters
Bar charts
Line charts
Scatter plots
Trendlines
KPI cards
Dashboard design
Interactive business analysis
Data Preparation & Process

The original Sales and Profit fields required numeric conversion for analysis.

Sales Numeric:

FLOAT(REPLACE([Sales], "$", ""))

Profit Numeric:

FLOAT(REPLACE([Profit], "$", ""))

These calculated fields were then used throughout the analysis instead of relying on the original text-formatted financial fields.
The project was organized into individual worksheets covering sales, profit, category, sub-category, region, segment, discount, and relationship analysis.

Two dashboards were then created.

Dashboard 1 — Sales Performance

The dashboard combines:

Total Sales
Total Profit
Sales by Category
Sales by Region
Monthly Sales Trend
Sales by Segment
Sales by Sub-Category
Dashboard 2 — Profitability & Business Insights

The dashboard combines:

Total Sales
Total Profit
Profit by Sub-Category
Profit by Region
Profit by Segment
Average Discount by Category
Sales vs Profit
Average Profit by Sub-Category

Key Insights:
Total Sales were approximately $2.30 million.
Total Profit was approximately $286.3 thousand.
Technology generated the highest total profit at approximately $145.4 thousand.
Office Supplies generated approximately $122.5 thousand profit.
Furniture generated approximately $18.4 thousand profit, showing a much weaker profitability contribution.
The West region generated the highest total profit at approximately $108.4 thousand.
The Consumer segment generated the highest total profit at approximately $134.1 thousand.
Copiers generated the highest total profit among sub-categories at approximately $55.6 thousand.
Tables recorded a substantial negative profit contribution, highlighting a significant profitability issue within that sub-category.
Furniture had the highest average discount among the three major categories.
The Sales vs Profit analysis showed a positive relationship between sales and profit, although higher sales did not always guarantee higher profitability.
