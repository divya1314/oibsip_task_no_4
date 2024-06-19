# Unveiling the Android App Market: Analyzing Google Play Store Data

This project aims to analyze Google Play Store data to understand app market dynamics. The analysis includes data preparation, category exploration, metrics analysis, sentiment analysis, and interactive visualization.

## Table of Contents

- [Dataset](#dataset)
- [Data Preparation](#data-preparation)
- [Category Exploration](#category-exploration)
- [Metrics Analysis](#metrics-analysis)
- [Sentiment Analysis](#sentiment-analysis)
- [Interactive Visualization](#interactive-visualization)
- [Conclusion](#conclusion)

## Dataset

The dataset used for this analysis is from Kaggle and can be found [here](https://www.kaggle.com/datasets/utshabkumarghosh/android-app-market-on-google-play).

## Data Preparation

Data preparation is a crucial step before performing any analysis. It involves cleaning and transforming the raw data to make it suitable for analysis. Here are the tasks handled by the data preparation process:

- **Removing Null Values**: Rows with missing data are removed to ensure accuracy in the analysis.
  
- **Removing Duplicate Rows**: Duplicate entries in the dataset are eliminated to avoid skewing the results.
  
- **Converting Data Types**: Ensuring correct data types (e.g., numerical or categorical) are assigned to each column for accurate analysis.
  
- **Handling Size and Price**: Converting 'Size' and 'Price' columns to numerical values allows for numerical operations and analysis.

## Category Exploration

Understanding the distribution of apps across different categories provides insights into market trends and user preferences. The category exploration module analyzes this distribution and visualizes it using a bar plot. This helps in identifying which categories have the most and least number of apps, and how these categories compare in terms of app count.

## Metrics Analysis

Metrics analysis focuses on examining various attributes of apps listed on the Google Play Store. This includes:

- **App Ratings**: Analyzing the distribution of app ratings to understand user satisfaction and app quality perception.
  
- **App Size**: Examining the distribution of app sizes to identify trends and understand storage requirements.
  
- **App Pricing**: Analyzing pricing trends across different categories and genres to understand pricing strategies and their impact on app adoption.
  
Metrics analysis involves creating visualizations such as histograms, scatter plots, and bar charts to illustrate these distributions and relationships.

## Sentiment Analysis

Sentiment analysis uses the VADER sentiment analyzer to assess user sentiments through app reviews. It involves the following steps:

- **Text Cleaning**: Preprocessing the text data to remove noise and irrelevant information.
  
- **Sentiment Scoring**: Computing sentiment scores for each review to quantify the sentiment expressed (positive, negative, or neutral).
  
- **Visualization**: Visualizing the sentiment distribution using charts such as histograms or pie charts to understand overall user sentiment towards apps.

## Interactive Visualization

Interactive visualization enhances data exploration by allowing users to interact with visual representations of data. In this project, interactive visualization is achieved using Plotly. The module includes:

- **Interactive Scatter Plot**: Creates a dynamic scatter plot that illustrates the relationship between app size and ratings. Each data point is color-coded by category, enabling users to explore how different app categories vary in size and user ratings.

- **Customization**: Users can zoom in, pan, and hover over data points to view detailed information, providing a flexible and informative way to explore the dataset.

These interactive visualizations provide deeper insights into app market dynamics, helping stakeholders make informed decisions based on data-driven analysis.

## Conclusion

Analyzing Google Play Store data offers valuable insights into the Android app market, revealing trends, user preferences, and factors influencing app success. By leveraging data preparation techniques, category exploration, metrics analysis, sentiment analysis, and interactive visualization, this project provides a comprehensive approach to understanding app market dynamics.

The findings from this analysis can guide developers, marketers, and decision-makers in optimizing app performance, improving user satisfaction, and making strategic decisions in the competitive landscape of the Google Play Store.

