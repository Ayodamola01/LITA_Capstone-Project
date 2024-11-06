# LITA_Capstone-Project
## Introduction to Data Analysis 
As a newbie to the Tech world, precisely Data Analysis it is mandatory to learn the essential skills needed to analyse data. This repository on LITA Capstone Project showcase the fantastic thing you can do with Excel, SQL and Power Bi.

## Scope
- Showcase basic data analysis concepts learnt.
- Practice using Excel for data analysis.
- Learn basic SQL queries.
- Create a simple Power BI dashboard.

## Requirements 
To get started, It is essential to have a good laptop have all the app necessary installed. Microsoft Excel, SQL (My SQL, ProsgreSQL and Power Bi. are to be installed for effectively learning.

## Use of the Apps
- Microsoft Excel [Download here](https://www.microsoft.com)
  - For data organization.
  - For data analysis.
  - For visualization.
  
- Microsoft SQL Server Management [Download here](https://www.microsoft.com)
  - For data extraction.
  - For data manipulation.
  - For querying.
  
- Power BI [Download here](https://www.microsoft.com)
  - For building interactive dashboards and reports.
  - For visualization
    
- Github is for portfolio building.
  

## Overview of Capstone project
- This is a project given by the facilitator to put to test all that has been taught in the class.
- Therefore, this repository is to showcase the use of the apps(tools) listed above in achieving the instruction on the dataset.
- The project is into 2 phases, Sales data and Customer data. Both are to be thoroughly analysed.

- Here are the instructions given on Sales Data and Customer Data respectively
  
** Project 1: Sales Performance Analysis for a Retail Store**
Summary: In this project, you are tasked with analyzing the sales performance of a retail store.
You will need to explore sales data to uncover key insights such as top-selling products, regional
performance, and monthly sales trends. The goal is to produce an interactive Power BI
dashboard that highlights these findings.
Instructions:
### Excel:
- Initial exploration of the sales data. Use pivot tables to summarize
    - total sales by product.
    - region and month.
    - Use Excel formulas to calculate metrics such as average sales per product and total revenue by region.
    - Create any other interesting report
### SQL:
Hint – You need to load the dataset into your SQL Server environment to write and
validate your queries.
    - retrieve the total sales for each product category.
    - find the number of sales transactions in each region.
    - find the highest-selling product by total sales value.
    - calculate total revenue per product.
    - calculate monthly sales totals for the current year.
    - find the top 5 customers by total purchase amount.
    - calculate the percentage of total sales contributed by each region.
    - identify products with no sales in the last quarter.
### Power BI:
- Create a dashboard that visualizes the insights found in Excel and SQL. 
  -  sales overview
  -  top-performing products
  -  regional breakdowns.

- Here are the analysis to the instruction given. Starting with SQL.
  select*from [Cleaned Sales data]
select product, sum(quantity*unitprice) as totalsales 
from [Cleaned Sales data]
group by Product
  
''' SQL
Select * from [Cleaned sales data]
select product, sum(quantity*unitprice) as totalsales
from [cleaned sales data]
group by product
'''

