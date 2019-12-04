# Anomaly detection in Taxi demand with LSTM network

In this notebook we try to predict Taxi demand in New York City in a critical time period. We explore the dataset to formulate important assumptions about taxi demand and human behaviour driving it, e.g. demand surges on certain days.

We make use of a LSTM Network to learn the behaviour of taxi demand in NYC. By training neural network to predict extreme values - i.e. lower (10th quantile), upper (90th quantile) - as well as the classical 50th quantile, we are able to make preditions and estimate uncertainty at the same time!

We implicitly define an anomaly as an unpredictable observation — i.e. with a great amount of uncertainty, which can calculated as difference between 90th and 10th qunatile. This simple assumption permits our LSTM to all do work.

































you can find the full article <b><a href='https://towardsdatascience.com/anomaly-detection-with-lstm-in-keras-8d8d7e50ab1b'>here</a></b>
