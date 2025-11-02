# RNN Stock Price Prediction

This project uses a Recurrent Neural Network (RNN) to predict stock prices for four major companies:
- **IBM (IBM)**
- **Google (GOOGL)**
- **Amazon (AMZN)**
- **Microsoft (MSFT)**

## Dataset
- **Total data points:** 11,997
- **Training samples:** 9,597
- **Validation samples:** 2,400

The dataset contains historical stock price information for each company. Features may include opening price, closing price, high/low values, trading volume, or derived time-series features depending on preprocessing.

## Model
The model is based on **Recurrent Neural Networks (RNNs)**, which are designed to handle sequential time-series data. The network learns patterns across historical price data to forecast future stock values.

## Objective
The goal of this project is to:
- Train an RNN to understand temporal stock price trends.
- Evaluate model performance on a validation set.
- Predict future stock movements for each company.

## Usage
1. Load and preprocess the stock price dataset.
2. Train the RNN model on the training dataset.
3. Validate and fine-tune using the validation subset.
4. Generate predictions and visualize results.

## Conclusion
This project demonstrates that:
- Simpler models can perform better when long-term dependencies are limited.
- Model selection should be based on data characteristics, not complexity alone.

