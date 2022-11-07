# ETF Analyzer
The goal of this project is within a Jupyter Notebook; using SQL database stores to analyze ETF data. The ETF consists of four stocks: GOST, GS, PYPL, and SQ. 

## Step 1 
Import the necessary libraries and dependencies:
- import numpy as np
- import pandas as pd
- import hvplot.pandas
- import sqlalchemy

Create a temporary SQLite database and populate the database with content from the etf.db seed file


Create an engine to interact with the SQLite database


Confirm that table names are contained in the SQLite database.


## Step 2 
Analyze the PYPL stock using SQL and a SELECT statement to read all the data from the database. Then Use Hvplot to plot the PYPL daily returns, and the PYPL cumulative returns. 

## Step 3 

### Optimize the PYPL stock data from the ETF with SQL queries to optimize the efficiency of accessing data from the database. 

- Access the PYPL closing prices where the price is higer than 200.0

- Using pd.read_sql_query to read the data from the database to a Pandas DataFrame, review the results.

- Using the time and close columns for those dates where the close was higer than 200.0 use a select statement to organize the data.

### Find the top 10 daily returns for PYPL.
 Use SQL to find the top 10 PYOL daily returns,
 - SELECT only the 'time' and 'daily_returns' columns
 - ORDER to sort the results in descending by 'daily_returns'
 - LIMIT to show only the top 10 results.
 
# Analyze the ETF Portfolio
 Build the entire ETF portfolio and evaluate performance. 
 
- Use an inner join to join on the 'time' column in the GDOT table using the syntax GDOT.time. Do the same for the other columns.

- Using pd.read_sql_query to Pandas Dataframe. 

 ## create dataframe that averages the daily_returns for all four assets.
 
 ## Use average daily returns to find cumulative returns. 
 
 ## then plot using HVPLOT 
 
 