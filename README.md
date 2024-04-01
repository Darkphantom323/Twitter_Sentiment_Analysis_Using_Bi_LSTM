# Twitter Sentiment Analysis for Hate Speech Detection

## Overview
This project focuses on detecting hate speech in tweets using various machine learning models. Hate speech is identified as tweets containing racist or sexist sentiments. The task involves classifying tweets as either containing hate speech (label '1') or not (label '0'). We leverage a labeled training dataset to train the models and then evaluate their performance on a separate test dataset.

## Dataset
The dataset used for this project is available on Kaggle at the following link: [Twitter Sentiment Analysis - Hatred Speech](https://www.kaggle.com/datasets/arkhoshghalb/twitter-sentiment-analysis-hatred-speech)
The dataset consists of labeled tweets, where '1' denotes tweets containing hate speech (racist or sexist) and '0' denotes tweets not containing hate speech.

## Models and Performance
1. **Multinomial Naive Bayes**
   - Accuracy: 93.72%
   - Naive Bayes is a probabilistic classifier based on Bayes' theorem. Despite its simplicity, it performs reasonably well for this task.

2. **Logistic Regression**
   - Accuracy: 94.5%
   - Logistic regression is a linear model suitable for binary classification tasks. It performs slightly better than Naive Bayes in this scenario.

3. **Linear SVC (Support Vector Classifier)**
   - Accuracy: 96.2%
   - Linear SVC is a powerful classifier that finds the hyperplane that best separates the classes. It achieves the highest accuracy among the traditional machine learning models used.

4. **Bi LSTM (Bidirectional Long Short-Term Memory)**
   - Accuracy: 95.1%
   - Bi LSTM is a deep learning model particularly well-suited for sequential data like text. It incorporates contextual information from both past and future words in the sequence, contributing to its high accuracy.
