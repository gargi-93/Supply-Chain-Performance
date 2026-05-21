Supply Chain Performance Analysis
This project presents an end-to-end Power BI dashboard designed to analyze supply chain performance across profitability, supplier risk, carrier efficiency, and inventory stockout exposure. The goal is to convert operational data into business insights that support faster and more informed decision-making.

Project Objective
The dashboard was built to evaluate supply chain performance through a business-focused analytics lens. It helps answer key operational questions such as:

•	Which product categories generate the highest revenue and gross profit?

•	Which suppliers carry the highest risk based on defect rate and lead time?

•	Which shipping carrier performs most efficiently?

•	Which products are at risk of stockout based on current inventory and incoming orders?

•	How do core performance metrics vary across locations?

Tools & Technologies
•	Power BI for dashboard design and interactive reporting

•	Power Query for data preparation and transformation

•	DAX for KPI calculations and custom business measures

•	Excel / CSV datasets as source data

Dashboard Structure
1. Executive Summary
This page provides a high-level overview of overall supply chain and business performance.

•	KPIs included:

•	Total Revenue

•	Gross Profit

•	Contribution Margin

•	Total Cost

•	Average Defect Rate

•	Stockout Alert

•	Visuals included:

•	Total Revenue by Product Type

•	Gross Profit by Product Type

•	Total Cost by Product Type

•	Inventory Stockout Risk table

•	Location slicer for interactive filtering

2. Supplier Analysis
This page focuses on supplier quality and operational reliability.

Visuals included:

Average Defect Rate by Supplier

Average Lead Time by Supplier

Supplier Risk Score by Supplier

A custom Supplier Risk Score was created by combining normalized defect rate and normalized lead time into one weighted measure:


Supplier Risk Score =
0.5 * [Normalized Defect Score]
+ 0.5 * [Normalized Lead Time Score]
This makes it easier to compare suppliers through a single risk metric instead of reviewing separate performance indicators.

3. Carrier Performance
This page evaluates shipping carriers based on operational efficiency.

Visuals included:

Carrier Efficiency Score by Shipping Carrier

This view helps identify which carriers are performing better and where logistics efficiency may need improvement.

Key Measures Created
The dashboard includes several calculated measures to support business analysis, including:

Total Revenue

Gross Profit

Contribution Margin

Total Cost

Average Defect Rate

Avg Supplier Lead Time

Normalized Defect Score

Normalized Lead Time Score

Supplier Risk Score

Carrier Efficiency Score

Inventory Gap

Stockout Alert

Business Value
This dashboard supports business users by helping them:

Monitor profitability and cost drivers across product categories

Detect supplier-related operational risks early

Evaluate carrier performance for logistics optimization

Track stockout exposure and inventory gaps

Compare business performance across locations

Key Insights Supported
The report enables analysis of questions such as:

Which suppliers should be monitored more closely due to higher defect rates and lead times?

Which carrier is the most efficient based on the defined score?

Which product categories contribute the most to revenue and profit?

Which products are facing the highest stockout risk?

Where are operational inefficiencies driving cost upward?

Files in This Repository
Supply chain.pbix — Power BI dashboard file
README.md — project documentation

How to Use
Download the .pbix file from this repository.

Open the file in Power BI Desktop.

Refresh data sources if required.

Use slicers and filters to explore performance by location, supplier, carrier, and product category.

Skills Demonstrated
This project demonstrates practical skills in:

Data cleaning and transformation

Business KPI development

DAX measure creation

Dashboard storytelling

Supply chain and operations analytics

Risk-based reporting

Future Improvements
Potential next enhancements include:

Time-series trend analysis across months or quarters

Drill-through pages for supplier and carrier details

Forecasting for demand and stockout risk

Interactive tooltip pages for KPI explanations

Publishing to Power BI Service for cloud-based sharing

Author
Gargi Pathak
Aspiring Data Analyst with a focus on Power BI, DAX, business intelligence, and analytics-driven decision-making.
