# Unit 5 - Financial-Planning


![Financial Panner](financial-planner.png)

## About 

This notebook was created as a financial planner used to help individuals asses their personal finance and to forecaset a reasonable retirmentent plan based on a combination of various assests. 

With the financial planner, the cryptocurreny and stock data found in this notebook are pulled from the alternative api and Alpaca api respectively. This information is compiled and formulated into a savings account and then compared against an emergency fund. If you're savings are greater than your emergency amount, you can be considered to be in good finacial health. 

The second portion of the notebook was designed to model potential retirement plans. We take two assets (SPY and AGG) and create a portfolio using real time data extracted from Alpaca. This data is then ran through the Monte Carlo Simulation script  (MCForecasttools.py). With that we are able to forecast potential expected returns. This is broken down even further by providing a 95% cofindence interval for the likely outcomes. Additionally the forecast can be adjusted so that you can determine the amount necessary for an earlier retirement.  This can be done making changes to the weights of the assets within your portfolio,  as well as by inputting a different inital investment. 




