# Twitter Sentiment Analysis

## Overview
This project implements **Twitter Sentiment Analysis** using machine learning. The goal is to classify tweets as **positive** or **negative** based on their sentiment. The model was trained on a dataset of 1.6 million tweets and achieved an accuracy of **77.65%** using a **Logistic Regression model**.

## Features
- Preprocessing of raw tweets (removal of stopwords, hashtags, mentions, and links).
- Vectorization using **TF-IDF**.
- Sentiment classification using a **Logistic Regression model**.
- Evaluation metrics like **accuracy, precision, recall, and F1-score**.

## Dataset
The dataset used for this project contains **1.6 million tweets** and includes the following columns:
1. **Sentiment**: Indicates whether the tweet is positive (1) or negative (0).
2. **Text**: The content of the tweet.

The dataset is preprocessed and split into training and test sets.

---

## Model Overview
1. **Preprocessing**:
   - Text normalization (lowercasing, removing special characters).
   - Removal of stopwords using `nltk`.
   - Tokenization of text.
2. **Feature Engineering**:
   - Tweets are vectorized using **TF-IDF Vectorizer** from `sklearn`.
3. **Model**:
   - Logistic Regression was used for binary classification.
4. **Evaluation**:
   - Accuracy: **77.65%**
   - Other metrics available in the project.

---

## Prerequisites
Make sure you have the following installed:
- Python (3.6 or higher)
- Pip (Python package installer)
- numpy
- pandas
- scikit-learn
- nltk





