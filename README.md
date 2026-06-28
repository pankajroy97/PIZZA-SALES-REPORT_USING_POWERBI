# PIZZA-SALES-REPORT_USING_POWERBI
I developed an interactive Swiggy Pizza Sales Report Dashboard using Power BI, analyzing sales data from January 2015 to December 2015. The project involved multiple stages, including data cleaning, data transformation, and data visualization. 

## Project Objective
The Swiggy Store wants to create an annual sales report for 2015. So that, the owner of the Swiggy store can understand their customers and grow more sales from Jan 2015 to Dec 2015.

Dataset Used– https://github.com/pankajroy97/PIZZA-SALES-REPORT_USING_POWERBI/blob/main/pizza_sales_excel_file.xlsx

## Problem Statement

### KPI Required-

1) Total Revenue  
2) Average Order of Values  
3) Total Pizza Sold  
4) Total Orders  
5) Average Pizza per order

### Here is your data in a clean table format:

| Measure             | DAX Function                               |
| ------------------- | ------------------------------------------ |
| Total Revenue       | `SUM(pizza_sales[total_price])`            |
| Total No of Order   | `DISTINCTCOUNT(pizza_sales[order_id])`     |
| Avg Order Value     | `[Total Revenue] / [Total No of Order]`    |
| Total Pizza Sale    | `SUM(pizza_sales[quantity])`               |
| Avg Pizza Per Order | `[Total Pizza Sale] / [Total No of Order]` |

   
### Chart Required-

* Daily Trends for Total Orders  
* Monthly Trends for Total Orders  
* Percentage of Sales by Pizza Category  
* Percentage of Sales by Pizza Size  
* Total Sales by Pizza Size  
* Top 5 Best Sellers by Revenue, Quantity and Orders  
* Bottom 5 Wrost Sellers by Revenue, Quantity and Orders  


Dashboard - https://github.com/pankajroy97/PIZZA-SALES-REPORT_USING_POWERBI/blob/main/pizza_sale.pdf  
Live Dashboard in Power BI - https://github.com/pankajroy97/PIZZA-SALES-REPORT_USING_POWERBI/blob/main/pizza_sale.pbix
