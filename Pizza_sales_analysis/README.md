# Pizza Sales Analysis

This project analyzes pizza sales data using SQL, Power BI, and Excel to derive insights into the performance of different pizza categories, sales trends, and key performance indicators (KPIs). 

## Tools and Technologies Used
1. **SQL**: Structured Query Language was used to query the pizza sales data, calculating key metrics such as total revenue, number of pizzas sold, and sales trends.
2. **Power BI**: This tool was used to visualize the data and present findings in an interactive dashboard.
3. **Excel**: Used for data manipulation and initial exploratory analysis.

## Datasets
- **pizza_sales.csv**: This dataset contains detailed information about pizza sales, including order IDs, pizza names, categories, sizes, quantities, and prices.(available on kaggle)

## SQL Queries Overview
You can review SQl Queries in the attachted file [SQL queries](https://github.com/Ribhu01/DS_Projects/blob/main/Pizza_sales_analysis/PIZZA%20SALES%20SQL%20QUERIES.docx)

## Steps covered
* Imported raw sales data into SQL server using import task option in SSMS and Sql to analyze the data in SSMS
* Imported data from SQL server into Power BI for creating dashboard
* Used Power Query editor to clean and transform the data
* Apply all necessary cleaning steps, such as removing duplicates, renaming columns, and changing data types
* Load and Apply the cleaned data into Power BI
* Design the dashboard layout
* Created a measures to aggregate and display the data using    Dax functions
* Use Visulizations for charts and slicers for filter dashboard
* Now, Add Sales Dashboard
* Add Pizza category and order date as Slicer and add some informative KPI
* Add Card chart, Area chart, Pie chart, Bar chart, Map etc
* Add buttons to create an another page with Visuals for sales summary of pizza sales

## Insights
* Busiest Days & Months: Orders are highest on weekends, specifically on Fridays and Saturdays. The months of July and January see the maximum orders.
* Sales Performance by Category and Size: Classic category contributes the most to total sales and orders, and large-sized pizzas are the most popular.
* Peak sales occur during the SECOND QUARTER of the year and JULY being the month with highest sale
* Best seller - The Thai Chicken Pizza generates the most revenue, while the Classic Deluxe pizza tops the list for the number of pizzas sold and total orders.
* The Brie Carre Pizza is the worst performer across all these metrics.
* LARGE-sized pizzas are the most popular choice among customers, representing about 46% of total sales, followed by MEDIUM (30%) and SMALL (22%) sizes.
*  Percentage share of total sales by all four Pizza Categories are almost same with CLASSIC category being the highest followed by SUPREME category.
Creating this dashboard was a valuable learning experience, especially in terms of mastering the use of parameters in Power BI. I’m looking forward to applying these insights to future projects, and I’m excited about the possibilities this opens up for more interactive and user-friendly data visualizations.

## Power BI Dashboard

you can checkout and interact with my dashboard  here

### snapshots of the dashboard
 * overall sales
![Salesreport(home)](https://github.com/user-attachments/assets/44d741d5-4b87-4dd5-ab6c-1d6b41e82744)

* Summmary of performance based on revenue,quantity and order
![Salesreport(summary)](https://github.com/user-attachments/assets/688c4b73-9e84-42be-a73f-c24c36b3af22)

