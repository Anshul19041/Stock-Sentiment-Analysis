# Stock Sentiment Analysis Using Machine Learning

## Overview

This project implements a Stock Sentiment Analysis model using Natural Language Processing (NLP) and Machine Learning. It analyses financial news headlines to predict stock market sentiment, which can be used as an indicator for trading strategies.

## Features

Preprocesses and cleans financial news headlines.

Uses CountVectorizer for feature extraction with n-grams.

Trains a Random Forest Classifier for sentiment prediction.

Evaluates model performance using accuracy and confusion matrix.

## Technologies Used

Python Libraries: Pandas, Scikit-learn, Joblib, Pickle

Machine Learning: Random Forest Classifier

Natural Language Processing: CountVectorizer (n-gram feature extraction)

Data Handling: CSV file processing with Pandas

## How to Use

Install dependencies.

Load the dataset and preprocess text data.

Train the model using RandomForestClassifier.

Evaluate the model performance using accuracy metrics.

## Future Enhancements

Implement Deep Learning models (LSTMs, Transformers) for better accuracy.

Integrate live news data from APIs for real-time predictions.

Include sentiment scoring for stronger decision-making.

