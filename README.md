# Stock Predictive Analysis

The objective revolves around leveraging a supervised Machine Learning (ML) model to forecast the forthcoming performance or trends specifically related to ACB Bank stocks.

## About Dataset

The dataset comprises Stock Prices and Volume data for the 30 companies listed in the VN30 Index in Vietnam.
The dataset spans a period of ten years, from January 1st, 2013 to June 30th, 2023.

ABC: ACB Bank

## Data Source

I used the dataset publicly available from https://www.kaggle.com/datasets/thangtranquang/stock-vn30-vietnam?select=ACB.csv

### Techniques Used
* Moving Average

The Moving Average (MA) technique involves calculating averages of a series of data points over specific periods to smoothen out fluctuations and highlight underlying trends.

![[1](100MA.png)](https://github.com/HoangPham2704/Stock_Trend_Prediction/blob/main/Picture/100MA.png?raw=true)

  Calculates the average price of a stock over the past 100 trading days.
  Provides a smoothed trend line representing short to mid-term price movements.
  Helps in identifying short-term trends, crossovers, and potential support/resistance levels.

![[2](100MA_&_200MA.png)](https://github.com/HoangPham2704/Stock_Trend_Prediction/blob/main/Picture/100MA_&_200MA.png?raw=true)

  Computes the average price of a stock over the previous 200 trading days.
  Offers a smoother trend line, reflecting longer-term price movements.
  Used to assess long-term trends, major price reversals, and overall market direction.

* LSTM ML Model
![Prediction_vs_Original_Price.png](https://github.com/HoangPham2704/Stock_Trend_Prediction/blob/main/Picture/Prediction_vs_Original_Price.png?raw=true))

 LSTM (Long Short-Term Memory) model is utilized to forecast and estimate the future behavior or performance trends of ACB Bank stocks. This model specializes in processing and understanding sequential data, allowing it to capture patterns and dependencies within historical stock data to make predictions regarding future stock movements or prices.

## Outcome

LSTMs capturing complex patterns and relationships within data, potentially offering improved accuracy for stock price predictions but might lack interpretability.

Moving Averages offer simplicity and easy interpretation but may not capture intricate patterns or non-linear relationships in stock prices as effectively as LSTMs. 
