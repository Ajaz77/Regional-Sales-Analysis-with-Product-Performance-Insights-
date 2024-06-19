# Regional-Sales-Analysis-with-Product-Performance-Insights-
Analyzes 2022-2023 sales data using Python for downloading, preprocessing, and cleaning, and M SQL Server for analysis. Identifies top 5 products by region, top 10 revenue-generating products overall, compares month-over-month growth, highlights highest sales category, and subcategory with highest profit growth.
This project analyzes retail orders data using Python and SQL. The dataset contains information about orders, including order date, ship mode, segment, country, city, state, postal code, region, category, subcategory, product ID, cost price, list price, quantity, discount percent, discount, sale price, and profit.

Key Steps:

Data Preparation:

Preprocessing the dataset to handle missing values, convert data types, and derive new columns such as discount, sale price, and profit.

Exploratory Data Analysis (EDA):

Exploring the dataset to understand its structure and characteristics.
Analyzing sales trends, top-selling products, revenue generation, month-over-month sales growth, and category/subcategory insights.

SQL Database Integration:

Establishing a connection to a SQL Server database using PyODBC and SQLAlchemy.
Inserting the preprocessed DataFrame into the database as a table named df_orders.

SQL Queries and Analysis:

Writing SQL queries to perform various analyses, such as identifying top-selling products in each region, comparing sales growth between different periods, and determining the highest-growth subcategory by profit.

Conclusion:

Summarizing key findings and insights derived from the data analysis process.
Highlighting the project's significance in making data-driven decisions for retail business strategies.
Technologies Used: Python, SQL, Pandas, PyODBC, SQLAlchemy

Dataset Source: Retail Orders Dataset on Kaggle

License: CC0-1.0

