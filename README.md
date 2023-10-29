# Identify Trends In Amazon Stock Price Using [LSTM](https://en.wikipedia.org/wiki/Long_short-term_memory)

The Random walk theory suggests that changes in asset prices are random. This means that stock prices move unpredictably so that past prices cannot be used to predict future prices accurately. So it's actually impossible to predict exactly the future stock price otherwise we would all become billionaires, but it's actually possible to predict some trends. This model predicts the upward and downward trends that exist in the Amazon stock price using LSTM.

The LSTM model will try to capture the downward and upward trend of the Amazon stock price. LSTM is the most powerful implementation that can do this because it performs better than the traditional RNN model and it aimed to deal with the [vanishing gradient](https://en.wikipedia.org/wiki/Vanishing_gradient_problem) problem present in traditional RNNs.

## Approach to Predicting Trends in Amazon Stock Price:

The LSTM model will be trained on five years of the Amazon stock price (2012 - 2016) and then, based on this training (based on the correlations identified or captured by the LSTM of the Google stock price), the model will predict the first month of 2017.

Note: The model is not going to try to predict exactly the stock price, the model will predict the trend, the upward or downward trend of the Amazon stock price.

## Dataset:
- Train data: Contains the Amazon stock price from the beginning of 2012 to the end of 2016,
- Test data: Contains the first month of 2017. That is the whole financial month of January 2017.

## Dataset Source:
- [Yahoo_fin](https://theautomatic.net/yahoo_fin-documentation/)

## Useful Links:
- [Recurrent Neural Network (RNN)](https://www.mathworks.com/discovery/rnn.html)
- [Long Short-Term Memory (LSTM)](https://wiki.pathmind.com/lstm)
