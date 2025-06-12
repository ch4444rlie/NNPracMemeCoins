# Meme Coin Price Predictor

## Overview
This project applies concepts from *Neural Networks from Scratch in Python* by Harrison Kinsley and Daniel Kukieła to develop a neural network-based model for predicting the price of a meme coin (Trump Coin in this case), a volatile cryptocurrency. The motivation behind this project is to help protect people from potential scams by providing insights into price movements driven by social media activity and public sentiment.

## Methodology
The project employs a nested neural network architecture:
- **Inner Neural Network**: Trained to analyze and predict sentiment from general investment-related discussions on social media (Reddit).
- **Outer Neural Network**: Utilizes the sentiment predictions, scraped coin prices, social media post volume, and social media post impressions to forecast the meme coin's price (Trump Coin).

## Sentiment Analysis Design
The inner neural network is designed to train on a broad dataset of general crypto investment-related Reddit discussions, rather than data specific to a single cryptocurrency. This approach enhances training efficiency, as collecting and processing coin-specific data can be slow and make the model overly specialized. By focusing on generalized sentiment analysis, the model becomes a more versatile tool, capable of adapting to various cryptocurrencies and market contexts.

## Objective
The predictor aims to enhance investor awareness by modeling the relationship between social media sentiment and Trump Coin price fluctuations, ultimately helping users make informed decisions and avoid potential financial scams in the meme coin market.

## Status
The project is approximately 80% complete. Current progress includes the implementation of the nested neural network architecture and initial training on sentiment and price datasets. Further refinements, including model optimization and validation, are ongoing.

## Implementation
The core implementation is detailed in the Jupyter notebook: `PredictTrumpCoin.ipynb`.

## Disclosure
This project is strictly for educational and learning purposes. It is not intended to provide financial advice or guide real-world investment decisions. Users should not rely on the model's predictions for actual trading or investment activities.
