Phishing Website Detection using Machine Learning
Overview

This project detects phishing websites using supervised machine learning and deep learning models. A dataset of phishing and legitimate URLs is used to extract important features and train classification models to identify malicious websites.

Dataset

Phishing URLs: PhishTank (5000 samples)

Legitimate URLs: University of New Brunswick dataset (5000 samples)

Total dataset size: 10,000 URLs

Feature Engineering

A total of 17 features were extracted:

Address bar-based features (9)

Domain-based features (4)

HTML & JavaScript-based features (4)

Models Used

Decision Tree

Random Forest

Support Vector Machine (SVM)

XGBoost

Multilayer Perceptron (MLP)

Autoencoder Neural Network

Training & Evaluation

Problem type: Binary Classification (Phishing = 1, Legitimate = 0)

Train-Test Split: 80% training / 20% testing

Best performing model: XGBoost (Accuracy: 86.4%)

Results

The XGBoost model achieved the highest performance and was saved for future deployment.

Future Improvements

Browser extension for real-time phishing detection

GUI-based application for user input and prediction
