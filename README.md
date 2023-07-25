# Dynamic Fama French 3 Factor Regression

Building on the initial repository to clean the fama french csv data, this code leverages the yfinance API to run a linear regression. The code allows the user to specify the ticker, start date, and end date. If no start date is provided, then the code will default to the first whole monthly period of the yfinance data. If n end date is provided, the the code will default to the last month of the fama french csv data. 
