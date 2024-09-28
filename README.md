# Twitter Sentiment Analysis

This project uses machine learning and natural language processing (NLP) techniques to predict the sentiment of tweets, classifying them as **positive**, **negative**, or **neutral**.

## Problem Statement
Analyzing user sentiment through tweets helps companies gain valuable insights during product launches. Understanding customer feedback allows businesses to make informed decisions, address concerns, and improve overall satisfaction.

## Approach

- **Natural Language Processing (NLP)**: We apply text preprocessing techniques to convert words into numerical vectors that machine learning models can use for sentiment prediction.
- **Vectorizers**:
  - **CountVectorizer**
  - **TfidfVectorizer**
- **Model**: A **deep neural network (DNN)** was used for the sentiment prediction task.

## Exploratory Data Analysis (EDA)
- The dataset shows more **neutral** sentiments compared to positive or negative sentiments.
- **Word clouds** indicate frequent words:
  - **Positive Tweets**: Words like "thank", "day", "great".
  - **Negative Tweets**: Words like "hate", "sad".

## Hyperparameter Tuning
After model development, hyperparameter tuning was performed to optimize the performance and achieve better accuracy.

## Results
- The model was able to predict sentiment with high accuracy during training, although overfitting was observed and addressed with regularization and dropout techniques.

