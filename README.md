# Spam-Email-Detection-with-Logistic-Regression
A logistic regression-based spam email detection model with 99.4% accuracy, featuring TF-IDF text vectorization and real-time email classification.

This project is a machine learning solution for detecting spam emails using Logistic Regression. The model is trained on a dataset of emails, where each email is labeled as either spam or not spam. The project involves preprocessing the email text, extracting features using TF-IDF (Term Frequency-Inverse Document Frequency), and training a logistic regression model to classify new emails. Additionally, users can input their own email content, and the model will classify it as either spam or not spam.

Features
- Data Preprocessing: Cleans the text by converting it to lowercase, removing punctuation, and removing stopwords.
- TF-IDF Vectorization: Converts the cleaned email text into numerical features using TF-IDF, focusing on the top 5000 features for computational efficiency.
- Logistic Regression Model: Trains a logistic regression model on the TF-IDF features to detect spam emails.
- Interactive Email Classification: Allows users to input their own email content and get a classification result (spam or not spam).
