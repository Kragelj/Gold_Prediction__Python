# Gold Price Prediction (ARIMA Model)
A Time Series Forecasting Approach

## Introduction
Gold has always been a valuable asset, prized for its stability in financial markets. However, predicting its price is challenging due to its susceptibility to economic changes, geopolitical events, and market dynamics.
<br>This project applies ARIMA (AutoRegressive Integrated Moving Average)—a widely used statistical time series model—to forecast future gold prices based on historical data, providing insights into market trends and predictive modeling.

### About the Dataset
The dataset contains daily gold prices collected from Investing.com website, spanning from 2010 to 2015. This time series captures fluctuations in gold prices over 15 years, offering a strong foundation for forecasting.

### Project Objectives
- Analyzing historical gold price trends to understand market behavior
- Implementing ARIMA forecasting to predict future price movements
- Evaluate ARIMA model performance through train/test validation 
- Refining time series techniques using exploratory data analysis

### Python Libraries Used
- Pandas – Data manipulation & structured analysis
- NumPy – Mathematical computations & transformations
- Seaborn & Matplotlib – Data visualization (visualizing trends & patterns)
- Scikit-learn – Data preprocessing & analysis
- Statsmodels – Time series modeling (ARIMA, Seasonal Decomposition)
- pmdarima – Automated ARIMA parameter selection

### Data Processing
- Data Exploration – inspecting dataset structure
- Data Cleaning & Preprocessing – handling data format, numeric conversion, dropping unnecessary columns

### Exploratory Data Analysis (EDA)
- Observing price trends, adding 90-day moving average to highlight trend direction
- Seasonal Decomposition - separating trend, seasonality, and residual noise for deeper insights and better pattern identification

### Using ARIMA model Forcasting
- Checking for stationarity (Augmented Dickey-Fuller Test)
- Differencing to ensure stationarity - removing trend components, allowing ARIMA to function effectively
- Identifying ARIMA parameters (p, d, q) - using ACF & PACF plots
- Using auto_arima() for optional prameter selection - ensuring the best fit
- Splitting data (Train/Test) for model validation
- Forcasting gold prices

**Evaluating Model Performance**
<br>We assess forecasting accuracy using:
<br>Mean Absolute Percentage Error (MAPE),
<br>Mean Absolute Error (MAE),
<br>Mean Squared Error (MSE),
<br>Root Mean Squared Error (RMSE),
<br>and R-squared (R2) Coefficient of Determination.

### Key Takeaways
Gold price depends on more than historical trends, therefor traditional time series methods may not be ideal for financial asset prediction. Gold price forecasting is a challenging task, requiring advanced techniques beyond ARIMA and different macroeconomic indicators for better forecasting.

