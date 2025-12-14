# Spam-Detection-Project
Detects spam emails with 97% accuracy using TF-IDF and Logistic Regression; includes error analysis and confusion matrix for interpretability.

Overview

This project builds a machine learning model to classify emails as spam or ham (not spam). The goal is to demonstrate the full pipeline of an ML project: data preprocessing, feature extraction, model training, evaluation, and error analysis.

The model uses Logistic Regression with TF-IDF vectorization (including unigrams and bigrams) to capture both single words and common spammy phrases

Dataset

The dataset is sourced from Kaggle: Spam Email Collection

It contains labeled spam and ham emails.

Place the CSV file in a data/ folder within the project directory.

How to Run

Clone the repository:

git clone https://github.com/SHANMUKH-TIWARI/Spam-Detection-Project


Make sure the dataset is in data/spam.csv.

Open Spam_Classifier.ipynb in Jupyter Notebook or VS Code.

Run the notebook top to bottom.

The notebook will load the dataset, preprocess the text, train the model, and evaluate performance.

False negatives are displayed for error analysis.

A confusion matrix visualization shows performance at a glance



Skills Demonstrated

Python, Pandas, NumPy

Data cleaning and preprocessing

Text feature extraction (TF-IDF, n-grams)

Logistic Regression and scikit-learn

Model evaluation (accuracy, precision, recall, F1, confusion matrix)

Error analysis
