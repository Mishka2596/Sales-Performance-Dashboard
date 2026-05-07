# Sales-Performance-Dashboard
This project is a Power BI dashboard built using the Superstore dataset. It provides insights into sales performance, profitability, and trends over time.

# Data Model

A star schema was implemented to improve performance and usability:

# Fact Table:
Orders
# Dimension Tables:
Dim_Date
Dim_Region
Dim_Category
Dim_Segment

Relationships were created using a many-to-one structure with single-direction filtering.

# Key Measures (DAX)
Total Sales
Total Profit
Profit Margin %
Sales Last Year (LY)
Sales Year-over-Year Growth (YoY %)

# Dashboard Features
KPI cards for high-level metrics
Sales breakdown by region, category, and segment
Monthly sales trend analysis
Interactive slicers for filtering

# Key Insights
Identifies top-performing regions and categories
Tracks sales growth over time
Highlights profitability trends

# Tools Used
Power BI
DAX (Data Analysis Expressions)
Data Modeling (Star Schema)

# How to Use
Open the Power BI file (.pbix)
Use slicers to filter data by year, region, category, or segment
Explore trends and performance metrics

