SQL Data Cleaning – Layoffs Dataset
This project shows the steps I took to clean a real-world layoffs dataset using SQL.

Files
layoffs.csv: Raw dataset

layoffs_data_cleaning.sql: SQL script with full cleaning process

Cleaning Steps
Created a staging table to protect raw data

Removed duplicates using ROW_NUMBER()

Standardized company, industry, and country values

Converted string dates to proper DATE format

Replaced empty strings with NULL

Filled missing industry values by matching company names

Deleted rows with no layoff data

Dropped the row_num column after cleanup

Tools
MySQL

SQL Window Functions

String and Date functions

Purpose
Practice real-world data cleaning using SQL
Make data ready for analysis