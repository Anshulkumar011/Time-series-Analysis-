# Time-series-Analysis-
Apple Stock Price Prediction

<h1 align="center">Hi 👋, I'm Anshul kumar</h1>
<h3 align="center">Forecasting Apple Stock Prices using Machine Learning Techniques</h3>

# Problem Statement
Stock prices are influenced by time-dependent trends, seasonal effects, and external factors. Accurately forecasting stock prices like Apple Inc. (AAPL) is crucial for financial planning and investment decisions. This project focuses on leveraging ARIMAX and SARIMAX models to predict AAPL's closing stock prices using both historical data and external features.

# Objective

•	Perform in-depth time series analysis on AAPL stock data

•	Apply ARIMAX and SARIMAX models to capture both trend, seasonality, and external influences

•	Forecast future prices with high accuracy

•	Evaluate model performance and visualize results


#  Dataset

•	Source: Yahoo Finance

•	Stock: Apple Inc. (AAPL)

•	Fields Used: Date, Open, High, Low, Close, Volume

•	External/Exogenous Variables: (if used) NASDAQ Index, Economic Indicators, etc.


# Models Used

1.	ARIMAX (AutoRegressive Integrated Moving Average with eXogenous variables)
   
o	Captures autocorrelation, trend, and influence of external variables (like market index).

2.	SARIMAX (Seasonal ARIMAX)

o	Extends ARIMAX by incorporating seasonal patterns, e.g., quarterly or monthly cycles in stock data.
Both models are tuned for best performance using AIC/BIC minimization and diagnostic plots (ACF, PACF, residuals).

# Tools & Libraries

•	Python

•	Pandas, NumPy

•	Matplotlib, Seaborn

•	statsmodels

•	yfinance

•	sklearn (for evaluation metrics)


# Time Series Workflow

1.	Data Collection

o	Fetched Apple stock data using yfinance

2.	Preprocessing
   
o	Converted dates, handled missing values

o	Log transformation and differencing for stationarity

o	Created lag features and rolling averages

3.	Stationarity Check
   
o	Used ADF (Augmented Dickey-Fuller) test

o	Differenced data to make series stationary

4.	Model Selection
	
o	ACF & PACF plots used to identify optimal (p,d,q) and (P,D,Q,s)

o	Grid search for best hyperparameters 

5.	Model Training
   
o	Fitted ARIMAX and SARIMAX on training data

o	Included exogenous variables if available

6.	Forecasting & Prediction
    
o	Forecasted stock price for future days

o	Compared predictions vs actual prices


Evaluation Metrics

•	MAE (Mean Absolute Error)

•	RMSE (Root Mean Squared Error)

•	MAPE (Mean Absolute Percentage Error)

•	R² Score (optional for regression context)

# Achieved high accuracy with RMSE as low as X.XX and strong model diagnostics.


# Results

•	The SARIMAX model effectively captured weekly and monthly seasonality in Apple's stock.

•	The ARIMAX model leveraged external indicators to enhance short-term prediction accuracy.

•	Plots of actual vs predicted closing prices showed very close alignment.


![Screenshot 2025-02-06 133538](https://github.com/user-attachments/assets/647dacaa-ea53-481f-b860-1eb05f2c75be)



<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/anshul kumar" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="anshul kumar" height="30" width="40" /></a>
<a href="https://kaggle.com/anshul kumar" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="anshul kumar" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> </p>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=anshulkumar011&show_icons=true&locale=en&layout=compact" alt="anshulkumar011" /></p>
