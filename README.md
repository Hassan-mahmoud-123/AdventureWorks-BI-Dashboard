📊 AdventureWorks: Global Sales & Returns BI Solution
🚀 Project Overview
This project involves building a comprehensive end-to-end Business Intelligence solution for AdventureWorks, a global manufacturing company. The goal was to transform raw sales, product, and customer data into an interactive dashboard that tracks performance, monitors KPIs, and uncovers actionable business insights.

Total Revenue: $24.9M.

Total Profit: $10.5M.

Unique Customers: 9.1K.

Overall Return Rate: 2.2%.

🛠️ Tech Stack
Power BI: Data Visualization & Reporting.

Power Query: ETL processes and data cleaning.

DAX (Data Analysis Expressions): Advanced calculations and Time Intelligence.

Data Modeling: Snowflake Schema architecture.

🏗️ The Data Journey (Process)
1. Data Transformation (ETL)
Using Power Query, I connected and cleaned multiple data sources, ensuring data types were consistent and handling missing values to prepare a solid foundation for analysis.

2. Data Modeling
Architected a complex Snowflake Schema. I established relationships between Fact Tables (FactSales and FactReturns) and Dimension Tables (DimCustomer, DimProduct, DimTerritory, and a custom DimCalendar).

3. DAX Calculations
Developed 15+ custom DAX measures to drive the dashboard's logic, including Time Intelligence for Month-over-Month comparisons and KPI tracking against business targets.

🧠 Challenges & Solutions
Challenge: Syncing Multiple Fact Tables

Solution: Connected both Sales and Returns facts through a shared DimCalendar and DimProduct table. This ensured that any filter applied (e.g., by date or category) updated all visuals across the entire dashboard simultaneously.

Challenge: Managing Complex Product Hierarchies

Solution: Implemented a Snowflake Schema to handle the normalization between products, subcategories, and categories. This allowed for granular drill-down analysis without impacting the dashboard's performance.

Challenge: Visualizing KPI Status Dynamically

Solution: Crafted advanced DAX logic for conditional formatting. I created visual indicators that automatically switch colors (Red/Green) to provide immediate feedback on whether monthly sales and profit targets were achieved.

💡 Key Business Insights
Sales Growth: Identified a significant upward trend in revenue starting in 2021, driven primarily by the Bikes category.

Operational Risk: Discovered that Shorts have the highest return rate (Top Returned Sub-Category), suggesting a need for quality control or sizing adjustments.

Customer Profiling: The Professional occupation segment is the most loyal, contributing the highest number of unique orders.

Market Reach: Successfully mapped global sales across 3 continents, identifying North America as the primary revenue hub.
