# Project-M1-M2

- The objective of this research is to examine the impacts of some macroeconomic factors on the stock market returns of the NASQAD composite index 
We use Two models are conducted in this study: 
- The Ordinary Least Squared (OLS) to test the relationship between the macro variables and the NASDAQ composite index
- The Granger Causality test to examine the relation between individual explanatory variables and the NASDAQ composite index (bidirectional)

workbook name: Module_1_&_2_30092021.ipynb

Steps 
1. Download the data from FRED St Louis and Nasdaq
2. Clean & merge the data
3. Descriptive statistic to understand the dataset

From there we use statsmodels:

4. Run Augmented Dick Fuller test to check for stationarity as it's a time serie
5. Take the first difference if a variable shwos non-stationarity
6. Repeat 4 and 5 until the time series exhibit stationarity
7. Run OLS model / analyses the results 
8. Run Multidirectional Granger Causality and check if there is a bidirectional causality between the dependent variable and independent variables
9. Next steps: Put a lag? How many lag for the Granger causality? More Macro variables? PCA?
