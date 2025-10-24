# SQL_RetailSales
Retail Sales Analysis SQL Project
Project Overview
Project Title: Retail Sales Analysis
Level: Beginner
Database: Sql_project_p1

This project is designed to demonstrate SQL skills and techniques typically used by data analysts to explore, clean, and analyze retail sales data. The project involves setting up a retail sales database, performing exploratory data analysis (EDA), and answering specific business questions through SQL queries. This project is ideal for those who are starting their journey in data analysis and want to build a solid foundation in SQL.

Objectives
Set up a retail sales database: Create and populate a retail sales database with the provided sales data.
Data Cleaning: Identify and remove any records with missing or null values.
Exploratory Data Analysis (EDA): Perform basic exploratory data analysis to understand the dataset.
Business Analysis: Use SQL to answer specific business questions and derive insights from the sales data.

Project Structure
1. Database Setup
Database Creation: The project starts by creating a database named Sql_project_p1.
Table Creation: A table named retail_sales_analysis is created to store the sales data. The table structure includes columns for transaction ID, sale date, sale time, customer ID, gender, age, product category, quantity sold, price per unit, cost of goods sold (COGS), and total sale amount.
<img width="972" height="380" alt="image" src="https://github.com/user-attachments/assets/b9a77b10-1773-49c9-ba44-185ebee75c06" />

2. Data Exploration & Cleaning
Record Count: Determine the total number of records in the dataset.
Customer Count: Find out how many unique customers are in the dataset.
Category Count: Identify all unique product categories in the dataset.
Null Value Check: Check for any null values in the dataset and delete records with missing data.
<img width="970" height="829" alt="image" src="https://github.com/user-attachments/assets/1b007cae-e750-4b37-97e1-183d07fc0878" />
<img width="957" height="231" alt="image" src="https://github.com/user-attachments/assets/e665fcce-ca0e-4842-bda6-5b0f2af5cb40" />

3. Data Analysis & Findings
The following SQL queries were developed to answer specific business questions:

1.Write a SQL query to retrieve all columns for sales made on '2022-11-05:
<img width="970" height="65" alt="image" src="https://github.com/user-attachments/assets/d3a36e22-9a5c-4d9e-9809-1556826fa758" />
2.Write a SQL query to retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 4 in the month of Nov-2022:
<img width="971" height="207" alt="image" src="https://github.com/user-attachments/assets/682547b6-64a7-4682-854e-663cc9ebd739" />
3.Write a SQL query to calculate the total sales (total_sale) for each category.:
<img width="968" height="108" alt="image" src="https://github.com/user-attachments/assets/2584b0d2-0e97-4262-bc51-bc030ecbda45" />
4.Write a SQL query to find the average age of customers who purchased items from the 'Beauty' category.:
<img width="975" height="88" alt="image" src="https://github.com/user-attachments/assets/17b942e5-913d-455d-a8c7-72d8d582dd92" />
5.Write a SQL query to find all transactions where the total_sale is greater than 1000.:
<img width="975" height="64" alt="image" src="https://github.com/user-attachments/assets/cbae48ba-8945-4b8c-9c82-f8f9e1d7e5f2" />
6.Write a SQL query to find the total number of transactions (transaction_id) made by each gender in each category.:
<img width="973" height="185" alt="image" src="https://github.com/user-attachments/assets/c57ca0da-c4d9-4331-9274-1367676cc61f" />
7.Write a SQL query to calculate the average sale for each month. Find out best selling month in each year:
<img width="979" height="167" alt="image" src="https://github.com/user-attachments/assets/0579a58a-e62f-4212-8f95-68a37f95e959" />
8.Write a SQL query to find the top 5 customers based on the highest total sales **:
<img width="980" height="167" alt="image" src="https://github.com/user-attachments/assets/47f50ca7-79c3-431d-a1e9-44e108267f8f" />
9.Write a SQL query to find the number of unique customers who purchased items from each category.:
<img width="974" height="90" alt="image" src="https://github.com/user-attachments/assets/30bc2a63-bf48-4441-84af-b86edccbeba0" />
10.Write a SQL query to create each shift and number of orders (Example Morning <12, Afternoon Between 12 & 17, Evening >17):
<img width="972" height="281" alt="image" src="https://github.com/user-attachments/assets/76a9ee37-f867-480c-b9d9-3f7e26885769" />

Findings
Customer Demographics: The dataset includes customers from various age groups, with sales distributed across different categories such as Clothing and Beauty.
High-Value Transactions: Several transactions had a total sale amount greater than 1000, indicating premium purchases.
Sales Trends: Monthly analysis shows variations in sales, helping identify peak seasons.
Customer Insights: The analysis identifies the top-spending customers and the most popular product categories.
Reports
Sales Summary: A detailed report summarizing total sales, customer demographics, and category performance.
Trend Analysis: Insights into sales trends across different months and shifts.
Customer Insights: Reports on top customers and unique customer counts per category.
Conclusion
This project serves as a comprehensive introduction to SQL for data analysts, covering database setup, data cleaning, exploratory data analysis, and business-driven SQL queries. The findings from this project can help drive business decisions by understanding sales patterns, customer behavior, and product performance.

Thank you for your support, and I look forward to connecting with you!












