# Electricity Demand Forecasting

This project focuses on forecasting national electricity demand using time series models, including ARIMA, RNN, and LSTM. The goal is to predict monthly electricity demand based on historical trends, seasonality, and other patterns in the data.

## Project Overview

- **Data:** Monthly electricity demand data
- **Objective:** Predict future electricity demand trends
- **Methods Used:**
  - ARIMA (AutoRegressive Integrated Moving Average)
  - RNN (Recurrent Neural Network)
  - LSTM (Long Short-Term Memory Network)
- **Key Findings:**
  - Electricity demand follows a yearly seasonal pattern, peaking in December and dropping in summer.
  - LSTM performed best based on evaluation metrics, while RNN captured the trend slightly better.

## Data Analysis

- Condensed to monthly electricity demand for better trend prediction.
- Checked for stationarity using the Augmented Dickey-Fuller (ADF) test.
- Used ACF and PACF plots to determine ARIMA model parameters.
- AI models trained using 24 months of sequential data as input.

## Model Performance

| Model  | Performance Summary |
|--------|----------------------|
| ARIMA  | Captures trend and seasonality but limited by linear assumptions. |
| RNN    | Performs well but struggles with long-term dependencies. |
| LSTM   | Best performer; effectively captures seasonality and trends. |

## Future Work

- Experiment with hybrid models combining statistical and deep learning approaches.
- Incorporate external factors such as temperature and economic indicators.
- Optimize hyperparameters for better forecasting accuracy.

## Dataset

[[Link to source data](https://www.kaggle.com/datasets/albertovidalrod/electricity-consumption-uk-20092022?select=historic_demand_2009_2024_noNaN.csv)] 


## License

This project is licensed under the MIT License.

