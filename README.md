# Fake-News-Prediction-ML-PR-4

A Machine Learning-based application that predicts whether a given news article is **Fake News or Real News**. The project uses **Natural Language Processing (NLP)** techniques to preprocess textual news data and a **Logistic Regression** classification model to perform the prediction.

 Project Overview

The rapid growth of digital media and social networking platforms has made the spread of misleading and fabricated news increasingly common.

This project aims to automatically identify potentially fake news articles by analyzing their textual content using Machine Learning.

The system processes a dataset of news articles, performs text preprocessing and feature extraction, splits the data into training and testing sets, and trains a Logistic Regression model for binary classification.

# Prediction Classes

-  **Real News**
-  **Fake News**


# Project Workflow

The overall workflow of the project is:

`
        News Dataset
             │
             ▼
     Data Preprocessing
             │
             ▼
     Feature Extraction
             │
             ▼
       Train-Test Split
             │
             ▼
    Logistic Regression
             │
             ▼
      Trained Model
             │
             ▼
       New News Data
             │
             ▼
       Prediction
             │
       ┌─────┴─────┐
       ▼           ▼
    REAL NEWS    FAKE NEWS
