# PowerBI Financial Report Project

## Overview
This PowerBI project is designed to provide insightful financial analysis and reporting based on the AdventureWorks2022 database. It aims to deliver comprehensive insights into sales, expenses, and the future financial state of the imaginary company.

## Dashboard 
![Financial Dashboard](/Dashboard/PowerBi_1.png)

- **Total Sales**: Measures the overall revenue generated from product sales. This KPI is for evaluating the company's growth and market reach.
- **Total Profit**: Indicates the net profitability after subtracting total expenses from total sales. 
- **Total Expenses**: Tracks all costs of producing the sold items. 
- **Units Sold**: Represents the total quantity of products sold. This metric is for understanding product demand.
- **Sales by Country**: Provides a geographical breakdown of sales, offering insights into market performance across different regions and helping tailor regional marketing strategies.
- **Product Sales**: Breaks down sales by product category to identify which items are performing well, which can inform product development and marketing investments.
- **Units Sold Forecast**: Uses historical sales data to predict future sales volumes. This forecast aids in strategic planning, inventory management, and production scheduling.
- **Sales Forecast**: Projects future sales revenue based on current trends and historical data, which is for financial planning and forecasting growth trajectories.

## Additional Features
### Ability to change the year and specific group
![Financial Dashboard](/Dashboard/PowerBi_3.png)

### Responsive dashboard showcasing changes compared to last year
![Financial Dashboard](/Dashboard/PowerBi_4.png)

### Drill down possibility on Product Sales
![Financial Dashboard](/Dashboard/PowerBi_5.png)

## Making The Project

### Getting the data
By using SSMS, analyzed what tables and columns to use in the dashboard. Decided to go forward with more of a Financial analysis so used more tables from Sales and Production


### Implementing the relationships between different tables
![Financial Dashboard](/Dashboard/PowerBi_relationship.png)

### Adding a new column for specifying the product type
For the reason of the default product types only having 4 different alternatives and not giving enough insight on the sales performance between different products, added a column that specifies products to more appropriate categories. Made it in Production.Product table and named the column ProductCategory.


## Data Source
- The data for this project is sourced from the AdventureWorks2022 database.
- Link: https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms

