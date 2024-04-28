# Stock Market Prediction with LSTM

This project explores the use of Long Short-Term Memory (LSTM) networks for stock market prediction. The notebook contains Python code for training an LSTM model to predict stock prices based on historical data.

## Overview

The project aims to implement an LSTM model to predict stock prices using historical data. It includes steps for data preprocessing, model training, evaluation, and prediction.

## Data

The dataset used in this project contains historical stock prices for a specific stock ticker ('XLB') from November 30, 2018, to November 30, 2022.

## Model Architecture

The LSTM model architecture consists of two LSTM layers followed by two dense layers. The model is compiled using the Adam optimizer and trained using mean squared error loss.

## Results

The trained model is evaluated on a test dataset, and the predictions are compared with the actual stock prices. Evaluation metrics such as root mean squared error (RMSE) and average percent error are calculated to assess the model's performance.

## How to Use

To run the notebook:

1. Install the required dependencies listed in the notebook.
2. Download the dataset or use a different stock ticker for analysis.
3. Execute each cell in the notebook sequentially to preprocess the data, train the model, and make predictions.

## Conclusion

The LSTM model demonstrates reasonable performance in predicting stock prices based on historical data. Further optimization and experimentation could improve the accuracy of the predictions.

For detailed code implementation and results, please refer to the notebook.

