<h1 align="center">
    Predict Stock
</h1>

This repository is a testament to my learning journey

The project revolves around leveraging a supervised Machine Learning (ML) model to forecast the forthcoming performance of ACB Bank stocks. Through this endeavor, I explored methods like Moving Average (MA) to calculate average series over specific periods and implemented LSTM to predict future stock behavior.

## About Dataset

The dataset comprises Stock Prices and Volume data for the 30 companies listed in the VN30 Index in Vietnam.

The dataset spans a period of ten years, from January 1st, 2013 to June 30th, 2023.

ABC: ACB Bank

## Data Source

I used the dataset publicly available from https://www.kaggle.com/datasets/thangtranquang/stock-vn30-vietnam?select=ACB.csv

## Techniques Used
* Moving Average

The Moving Average (MA) technique involves calculating averages of a series of data points over specific periods to smoothen out fluctuations and highlight underlying trends.

### 100-day Moving Average (100MA):

![[1](100MA.png)](https://github.com/HoangPham2704/Stock_Trend_Prediction/blob/main/Picture/100MA.png?raw=true)

  Calculates the average price of a stock over the past 100 trading days.
  
  Provides a smoothed trend line representing short to mid-term price movements.
 
  Helps in identifying short-term trends, crossovers, and potential support/resistance levels.

### 200-day Moving Average (200MA):

![[2](100MA_&_200MA.png)](https://github.com/HoangPham2704/Stock_Trend_Prediction/blob/main/Picture/100MA_&_200MA.png?raw=true)

  Computes the average price of a stock over the previous 200 trading days.
 
  Offers a smoother trend line, reflecting longer-term price movements.
 
  Used to assess long-term trends, major price reversals, and overall market direction.

* LSTM ML Model

![Prediction_vs_Original_Price.png](https://github.com/HoangPham2704/Stock_Trend_Prediction/blob/main/Picture/Prediction_vs_Original_Price.png?raw=true)

 LSTM (Long Short-Term Memory) model is utilized to forecast and estimate the future behavior or performance trends of ACB Bank stocks. This model specializes in processing and understanding sequential data, allowing it to capture patterns and dependencies within historical stock data to make predictions regarding future stock movements or prices.

 ## Limitation:
 
 As a newcomer in the field, this project served as a valuable learning experience. While the forecasts may not have met the desired accuracy, it provided insights into the complexities of stock forecasting and the nuances of machine learning models in financial analysis.
