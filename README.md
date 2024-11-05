# Walmart-Sales-Analysis


## Project Overview
This project delves into Walmart's sales data to pinpoint high-performing stores and products, analyze sales trends, and explore customer purchasing patterns. The primary aim is to uncover insights that could enhance and refine Walmart’s sales strategies. The dataset originates from the Kaggle Walmart Sales Forecasting Competition.

In this competition, participants are provided with historical sales records for 45 Walmart stores located in various regions. Each store is comprised of multiple departments, and participants are challenged to predict sales for each department. The dataset also includes data on special markdown events associated with holidays, which have been shown to influence sales; however, determining which departments are impacted, and to what degree, poses an additional challenge. Source

## Project Objectives
The main objective is to extract insights from Walmart’s sales data to better understand factors influencing sales across various stores.

## Dataset Overview
The dataset, sourced from the Kaggle Walmart Sales Forecasting Competition, contains sales transaction data for three Walmart branches located in Mandalay, Yangon, and Naypyitaw. It includes 17 columns and 1,000 rows.

## Analysis Plan
1. Product Analysis

Analyze product data to understand the various product categories, identify top-performing categories, and determine which products may require further improvement.

2. Sales Analysis

This analysis will uncover sales trends across different products, helping to gauge the success of existing sales strategies and identify areas for potential optimization.

3. Customer Analysis

This analysis will segment customers, reveal purchasing trends, and assess the profitability of each customer segment.

## Methodology
Data Cleaning: The first step involves reviewing the dataset to identify and handle any missing or NULL values.

Establish a database
Create a table and load the dataset
Identify columns with null values. The table setup includes NOT NULL constraints on each field, so rows with null values are automatically filtered out.
Feature Engineering: This process generates new columns to provide additional insights.

Add a time_of_day column to categorize transactions into Morning, Afternoon, and Evening, helping us determine which parts of the day see the most sales.
Create a day_name column to capture the day of the week for each transaction, providing insights into the busiest days for each branch.
Add a month_name column to identify the months with the highest sales and profit.
Exploratory Data Analysis (EDA): The EDA process addresses the project's objectives by extracting insights from the data.


## Business Questions To Answer

### Generic Question

1. How many unique cities does the data have?
2. In which city is each branch?

### Product

1. How many unique product lines does the data have?
2. What is the most common payment method?
3. What is the most selling product line?
4. What is the total revenue by month?
5. What month had the largest COGS?
6. What product line had the largest revenue?
5. What is the city with the largest revenue?
6. What product line had the largest VAT?
7. Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
8. Which branch sold more products than average product sold?
9. What is the most common product line by gender?
12. What is the average rating of each product line?

### Sales

1. Number of sales made in each time of the day per weekday
2. Which of the customer types brings the most revenue?
3. Which city has the largest tax percent/ VAT (**Value Added Tax**)?
4. Which customer type pays the most in VAT?

### Customer

1. How many unique customer types does the data have?
2. How many unique payment methods does the data have?
3. What is the most common customer type?
4. Which customer type buys the most?
5. What is the gender of most of the customers?
6. What is the gender distribution per branch?
7. Which time of the day do customers give most ratings?
8. Which time of the day do customers give most ratings per branch?
9. Which day fo the week has the best avg ratings?
10. Which day of the week has the best average ratings per branch?
