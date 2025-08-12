# PRODIGY_DS_04
Twitter Sentiment Analysis

📌 Project Overview

This project performs sentiment analysis on a Twitter dataset to understand public opinions about different entities (brands, products, etc.). The analysis includes cleaning the dataset, removing null and duplicate values, and visualizing sentiment distributions overall and for specific brands.
📂 Dataset

File: twitter_training.csv
Columns:
ID – Unique identifier for each tweet
Entity – Brand or product mentioned in the tweet
Sentiments – Sentiment label (Positive, Negative, Neutral, Irrelevant)
Contest – Tweet text/content
Source: Dataset provided for analysis

🛠 Technologies Used

Python Libraries:
Pandas → Data manipulation
Matplotlib → Data visualization
TextBlob → Natural Language Processing (optional sentiment analysis)
Google Colab for development

📊 Steps Performed

1. Data Loading

Loaded CSV file with appropriate column names
Inspected dataset with .head() and .describe()
2. Data Cleaning
Removed NaN values
Removed duplicate rows
Verified cleaned dataset size
3. Sentiment Analysis
Counted total number of tweets in each sentiment category
Visualized sentiment distribution using a bar chart
4. Brand-Specific Analysis
Filtered tweets mentioning Microsoft
Counted sentiment distribution for that brand
Visualized brand-specific sentiment using a pie chart

📈 Visualizations
Bar Chart: Overall sentiment distribution
Pie Chart: Sentiment distribution for Microsoft tweets
