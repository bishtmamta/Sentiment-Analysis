# Sentiment Analysis using Python
An end-to-end Natural Language Processing (NLP) and Text Mining project that analyzes customer sentiments from textual data. By extracting polarity and subjectivity scores using TextBlob and NLTK, this pipeline translates raw text into actionable insights to help businesses track user sentiment and improve customer satisfaction.

---

## 📋 Overview
Text mining enables product-based companies to examine customer feedback, understand market trends, and enhance customer experience. This project demonstrates a complete data preprocessing pipeline, feature extraction, sentiment analysis, and visual data exploration on Twitter/Social Media text datasets.

---

## Key Features
Data Cleaning & Normalization: Noise removal, stopword filtering, punctuation removal, regex-based URL/number stripping, and lowercasing.

Text Tokenization & Normalization: Advanced tokenization via TweetTokenizer, Stemming, and Lemmatization.

Sentiment Metrics:

Polarity Score: Measures sentiment on a scale from -1.0 (Negative) to +1.0 (Positive).

Subjectivity Score: Measures opinion vs. fact on a scale from 0.0 (Objective) to 1.0 (Subjective).

Categorical Classification: Automatic labeling into Positive, Neutral, and Negative categories.

Visual Exploration: Visualizing frequent terms via custom WordCloud generation.

---

## 🛠️ Tech Stack & Dependencies
Language: Python 3.x

Core Libraries:

pandas, numpy — Data manipulation & structured data handling

nltk — Natural Language Toolkit (Tokenization, Stopwords, Lemmatization, Stemming)

textblob — Sentiment scoring (Polarity & Subjectivity)

matplotlib, seaborn — Static data visualization

wordcloud — Text frequency visualization

re, string — Regex pattern matching and string cleaning
