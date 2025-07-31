**Sales-Performance-Analysis-Dashboard_Powerbi-SQL**


An interactive Power BI dashboard designed to empower sales managers and representatives with comprehensive insights into internet sales performance, product trends, customer 
behavior, and budget adherence. This solution transforms raw sales data into actionable visualizations, facilitating data-driven decision-making and improved sales follow-up.

**The Business Challenge**
Previously, sales reporting relied on static reports, making it difficult to gain dynamic insights into sales performance. Sales managers needed a more visual and interactive 
way to understand:

What products are selling best? 

Which clients are contributing most to sales? 

How sales have evolved over time? 

How actual sales compare against the budget? 

Sales representatives also needed tailored views to follow up on their specific customers and products. The challenge was to move from static, inflexible data to a dynamic, 
filterable dashboard that supports both high-level management overview and detailed individual performance tracking.

**Data Journey & Technical Architecture**

Data Sourcing: The core sales performance data (products, customers, sales transactions) was extracted from a SQL database

Data Modeling & Transformation (Power BI): Data was loaded and modeled within Power BI. This involved:Establishing crucial relationships between sales, product, customer, 
and calendar tables. Integrating the budget data from the Excel spreadsheet to enable direct comparison against actual sales performance.

Visualization (Power BI): Microsoft Power BI Desktop was used to create the interactive dashboard, connecting directly to the SQL Database to pull the necessary data and 
visualize it as per the user requirements.

**Dashboard Screenshots & Interaction**

Page 1: Sales Overview
This page provides an executive summary of sales performance, highlighting overall revenue, budget adherence, top product categories, best-performing sales reps, and leading
products.
<img width="977" height="560" alt="image" src="https://github.com/user-attachments/assets/c8703de9-5f66-4816-b1a3-0393d43d09ce" />

Page 2: Customer  Overviewetailed table of sales performance by individual sales representative across each month . This allows sales representatives to quickly identify 
their top-performing customers and track personal sales trends . Additionally, interactive filters for "Customer City" and "Gender" enable granular analysis of customer
demographics and locations, supporting targeted follow-up strategies.

<img width="972" height="555" alt="image" src="https://github.com/user-attachments/assets/48713eb2-bbed-4d2e-8f1d-a18b49b6fbbc" />
