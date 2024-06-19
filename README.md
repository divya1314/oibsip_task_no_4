# Unveiling the Android App Market: Analyzing Google Play Store Data

This project aims to analyze Google Play Store data to understand app market dynamics. The analysis includes data preparation, category exploration, metrics analysis, sentiment analysis, and interactive visualization.

## Table of Contents

- [Dataset](#dataset)
- [Data Preparation](#data-preparation)
- [Category Exploration](#category-exploration)
- [Metrics Analysis](#metrics-analysis)
- [Sentiment Analysis](#sentiment-analysis)
- [Interactive Visualization](#interactive-visualization)

## Dataset

The dataset used for this analysis is from Kaggle and can be found [here](https://www.kaggle.com/datasets/utshabkumarghosh/android-app-market-on-google-play).

## Data Preparation

The `data_preparation.py` script handles the following tasks:
- Removing rows with null values.
- Removing duplicate rows.
- Converting data types for accurate analysis.
- Converting 'Size' and 'Price' columns to numerical values.

## Category Exploration

The `category_exploration.py` script analyzes the distribution of apps across various categories and visualizes it using a bar plot.

## Metrics Analysis

The `metrics_analysis.py` script examines app ratings, size, and pricing trends. It creates visualizations to show the distribution of ratings and the relationship between app size, price, and ratings.

## Sentiment Analysis

The `sentiment_analysis.py` script uses the VADER sentiment analyzer to assess user sentiments through reviews. It cleans the text data and computes sentiment scores, visualizing the sentiment distribution.

## Interactive Visualization

The `interactive_visualization.py` script uses Plotly to create an interactive scatter plot showing the relationship between app size and rating, color-coded by category.
