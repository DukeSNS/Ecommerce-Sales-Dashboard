Ecommerce Sales Dashboard. Power BI
Overview

this project showcases an end to end ecommerce data analysis workflow using power bi. it focuses on cleaning raw transaction data, transforming it into an analysis ready format, and building an interactive dashboard that highlights key business insights.

the goal is to demonstrate practical data cleaning, data modeling, and data visualization skills using a realistic ecommerce dataset.

Dataset

the dataset contains ecommerce transaction level data with the following fields

transaction_id

user_name

age

country

product_category

payment_method

total_revenue

transaction_date

raw data was originally provided in csv format.

Data Cleaning and Transformation

data preparation was done using power bi power query. key steps include

removed duplicate transaction records

trimmed and standardized text fields

handled missing values by replacing blanks with logical defaults

filtered out invalid records such as zero or negative revenue

standardized country names for geographic analysis

created derived columns such as age_group and high_value_order

ensured correct data types for all fields

the raw dataset was preserved and a cleaned version was used for reporting.

Dashboard Features

the final dashboard includes

total revenue, total orders, and average order value summary cards

revenue by product category

revenue by age group

revenue by payment method

geographic revenue distribution using map visuals

monthly revenue trends

interactive slicers for country, product category, age group, and payment method

the dashboard is designed as a single page executive overview.

Tools Used

power bi desktop

power query for data cleaning and transformation

dax for calculated measures

File Structure

raw data. ecommerce_transactions_raw.csv

cleaned data. ecommerce_transactions_clean.xlsx

power bi report. ecommerce_sales_dashboard.pbix

Notes

this project was created for portfolio purposes and focuses on clarity, usability, and real world data handling practices.