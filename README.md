# Twitter Sentiment Analysis

This project focuses on the sentiment analysis of tweets using machine learning and deep learning techniques. The aim is to classify tweets into three categories: **positive**, **negative**, and **neutral** based on their textual content.

## Project Overview

In this project, we:
- Extracted features from tweets using **Bag of Words (BoW)** and **TF-IDF**.
- Built a **neural network model** using **Keras** and **TensorFlow** to classify the tweets.
- Used **dropout**, **regularization**, and **early stopping** techniques to prevent overfitting.
- Visualized the training and validation accuracy/loss to analyze the model performance.

## Dataset

The dataset used for this project consists of tweets collected from Twitter. The dataset includes labeled tweets for **positive**, **negative**, and **neutral** sentiments.

## Project Structure

- **`Twitter - Analysis.ipynb`**: The main Jupyter Notebook that contains the entire workflow from data preprocessing to model training and evaluation.
- **`data/`**: This folder should contain the dataset used for training the model (this folder may not be included in the repository due to size limits).
- **`requirements.txt`**: This file lists all the Python libraries required to run the project.
- **`results/`**: Contains the plots and graphs showing model performance.

## Features

- **Preprocessing**: 
  - Cleaned the tweets by removing stop words, punctuation, and special characters.
  - Applied decontraction and tokenization to handle contractions in text data.

- **Feature Extraction**: 
  - **CountVectorizer** and **TF-IDF** were used for converting textual data into numerical format.

- **Model**:
  - A deep neural network model with **Dense layers** was built using **Keras** and **TensorFlow**.
  - Dropout layers were added to prevent overfitting.
  - **L2 Regularization** was applied to further control overfitting.
  - **EarlyStopping** was used to stop the training when the validation loss stopped improving.

