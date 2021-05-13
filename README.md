# Sales Insights Project

## Overview

This projects basically consists of a dataset which shows the sales of a company over the past 4 years. The dataset includes various measures like transactions of the products, market codes, names of markets, total revenue, etc. This project mainly focuses on the sales, company did in the past four years all over INDIA. Also, the data has been fetched from Mysql server into Tableau. So, after fetching data and after analysis and visualisation using Tableau, what will be the overall output is shown via dashboard.

The overall outcomem consists of:
  - What will be the companies revenue by quantity and sales from year 2017 - 2020?
  - What will be the revenue of whole year ?
  - What will be the reveneue differnt states throughout the year?
  - Top 5 customers of the company by sales.
  - Top 5 products by sales.


## Data Source and Database Schema

The data source used in this projects consists of five different file named:
  
  1. transactions.csv
  2. customers.csv
  3. products.csv
  4. markets.csv
  5. date.csv

The database schema used in this project includes: All the four files named customers.csv, products.csv, markets.csv, date.csv performed an inner join with the trasactions.csv file as most of the operations can be done with the transactions.csv file.
  
 
## Database Schema

![Databse Schema](https://user-images.githubusercontent.com/49076315/118117391-301f6000-b409-11eb-8003-130ca0470293.JPG)


## Data Cleaning Process

In this Data cleaning process the data which was fetched from the Mysql server was cleaned before analyzing as there were various values which were negative which were not needed as well as various market names which were of foreign countries which were of no need as we are creating the sales insight for INDIA only. Also, some of the currencies were in Dollars so to convert it into Indian rupees was must. Some of the data cleaning process was done manually while most of the cleaning was done with the help of DATA INTERPRETER method of Tableau. Now, the data was in proper format and the data was ready for analyzing.


## Analyzing Process.

In this analyzing process the data which was cleaned was then analysed to find various insights, patterns from the formatted data. After analyzing the data and creating insights from the formatted data the visualisation process was done.


## Data Visualisation

This process is used for creating visualisations from the analyzed data and using those visuals to create dashboard using various charts like bar chart, line chart etc and various other functionalities.

## Dashboard (Final Outcome)

![Dashboard](https://user-images.githubusercontent.com/49076315/118102337-4bcd3b00-b3f6-11eb-9aae-c3c399d8f796.JPG)

This dashboard consists of various information regarding the visualised data:

  - Total Revenue (Total revenue of the 4 years as well as the value was dynamic which was changing as per years and months).
  - Total Sales (Total sales which consists of the sales of 4 years as well as the value was dynamic changing as per years and months).
  - Revenue by State (Bar Chart) representing revenue of different states as per years and months.
  - Revenue by Sales (Bar Chart) representing revenue of sales of different states as per years and months.
  - Revenue by Year (Line chart) representing revenue of different years.
  - Top 5 customers (Bar Chart) representing the top 5 customers by revenue all over INDIA.
  - Top 5 products (Bar Chart) representing the top 5 products by revenue all over INDIA.
