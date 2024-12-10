# US Airline Sentiment Analysis using LSTM

## Overview
This project analyzes customer sentiment in tweets about US airlines. Using a Long Short-Term Memory (LSTM) model, the sentiments are classified into positive, neutral, or negative categories.

## Dataset
The dataset used is the **[US Airline Sentiment Dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)**, containing tweets labeled with sentiments (positive, neutral, or negative).

## Model
The LSTM model includes:
- **Embedding Layer**: Converts words into vector representations.
- **LSTM Layer**: Captures the sequence and context of words in tweets.
- **Dense Layer**: Classifies tweets into sentiment categories.

## Results
The LSTM model achieved:
- **Accuracy**: 93%
- **Sentiment Breakdown**: 
  - Positive Sentiment: Correctly classified tweets expressing satisfaction.
  - Negative Sentiment: Effectively identified tweets expressing dissatisfaction.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.