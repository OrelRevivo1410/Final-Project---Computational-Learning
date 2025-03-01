## Stock Market Synchronization Analysis using RNNs and LSTMs
A machine learning approach for forecasting stock price synchronization in the American stock market using Recurrent Neural Networks (RNNs), Long Short-Term Memory (LSTM) networks, and non-linear time-series analysis.

## Overview
This project explores stock synchronization prediction through:
Cross-recurrence plots (CRP) for capturing non-linear relationships between stock prices
Application to American market stocks (NYSE and NASDAQ)
Comparing 8D embedding (closing prices, volume) vs 16D embedding (high, low, closing prices, volume)
Evaluating RNN vs LSTM performance with different architectural variations

## Dataset
Time Period: January 2015 to February 2025
Companies: 30 highly capitalized companies across various sectors
Features: High, Low, Closing prices, and Trading volume
Split: 80% training, 20% testing

## Key Findings
RNN models consistently outperformed LSTM models
8-dimensional embeddings generally yielded better results than 16-dimensional embeddings
Original architecture performed better than modified architectures
Simpler approaches proved more effective for this specific financial time series task

## Authors
Idan Shabo (318632312)
Orel Revivo (208088815)
