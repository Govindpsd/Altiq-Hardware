# AtliQ Hardware Sales Project

## Overview
The AtliQ Hardware Sales project involves comprehensive data analysis and visualization to understand the sales performance of AtliQ Hardware. The project was conducted in two phases: data analysis using MySQL and data visualization using Tableau.

## Project Phases

### Phase 1: Data Analysis with MySQL
- **Data Extraction**: Extracted sales data from the database.
- **Data Cleaning**: Performed data cleaning and transformation to ensure data quality.
- **Star Schema Creation**: Designed a star schema with a Transaction fact table and relevant dimension tables.

### Phase 2: Data Visualization with Tableau
- **Data Import**: Imported the cleaned data from MySQL into Tableau.
- **Calculated Columns**: Created a calculated column for Normalized Amount, converting sales from USD to INR.
- **Filtering Data**: Removed negative sales values using filters.
- **Sheet Creation**: Developed various sheets to visualize different aspects of the data.
- **Dashboard Creation**: Combined the sheets into a comprehensive dashboard.

## Dashboard Components
The final Tableau dashboard includes the following components:
- **Total Revenue**: Visual representation of the total revenue generated.
- **Sales Quantities**: Analysis of the total sales quantities.
- **Revenue by Market**: Breakdown of revenue by different markets.
- **Sales Quantities by Market**: Visualization of sales quantities segmented by market.
- **Revenue by Year**: Yearly revenue trends.
- **Top 5 Customers**: List of the top 5 customers based on revenue.
- **Top 5 Products**: List of the top 5 products based on sales.

## Usage
1. Download the `.twbx` file containing the Tableau workbook.
2. Open the file in Tableau Desktop to explore the visualizations and dashboard.

## Visualizations
Here are some snapshots of the visualizations included in the dashboard:

![Total Revenue](https://github.com/Govindpsd/Altiq-Hardware/blob/main/TotalRevenue.png)
![Sales Quantities](images/sales_quantities.png)
![Revenue by Market](images/revenue_by_market.png)
![Sales Quantities by Market](images/sales_quantities_by_market.png)
![Revenue by Year](images/revenue_by_year.png)
![Top 5 Customers](images/top_5_customers.png)
![Top 5 Products](images/top_5_products.png)

## Data
- `AtliQ_Hardware_Sales.twbx`: Packaged Tableau workbook containing the visualizations and data.
- `db_dump.sql`: sql file containing the raw data used  in the project.


## Contact
- Govind Parshad
- pgovind887@gmail.com
