# Sales Performance Analysis for a Retail Store

## Project Overview
In this project, the objective is to analyze the sales performance of a retail store to uncover insights such as top-selling products, regional performance, and monthly sales trends. The final output is an interactive Power BI dashboard showcasing these insights.

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Tools Used](#tools-used)
- [Data cleaning and preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Analysis](#analysis)
  1. Excel Analysis
  2. SQL Analysis
  3. Power BI Dashboard
- [Results and Insights](#results-and-insights)
- [Recommendations](#recommendations)

## Objectives
The main objectives of this project are:

Perform sales analysis to identify top-selling products, regional performance, and monthly sales trends.
Visualize key insights in an interactive Power BI dashboard.
Provide actionable insights for decision-makers.

## Dataset
Source:   The primary dataset used for this analysis is the “sales_data.csv” file, containing detailed information about each sales made in every region.
Description: The dataset contains information on sales transactions, products, regions,customerID, orderID, unit price, quantity sold and dates.

## Tools Used
- Excel: For initial data exploration, pivot tables, and formula calculations.
- SQL (SQL Server): For in-depth data queries and insights extraction.
- Power BI: For creating an interactive dashboard to visualize findings.


## Data cleaning and preparation 

In the initial data preparation phase, we performed the following task
1. Data loading and inspection
2. Handling duplicates and missing values
3. Data cleaning and formatting

## Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- what product are top sellers?
- what region are top performers?
- what is the overall sales trend?


## Analysis
1. ### Excel Analysis
Goal: Perform initial exploration and calculation of sales metrics.

Steps:
- Used pivot tables to summarize total sales by product, region, and month.
- Calculated average sales per product and total revenue by region using Excel formulas.
- Additional reports created for monthly and quarterly trends.


2. ### SQL Analysis
Goal: Perform in-depth data analysis using SQL queries.

Queries:
- Retrieve the total sales for each product category.
- Find the number of sales transactions in each region.
- Identify the highest-selling product by total sales value.
- Calculate total revenue per product.
- Calculate monthly sales totals for the current year.
- Find the top 5 customers by total purchase amount.
- Calculate the percentage of total sales contributed by each region.
- Identify products with no sales in the last quarter.


3. ### Power BI Dashboard
Goal: Visualize the insights found in Excel and SQL in an interactive format.

Visualizations Included:
- Sales Overview: Summary of total sales, revenue, and key performance indicators.
- Top-Performing Products: Visualization of products with highest sales.
- Regional Breakdown: Sales performance analysis by region.
- Monthly Sales Trends: Line chart of monthly sales across the current year.
   
### Results and Insights
- Total revenue by product,region and month using pivot table
  ![TOTAL REVENUE BY PRODUCT, REGION AND BY MONTH](https://github.com/user-attachments/assets/354235ab-b2db-415b-89b6-83d4787d80ff)


- Top-Selling Products: Shoe is the top selling product in terms of revenue
  ![TOP PERFORMING PRODUCT](https://github.com/user-attachments/assets/cfb8bdd5-b59e-49e6-81ed-5ef007df114b)

- Regional Performance:South is the best performing region in terms of revenue
  ![REGIONAL PERFORMANCE](https://github.com/user-attachments/assets/d8f6040d-e5f0-470e-adb8-bf787109c247)

- Monthly Sales Trends: The best selling month was feburary overtime
![MONTHLY SALES TREND OVERTIME](https://github.com/user-attachments/assets/9ac1265a-3276-4f14-9db6-a5d62305a492)

### Recommendations

Based on the analysis, we recommend the following actions:
- Focus on expanding and promoting Gloves,Jacket and Socks as they are the least performing products
- invest in marketing and promotion in West and North as they are the least performing region
- invest in promotion and marketing especially in the month of April, September and December
