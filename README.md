# Adidas Sales Dashboard
## Problem Statement
This dashboard is designed to provide comprehensive insights into Adidas sales metrics. It helps businesses analyze key metrics such as operating margin, operating profit, and total sales. The goal is to optimize business decisions, improve profitability, and understand the performance of different products, regions, and sales methods.

### Data Used:-
The project involves the following 4 tables:

* Product: Image Url, Product
* Data Sales Adidas: Invoice Date, Location Key, Operating Margin, Operating Profit, Price per Unit, Product, Retailer, Retailer ID, Sales Method, Total Sales, Units Sold
* Location: City, LocationKey, Region, State
* Calendar: Date, Month, Month No., QTR, Year
### Steps :-
#### Step 1: Data Preparation and Transformation
* Product Table Integration: Linked the Product table to the Data Sales Adidas table via the Product column to include product-specific details in the analysis.

* Location Table Integration: Connected the Location table to the Data Sales Adidas table using the Location Key column, enabling geographic analysis of sales data.

* Calendar Table Integration: Integrated the Calendar table with the Data Sales Adidas table using the Invoice Date column to allow time-based analysis.

#### Step 2: Dynamic Measures and Analysis
* DAX Measures: Created various DAX measures to calculate metrics such as Total Sales, Units Sold, Operating Margin, and Operating Profit. These measures provide critical insights into the business's performance.

* Dynamic Analysis: Implemented dynamic analysis capabilities to explore different sales methods, regions, and products, helping to identify trends and opportunities.

#### Step 3: Data Visualizations
* Visual Representation: Created various visualizations, including bar charts, line graphs, and KPIs, to represent key metrics like Total Sales, Units Sold, and Operating Profit.

* Slicers and Filters: Added slicers and filters to enable users to drill down into specific regions, time periods, or product categories, providing a deeper understanding of the sales performance.
