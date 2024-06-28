# Coffee Sales Analysis Project - Power BI
## Project Overview
The Coffee Sales Analysis Project is designed to analyze the sales performance of various coffee products across different store locations. The goal is to identify trends, optimize inventory, and develop marketing strategies to increase revenue and customer satisfaction. This project utilizes Power BI for data visualization and analysis.

## Implementation Steps
Import Data: Load your dataset into Power BI.

Data Transformation: Use Power Query to clean and transform the data.

Create Measures and Calculated Columns: Define necessary DAX measures and calculated columns.

Build Visuals: Create recommended visualizations using Power BI's drag-and-drop interface.

Design and Layout: Arrange the visuals logically and aesthetically on the dashboard.
## Key Metrics to Track
Total Sales Revenue: Sum of (transaction_qty * unit_price)

Number of Transactions: Count of transaction_id

Average Transaction Value: Average of (transaction_qty * unit_price)

Units Sold: Sum of transaction_qty

Sales by Product Category: Sum of (transaction_qty * unit_price) grouped by product_category

Sales by Product Type: Sum of (transaction_qty * unit_price) grouped by product_type

Sales by Store Location: Sum of (transaction_qty * unit_price) grouped by store_location

Peak Sales Hours: Transaction count or revenue by transaction_time

Sales Trends Over Time: Sum of (transaction_qty * unit_price) by transaction_date

## Analysis Questions
Which products are the top sellers?

    By product_category
    
    By product_type
    
    By product_detail

Which store locations have the highest and lowest sales performance?

    By total sales revenue
    
    By units sold
    
    By number of transactions

What are the peak sales hours and days?

    By transaction_time
    
    By transaction_date (day of the week, month, seasonality)

How does the average transaction value vary across different store locations?

What is the sales trend over different time periods (daily, weekly, monthly, quarterly, yearly)?

How does the sales performance of different product categories compare over time?

Are there any seasonal trends or patterns in coffee sales?

How do promotions or special events affect sales?


## KPI Requirements
### Total Sales Analysis
Calculate the total sales for each respective month.

Determine the month-on-month increase or decrease in sales.

Calculate the difference in sales between the selected month and the previous month.

### Total Order Analysis
Calculate the total number of orders for each respective month.

Determine the month-on-month increase or decrease in the number of orders.

Calculate the difference in the number of orders between the selected month and the previous month.

### Total Quantity Sold Analysis
Calculate the total quantity sold for each respective month.

Determine the month-on-month increase or decrease in quantity sold.

Calculate the difference in the quantity sold between the selected month and the previous month.

## Charts Requirements
### Calendar Heat Map
Implement a calendar heat map that dynamically adjusts based on the selected month from the slicer.

Each day on the calendar will be color-coded to represent sales volume, with darker shades indicating higher sales.

Implement tooltips to display detailed metrics (sales, orders, quantity) when hovering over a specific day.

### Sales Analysis by Weekday and Weekends
Segment sales data into weekdays and weekends to analyze performance variations.

Provide insight into whether sales patterns differ significantly between weekdays and weekends.

### Sales Analysis by Store Location
Visualize sales data by different store locations.

Include month-over-month difference metrics based on the selected month in the slicer.

Highlight MoM sales increase or decrease for each store location to identify trends.

This project is aimed at providing comprehensive insights into coffee sales, helping businesses make data-driven decisions to optimize their strategies for better revenue and customer satisfaction.
