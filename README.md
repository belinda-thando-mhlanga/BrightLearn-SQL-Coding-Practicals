# BrightLearn-SQL-Coding-Practicals
Practical Exercises that I completed while learning SQL with BrightLearn Academy
These are my SQL solutions covering fundamental queries, JOINs, and advanced NULL handling concepts.
Developed using Snowflake SQL syntax with retail and shopping datasets.

## Setup and Environment
I used Snowflake for Coding and developing my solutions 

## Datasets Used for all the 3 practicals
- retail_sales_dataset.csv
- shoping_trends.csv
- orders_large.csv, products_large.csv, customers_large.csv

## Practical 1: SQL Fundamentals
Focus: Basic SQL syntax using retail_sales_dataset

- SELECT and SELECT DISTINCT for retrieving and identifying unique data
- WHERE clause for filtering with comparison operators (>, BETWEEN, IN, NOT, >=)
- Aggregate functions: COUNT, AVG, SUM, MAX, MIN
- GROUP BY for grouping results by categories
- HAVING clause for filtering aggregated results
- CASE statements for conditional logic and data categorization

## Practical 2: SQL JOINs
Focus: Different JOIN types using orders, products, and customers datasets

- INNER JOIN: Matching records in both tables
- LEFT JOIN: All records from left table with matches from right
- RIGHT JOIN: All records from right table with matches from left
- FULL OUTER JOIN: All records from both tables, showing NULLs for non-matches

## Practical 3: Advanced SQL - NULL Functions
Focus: NULL handling and advanced filtering using shoping_trends dataset

- NULL filtering with IS NULL and IS NOT NULL
- NULL replacement using IFNULL and COALESCE
- Advanced aggregation with NULL value counts
- Conditional aggregation and grouping with HAVING
- CASE statements with NULL handling log
