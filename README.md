# MastersDissertation

# Stock Market Forecasting with Topic Modelling and Sentiment Analysis
# Description:
This repository contains an analysis of the stock market leveraging topic modeling using Latent Dirichlet Allocation (LDA) combined with sentiment analysis techniques sourced from BERT and VADER.

# Key Components:
# Data Preprocessing:

The raw financial news data is cleaned to remove any noise.
Tokenization of the sentences to derive meaningful words or tokens.
Removal of stopwords to ensure only significant words are taken into account.
# Topic Modeling (LDA):

LDA is used to classify the financial news into various topics. This helps in understanding the dominant themes in the data.
Visualizations are provided to depict the topic-word distribution.
# Sentiment Analysis:

Two sentiment analysis techniques are implemented:
a. BERT: A transformer-based model that's pre-trained on a vast amount of text. It's fine-tuned here for sentiment analysis on financial news.
b. VADER: A rule-based sentiment analysis tool specifically designed for social media sentiments but adapted for financial contexts in this code.
Modeling for Stock Prediction:

Six machine learning models are trained using sentiment scores as features to predict the stock market movements: RandomForestClassifier, LogisticRegression, SVM, KNN, GradientBoosting, and DecisionTree.
Performance metrics, including accuracy, precision, recall, and f1 score, are computed for each model.
Visualizations:

Bar charts are used to depict the comparative performance of different models based on the sentiment scores provided by BERT and VADER.
# Results:
The analysis provides insights into how news sentiment, as gauged by BERT and VADER, correlates with stock market movements.
Model performance metrics offer a comparative evaluation of how well each model predicts stock market movements based on news sentiment.
