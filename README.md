# Sentiment Analysis Project

## Overview

This project focuses on performing sentiment analysis on text using Python libraries like **TextBlob**. Sentiment analysis evaluates a piece of text to determine its emotional tone. The objective is to classify the sentiment of a given text into categories such as positive, neutral, or negative, and to provide additional insights into the text.

## Features

### Sentiment Polarity
- Determines the polarity of the text, represented by a numerical value between -1 (very negative) and 1 (very positive).

### Sentiment Classification
Categorizes the sentiment of the text into one of the following labels:
- Very Positive
- Positive
- Slightly Positive
- Neutral
- Slightly Negative
- Negative
- Very Negative

### Subjectivity Analysis
- Evaluates the subjectivity of the text, ranging from 0 (completely factual) to 1 (highly opinionated).

### Text Metrics
Provides additional text insights:
- Number of sentences
- Number of words

### Error Handling
- Handles common errors, such as missing input files, to ensure smooth execution.



## Example Use Cases

- **Analyzing Reviews**: Determine the sentiment of customer reviews or feedback to gauge user satisfaction.
- **Content Moderation**: Identify negative or offensive content in social media posts or other user-generated content.
- **Opinion Mining**: Understand public sentiment on various topics based on text data like blogs, articles, or forum posts.

## Key Libraries Used

- **TextBlob**: For natural language processing and sentiment analysis.
- **Python File Handling**: To manage reading from and writing to files efficiently.
