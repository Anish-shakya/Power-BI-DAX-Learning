# 📚🗓️ Welcome to Power BI Dax Learning 🤓📊
- In this git repo, I embark on learning DAX language🚀💻.
- Get ready to explore some fundaments 📝 of Power BI And DAX for data analysis📊🔢📈
- Happy Learning !!🤩📚💻

![Alt text](Assets/power%20bi.jpeg)

| Resources | Description |
| ----------- | ----------- |
|Microsoft|https://learn.microsoft.com/en-us/dax/dax-overview|

## Learning Logs 📑
| Index | Skill Learned |
| ----------- | ----------- |
|[**Introduction**](#introduction)|DAX Overview, Calculated table,columns and Row level security|
|[**Aggregation Functions**](#aggregate-functions)||
|Date and Time Functions||
|Filter Functions||
|Relationship Functions||
|Table Manipulation Functions||
|Time Intelligence Functions||
|DAX Statements||

# Introduction
## DAX Overview
- DAX (Data Analysis Expression) is a formula expression language.
- It is used in Analytics services, Power BI , Power Pivot in Excel.
- DAX formula is used to created calculated columns, calulated tables and custom measures for our analysis

## Measures
- Measure in Power BI are calculations made using DAX formula which is used in analysis and reporting.
- Measure can often be aggregation,caculations or operations in our data.
## Calculated Columns
- Calulated Columns refers to new columns that are created using or appling dax fomula to exiting columns in our dataset.
- Values in calculated columns are static,fixed and store in our dataset
## Calculated Tables
- Calculated tables are tables that are created within Power BI using DAX expressions.
- These tables are not part of our original data source but instead, they are dynamically generated based on DAX expressions we define.
## Row Level Security
- Row-level security (RLS) in Power BI allows us to restrict access to specific rows of data based on the user who is accessing the report or dashboard.

# Aggregate Functions
- Functions that operates on a set of values and return a single value as a result.
- Some of the commonly used Aggregate functions are SUM,AVG,MIN,MAX,COUNT.
- It can be used to summarize a data and perform various types of calculations. 

|Fucntion|Description|
|--------|-----------|
|**APPROXIMATEDISTINCTCOUNT**|Returns an estimated count of unique values in a column.|
|**AVERAGE**|Returns the average (arithmetic mean) of all the numbers in a column.|
|**AVERAGEA**|Returns the average (arithmetic mean) of the values in a column.|
|**AVERAGEX**|Calculates the average (arithmetic mean) of a set of expressions evaluated over a table.|
|**COUNT**|Counts the number of rows in the specified column that contain non-blank values.|
|**COUNTA**|Counts the number of rows in the specified column that contain non-blank values.|
|**COUNTX**|Counts non-blank results when evaluating the result of an expression over a table|
|**COUNTBLANK**|Counts the number of blank cells in a column.|
|**COUNTROWS**|Counts the number of rows in the specified table, or in a table defined by an expression.|
|**COUNTX**|Counts the number of rows that contain a number or an expression that evaluates to a number, when evaluating an expression over a table.|
|**DISTICTCOUNT**|Counts the number of distinct values in a column.|
|**DISTINCTCOUINTNOBLANK**|Counts the number of distinct values in a column.|
|**MAX**|Returns the largest numeric value in a column, or between two scalar expressions.|
|**MAXA**|Returns the largest value in a column.|
|**MAXX**|Evaluates an expression for each row of a table and returns the largest numeric value.|
|**MIN**|Returns the smallest numeric value in a column, or between two scalar expressions.|
|**MINA**|Returns the smallest value in a column, including any logical values and numbers represented as text.|
|**MINX**|Returns the smallest numeric value that results from evaluating an expression for each row of a table.|
|**PRODUCT**|Returns the product of the numbers in a column.|
|**PRODUCTX**|Returns the product of an expression evaluated for each row in a table.|
|**SUM**|Adds all the numbers in a column.|
|**SUMX**|Returns the sum of an expression evaluated for each row in a table.|

## APPROXIMATEDISTINCTCOUNT
- The APPROXIMATEDISTINCTCOUNT function in DAX is used to estimate the number of distinct values in a column or expression.
- It provides an approximate count, which can be significantly faster than calculating the exact distinct count, especially for large datasets.

