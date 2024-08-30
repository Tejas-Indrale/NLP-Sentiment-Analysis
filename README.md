Twitter Sentiment Analysis: Vaccination Tweets
Objective:
Analyze sentiments in tweets related to vaccination using NLP and machine learning techniques.

Data Overview:

Dataset: Kaggle's vaccination tweets dataset with 11,020 tweets.
Key Columns: text (tweet content), sentiment (Positive, Neutral, Negative).
Preprocessing:
Removed URLs, mentions, hashtags, and punctuation.
Tokenized and removed stopwords.
Applied stemming.
Sentiment Analysis:

Polarity Calculation: Used TextBlob to determine the sentiment polarity.
Classification:
Logistic Regression model.
Test Accuracy: 84.64%
Best Parameters: C=10
Visualization:

Word clouds for positive, negative, and neutral tweets.
Confusion matrix for model evaluation
