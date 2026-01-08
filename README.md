# Microsoft-stock-price-prediction dataset

This dataset contains historical stock price data of Microsoft Corporation (MSFT) collected over multiple years.
It is designed for time series analysis and stock price prediction using Machine Learning and Deep Learning models.
Each record in the dataset represents one trading day, capturing price movements and trading volume.
The dataset helps understand market trends, price behavior, and future price forecasting.

-------

 ## Dataset Attributes
- Date :Trading date
- Open :Opening price of the stock
- High :Highest price during the day
- Low :Lowest price during the day
- Close :Closing price of the stock
- Adj Close :Adjusted closing price
- Volume :Number of shares traded

------

 ## Objective of the Dataset
The main objective of this dataset is to:

- Analyze historical stock trends
- Predict future stock prices
- Understand price fluctuations over time
- Apply ML/DL techniques for time series forecasting

------

 ## How This Dataset Benefits
- Helps students learn real-world financial data analysis
- Useful for understanding time series forecasting
- Enables implementation of LSTM, RNN, Linear Regression
- Improves skills in data preprocessing and visualization
- Supports academic and research-based ML projects

-------

 ## Working of Stock Price Prediction
**Step 1** : Data Collection
Historical MSFT stock data is collected from financial sources such as Yahoo Finance.
**Step 2** : Data Preprocessing
- Convert date column to datetime format
- Sort data by date
- Handle missing values
-Normalize prices using MinMaxScaler 
**Step 3** : Feature Selection
- The Close price is mainly used as the target variable
- Past prices are used as input features
**Step 4** : Sliding Window Technique
Previous 30–60 days of stock prices are used to predict the next day price
**Step 5** : Model Training
Models commonly used:
- Linear Regression
- LSTM (Long Short-Term Memory)
- Random Forest
- XGBoost
**Step 6** : Prediction
The trained model predicts future MSFT stock prices based on historical patterns.

--------

## Output
The output of this dataset and model includes:

- Predicted stock prices
- Line graph comparing actual vs predicted prices
- Trend visualization over time
- Error metrics such as RMSE and MAE

-------

## Example Output:
 - Stock price prediction graph
 - Next-day or future-day price forecast

 -------
 
 ## Conclusion
The MSFT Stock Price Prediction dataset provides a strong foundation for understanding financial time series forecasting.
By applying machine learning and deep learning models, meaningful insights into stock behavior can be achieved.
Although predictions are not guaranteed due to market volatility, the dataset is highly valuable for educational and analytical purposes.

-------

## Technologies Used
- Python
- Pandas & NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras

-------
