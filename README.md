# Predicting the price of Bitcoin, intro to LSTM

This project was built as part of the article "Predicting the price of Bitcoin, intro to LSTM", which was published [here](https://livecodestream.dev/post/2020-06-04-predicting-the-price-of-bitcoin-intro-to-lstm/).

Today we are going to discuss how to predict the price of Bitcoin by analyzing the pricing information for the last 6 years. Note that we already have established that our analysis will only focus on the pricing information, leaving aside any factor which may impact the price of Bitcoin, like for example, news, which can play a very important rule. For this reason, I say that this article and related project are only intended for educational purposes and should not be used in production. It is an overly simplistic model that will help us explain and understand time series forecasting using Python and Recurrent Neural Networks (RNNs), more precisely we will build an LSTM (Long-Short Term Memory) model......

## Set Up

1. Check out the code

2. Install dependencies

```shell script
pipenv install
```

3. Start jupyter notebook `analysis.ipynb`