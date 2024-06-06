# Retail_Sales_Analytics_Report
Tasks and Steps:

1. Data Integration:

Developed a resilient mechanism to load all sales files into a single Sales fact table.
Ensured the mechanism handles missing files and automatically incorporates new yearly files upon refresh.

2. Data Modeling:

Transformed the Sales fact table to split "Location" into Country and City.
Set proper data types for geo-mapping and date formatting.
Created a unique GeoKey in the Sales and Geography tables.
Cleaned ID columns in SalesRep and SubCategory tables by removing the “ID - ” prefix.
Connected all tables using the Calendar table in the PBIX file.

3. DAX Calculations:

Total Revenue (Product Retail Price * Units).
Total Cost (Product Standard Cost * Units).
 Gross Profit (Total Revenue - Total Cost).
Created a measure for Gross Profit Month-over-Month Growth %.
Created a measure for Average Sales per Day based on actual sales dates.
Calculated Quarterly Business Report (QBR) measures for product performance, including QoQ Growth.
4. Dashboard Assembly:

Designed a one-page dashboard using various visuals to display sales insights.

Deliverables:

A resilient data loading mechanism.
A well-structured data model with necessary transformations and connections.
A set of DAX calculations to provide key performance metrics.
A visually appealing and informative one-page sales dashboard.

This project will enable dynamic and insightful sales reporting, aiding in strategic decision-making
