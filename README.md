📈 Time Series Analysis of Ethereum (ETH/USDT) Market Projections using ARIMA

-----------------------------------------------------------------------------------------------------------------------------------------------------------

🔍 Project Overview

This project explores the use of the ARIMA (AutoRegressive Integrated Moving Average) model to analyze and forecast Ethereum (ETH/USDT) price trends. With cryptocurrency markets being 

highly volatile, accurate time series forecasting is essential for informed decision-making.

The project aims to model historical Ethereum price data and make short-term projections based on statistical patterns in the time series.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🧠 Objective

To build a statistical model that can:

Analyze historical price trends of Ethereum (ETH/USDT).

Perform time series decomposition to identify trend and seasonality.

Forecast future Ethereum prices using ARIMA modeling.

Visualize the accuracy of predictions through graphical evaluations.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📌 Technologies & Tools

Programming Language: Python

Libraries:

pandas, numpy – Data manipulation

matplotlib, seaborn – Visualization

statsmodels – ARIMA modeling

pmdarima – Auto ARIMA for optimal parameter selection


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🗃️ Dataset

Source: Yahoo Fianance

Data: Historical daily prices of Ethereum paired with USDT

Features: Date, Open, High, Low, Close, Volume

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🔧 Methodology

Data Preprocessing:

Handled missing values and formatted datetime

Extracted the closing price for modeling

Exploratory Data Analysis (EDA):

Visualized price trends, rolling statistics

Checked stationarity using Augmented Dickey-Fuller (ADF) test

Modeling:

Applied ARIMA modeling

Used Auto ARIMA to automatically determine (p,d,q) parameters

Trained the model on historical data

Forecasting:

Generated price predictions for future dates

Compared forecasted values against actual prices (if available)

Evaluation:

Visual and statistical evaluation using MSE, RMSE, and AIC/BIC scores

Plotted actual vs predicted values

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Results

The ARIMA model effectively captured the underlying trend in the ETH/USDT price series.

Forecasts showed reasonable accuracy for short-term predictions.

The model provides a solid baseline for further improvements using more advanced techniques like LSTM or Prophet.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🏁 Future Work

Extend the forecasting horizon

Integrate real-time data streaming

Compare ARIMA with machine learning-based models (LSTM, GRU)

Build an interactive dashboard for live updates

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

👩‍💻 Author

Muqadas Ejaz

Machine Learning Engineer | Data Science Enthusiast
LinkedIn (https://www.linkedin.com/in/muqadasejaz/)
