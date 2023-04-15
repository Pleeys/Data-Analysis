Earnings-Price Regression Analysis
This program retrieves quarterly earnings data and daily adjusted closing price data for a given stock ticker using the Alpha Vantage API. 
The program then performs a regression analysis on the relationship between the reported EPS, estimated EPS, surprise, 
and surprise percentage of the earnings data and the percentage change in closing price following the earnings release.

Installation
Before running the program, ensure that the required Python packages are installed. These packages are:

pandas
datetime
requests
statsmodels
numpy

You can install these packages using pip:
pip install pandas datetime requests statsmodels numpy

Usage
To use the program, simply run the script in a Python environment. 
Make sure to modify the key and ticker variables at the top of the script to the desired Alpha Vantage API key and stock ticker, respectively.

The program outputs the results of the regression analysis, including the model summary, reset test, and Breusch-Pagan test statistics.
