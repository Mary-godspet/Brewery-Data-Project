# Brewery-Data-Project
This Project is aimed at exploring sales performance, profitability, product performance, and business trend
# Brewery Data project

This project helps the business evaluate its sales performance, identify revenue and profit trends across different West African countries, regions, years and months. 

The project focuses on identifying critical factors influencing sales and profitability, optimizing pricing, production and distribution strategies, and providing data-driven recommendations for business decision making.

# Business Questions
1. which brands generated the highest revenue and profit?
2. which brands have the strongest profit margin?
3. what year generated the highest revenue and profit?
4. which Sales Rep contributed the most profit?
5. which months generated the highest and lowest profit?
6. How has profit changed between 2017 and 2019?
7. which countries and regions performed best?
8. Does higher revenue always translate into higher cost?
9. which product contributed most to overall profitability?
10. what factors could explain changes in profitability overtime?
11. what actions can management take to improve business performance?

# Dataset
# Column
Sales_ID\
Customer_ID\
Sales_Reps\
Brands\
Plant_Cost\
Unit_Price\
Quantity\
Revenue\
Profit\
Total_Cost\
Countries\
Region\
Months\
Years

# Brands
Castle lite\
Budweiser\
Hero\
Trophy\
Eagle Lager\
Grand Malt\
Beta Malt

# Brands Type
Beer\
Malt

# Countries
Nigeria\
Benin\
Ghana\
Togo\
Senegal

# Regions 
Southsouth\
Southeast\
Northwest\
Northeast\
Southwest\
Nothcentral

# Data Cleaning & Preparation
The following steps were taken the clean and prepare the data for analysis.
1. Open power query editor in Excel
2. Load data into power query
3. Transform my data by checking for missing, duplicates, and inconsistent values
4.  Replacing missing sales values with the average sales value, and also removing empty rows and convert data types where necessary
5. Given the total sales and profit, two new columns were created namely; ‘Cost’ and ‘Selling Price’ this will enable us know the percentage of total cost relative to revenue and also the total selling price
6. Given the Plant_Cost and cost columns, a new column "variable cost" was created
7. Given the months column, a new column "Quarter" column was created to help analyse quarterly performance.
8. Load and apply, this will open your data in an Excel workbook
9. Click on the first cell in your already opened workbook, under the column title
10. Creating a calculated field in PivotTable for " Profit Margin"
11. Preparing the data for dashboard analysis from PivotTable

# Analysis Performed
# 1. Sales Performance Analysis
Revenue and Sales quantity were analysed across:\
. Brands\
. Years\
. Months\
. Quarter\
. Countries\
. Regions\
. Sales Representatives

This helps to identify areas that contributed most significantly to overall sales

# 2. Profitability Analysis
This was analysed using:\
. Revenue\
. Total Cost\
. Profit\
. Profit Margin\
. Quantity Sold

The analysis also examined whether high revenue translated into high profitability

# 3. Brand Performance
Brands were compared based on:\
. Revenue\
. Profit\
. Quantity Sold\
. Cost\
. Profit Margin

This helps itdentify high-performing and underperforming brands

# 4. Sales Representative Performance
Sales Reps were eveluated based on their contribution to:\
. Revenue\
. Profit\
. Quantity Sold

The analysis emphasizes profit contribution rather than revenue alone, since the sales representative generating the highest revenue may not necessarily generate the highest profit.

# 5. Trend Analysis
Monthly, Quarterly, and Yearly trends were analysed to identify:\
. Profit growth or decline\
. Peak-performing periods\
. Low-performing periods\
. Changes in revenue and profitability overtime

# Dashboard
Dashboards were designed to provide management with an interactive overview of business performance.

Key metrics include:\
. Total Revenue\
. Total Profit\
. Total Cost\
. Profit Margin\
. Quantity Sold\
. Brand Performance\
. Sales Representative Performance\
. Monthly Profit Trends\
. Yearly Performance

Dashboard Preview

<img width="1836" height="812" alt="Image" src="https://github.com/user-attachments/assets/87af9749-72c0-4940-ae96-afa3b4452940" />\

<img width="1844" height="812" alt="Image" src="https://github.com/user-attachments/assets/f92cab89-3600-4538-9ff9-ccfb36d45a31" />\

<img width="1859" height="828" alt="Image" src="https://github.com/user-attachments/assets/1a2240d7-a703-4491-aa2f-036e462fcc05" />\

<img width="1842" height="825" alt="Image" src="https://github.com/user-attachments/assets/78666f87-e48d-4de9-90a4-eb7683314b9a" />
