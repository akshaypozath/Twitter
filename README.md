#TWITTER DATA ANALYSIS
This project performs a comprehensive analysis of Twitter data, particularly tweets from public figures like Donald Trump. The analysis includes data collection, cleaning, sentiment analysis, device usage trends, time-based activity, and principal component analysis (PCA) for tweet content.

Features
Twitter API Integration:
Uses the tweepy library to fetch recent tweets from specified accounts using Twitter API credentials.

Data Caching:
Saves downloaded tweets as JSON files to prevent repeated API calls.

Tweet Preprocessing:
Converts raw tweet data into structured format, cleans HTML tags, removes punctuation, handles duplicates, and processes timestamps.

Device Analysis:
Identifies the most frequently used devices (e.g., iPhone vs Android) and analyzes time-of-day usage patterns.

Sentiment Analysis:
Implements a custom lexicon-based sentiment scoring system using the VADER sentiment lexicon. Aggregates polarity scores for each tweet.

Comparison of Sentiment Sources:
Compares sentiment polarity for tweets mentioning different media outlets like Fox and NYT.

PCA on Tweet Content:
Applies Principal Component Analysis to the most frequent words in tweets to discover underlying patterns and relationships.
