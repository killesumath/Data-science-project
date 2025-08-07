# Airline Tweet Sentiment Classifier

This project focuses on classifying airline-related tweets into three sentiment categories: Positive, Neutral, and Negative.

## What This Project Covers

-> Used a dataset of tweets directed at airline customer service.  
-> Performed exploratory data analysis (EDA) and cleaned the text data.  
-> Preprocessed tweets with lowercasing, punctuation removal, stop word removal, and stemming.  
-> Used TF-IDF for traditional models and tokenizer + embedding for deep learning models.

## Models and Performance

-> Logistic Regression: 78.6% accuracy – Simple and fast, but biased toward the negative class.  
-> Decision Tree: 69.7% accuracy – Easy to interpret, but struggled with minority classes.  
-> BiLSTM: 76% accuracy – Best overall performance and class balance.  
-> Simple RNN: 74% accuracy – Worked well on short tweets.

## Key Learnings

-> Short and sarcastic tweets were the hardest to classify.  
-> BiLSTM captured context the best among all models.  
-> Logistic Regression and Decision Tree struggled with positive and neutral sentiments.

## Files Included

-> Sumath_DS_FinalProject.ipynb: Jupyter Notebook with code and outputs  
-> Tweets.csv: The dataset used  
-> Sumath_DS_FinalProject_report.pdf: Final written report  
-> README.md: Project summary

## Author

Sumath Chandra Kille  

