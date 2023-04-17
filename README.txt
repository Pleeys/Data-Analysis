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

It's important to note that the linear regression analysis performed by this program is currently only implemented for the stock ticker "MSFT". If you wish to perform the analysis on a different stock ticker, you will need to modify the data used in the analysis. Specifically, you will need to retrieve the quarterly earnings data and daily adjusted closing price data for the desired stock ticker using the Alpha Vantage API and modify the script to use this new data.

To modify the script for a different stock ticker, you will need to replace the ticker variable at the top of the script with the desired stock ticker. Additionally, you will need to modify the data used in the regression analysis to correspond to the new stock ticker. This may involve changing the format or contents of the data, as well as updating any relevant data processing or filtering steps.
