Efficient Home Sales Analysis with PySpark

Project Summary

This project leverages PySpark to process and analyze home sales data efficiently. It explores key trends based on variables like bedrooms, bathrooms, square footage, and view ratings.

Data Processing Workflow

Imported PySpark SQL functions for data manipulation.

Loaded home_sales_revised.csv from an AWS S3 bucket into a DataFrame.

Created a temporary home_sales table for SQL-based queries.

Key Findings

Home Price Trends

Average prices of four-bedroom homes sold per year.

Pricing trends for three-bedroom, three-bathroom homes by year.

Prices of homes with three bedrooms, three bathrooms, two floors, and at least 2,000 sqft.

Impact of View Ratings on Price

Average home price by view rating for properties priced at $350,000 or more.

Measured query execution times.