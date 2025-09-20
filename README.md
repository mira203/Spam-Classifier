# Spam Classifier
This project implements a Spam Detection Web App using Python, Scikit-learn, and Streamlit. It classifies text messages as Spam or Ham (not spam) in real-time.

# Features
Train a Naive Bayes classifier on SMS dataset.
Convert text into numerical features using CountVectorizer.
Interactive Streamlit web app for user input.
Instant prediction of Spam vs Ham.
Simple, lightweight, and easy to run locally.

# How It Works
Load and preprocess the dataset (spam.csv).
Map categories: spam → 1, ham → 0.
Split data into training and testing sets.
Extract features using Bag of Words with CountVectorizer.
Train a Multinomial Naive Bayes model.
Deploy the trained model in a Streamlit interface.
User enters a message → model predicts Spam/Ham instantly.

# Example Run
Streamlit App:
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/ad41cf77-f515-4636-9225-b0814e9c3141" />
