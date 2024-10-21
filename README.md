# athletic_sales_analysis
Athletic Sales Analysis
This project analyzes athletic product sales across various regions, states, and cities for the years 2020 and 2021. Using Python and Pandas, we explore which retailers, products, and locations performed the best based on total sales and units sold.

Table of Contents
Overview
Project Files
Data Description
Analysis Steps
Results
How to Run the Project
Contributing
Overview
The primary goal of this project is to provide insights into athletic sales by analyzing the data for the years 2020 and 2021. The analysis focuses on identifying top-performing regions, cities, and retailers, as well as the products that generated the most sales.

Project Files
athletic_sales_2020.csv: Contains sales data for the year 2020.
athletic_sales_2021.csv: Contains sales data for the year 2021.
athletic_sales_analysis.ipynb: Jupyter notebook with the code and analysis for this project.
Data Description
The sales data includes the following key columns:

Retailer: The retailer selling the products.
Region: The geographic region of the sale.
State: The state where the sale occurred.
City: The city where the sale occurred.
Product: The product sold.
Units Sold: The number of units sold for the product.
Total Sales: The revenue generated from the sales.
Operating Profit: The profit made from each sale.
Analysis Steps
The analysis performed includes:

Data Import: Loading the data from CSV files into Pandas DataFrames.
Pivot Tables: Creating pivot tables to explore total sales and units sold across regions, states, and cities.
Grouping and Aggregation: Using the groupby function to identify top-performing regions, states, and cities.
Top Performers: Identifying the best retailers, cities, and products based on sales data.
Insights: Highlighting key trends in product sales and geographic performance.
Key Operations:
Pivot Tables: Aggregating sales and units sold data by region, state, and city.
Groupby Operations: Grouping data by retailer and location to determine top performers.
Sorting Results: Sorting results to highlight the regions and retailers with the highest total sales and units sold.
Results
The analysis provided the following insights:

Top Cities by Sales: Cities such as New York, San Francisco, and Miami had the highest total sales.
Top Retailers: Foot Locker and West Gear emerged as leading retailers in terms of units sold and sales revenue.
Regional Trends: The Northeast and West regions consistently outperformed other regions in terms of total sales.