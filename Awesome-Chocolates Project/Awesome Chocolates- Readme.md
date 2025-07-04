Awesome Chocolates Power BI Dashboard
Project Overview
This project presents a comprehensive Power BI dashboard developed for Awesome Chocolates, visualizing key business performance metrics including sales, costs, profit, and shipments across various regions and product categories.
 Objective
To track and analyze monthly business performance and enable decision-makers to:
•	Monitor KPIs like Total Sales, Profit %, and MoM/YoY changes
•	Evaluate salesperson-level contributions and profit margins
•	Analyze shipment trends and box volumes
•	Slice insights by Product Type and Country
Key Features
•	KPI Cards: Showcasing Total Sales ($34.04M), Profit ($20.52M), Shipments (6.1K), and Costs ($13.52M) with MoM comparisons.
•	Region and Product Filters: Buttons allow quick filtering by country and product type.
•	Time Series Line Chart: Monthly trend of sales.
•	Shipment Distribution Histogram: Visualizing shipment volume by size.
•	Salesperson Table:
o	Sales, Profit, Profit %, LBS % with data bars and icons
o	Conditional formatting highlights high and low performers
•	Calendar Table: Supports time intelligence (MoM, YoY, YTD)
DAX Highlights
•	Used DAX to compute:
o	MoM Sales Change %
o	YoY Sales Change %
o	Profit %
o	Total Sales Previous Year, Current Year (YTD)
•	Used VAR, CALCULATE, DATESYTD, SAMEPERIODLASTYEAR, and DIVIDE functions for efficiency and clarity.
Tools & Skills
•	Power BI Desktop
•	DAX (Data Analysis Expressions)
•	Data Modeling with star schema
•	Power Query for data cleaning and calendar table creation
What I Learned
•	Creating dynamic KPIs using time intelligence
•	Building user-friendly dashboards with slicers and icons
•	Optimizing DAX measures with VAR and performance-friendly patterns
Data Source
Synthetic chocolate sales and shipment data modeled in a star schema (Fact: Shipments, Dimensions: Products, People, Calendar, Locations)


