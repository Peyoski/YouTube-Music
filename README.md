YouTube Data Analysis

This repository contains a Python-based data analysis of a YouTube dataset. The dataset includes information about trending videos, including metadata such as titles, descriptions, tags, views, likes, dislikes, and comments.

Table of Contents

Introduction

Dataset Overview

Analysis Steps

1. Reading and Preprocessing Data
2. Sentiment Analysis
3. Word Cloud Analysis
4. Emoji Analysis
5. Combining Multiple CSV Files
6. Exporting Data
7. Category-wise Likes Analysis
8. Audience Engagement Analysis
9. Top Trending Channels
10. Punctuation and Engagement

Conclusion

Introduction

YouTube is one of the largest platforms for sharing and consuming video content globally. Analyzing trends and user engagement on YouTube can provide valuable insights for content creators, marketers, and platform administrators. This project aims to explore various aspects of the YouTube dataset through data analysis techniques.

Dataset Overview

The dataset used in this analysis contains information about trending videos on YouTube, including attributes such as video titles, descriptions, tags, view counts, likes, dislikes, comments, and channel information. The dataset is structured in CSV format and consists of multiple files.

Analysis Steps

1. Reading and Preprocessing Data
The dataset is read into a Pandas DataFrame, and preprocessing steps are applied, including handling missing values, duplicate entries, and data cleaning.

2. Sentiment Analysis
Sentiment analysis is performed on video comments using the TextBlob library to determine the sentiment polarity of each comment.

3. Word Cloud Analysis
Word cloud visualizations are generated to visualize the most frequent words in positive, negative, and neutral comments.

4. Emoji Analysis
The distribution of emojis in comments is analyzed to understand the use of emojis by viewers.

5. Combining Multiple CSV Files
Multiple CSV files containing YouTube data are combined into a single DataFrame for comprehensive analysis.

6. Exporting Data
Data from the analysis is exported to CSV, JSON, and SQLite formats for further exploration and sharing.

7. Category-wise Likes Analysis
Likes on trending videos are analyzed across different video categories to identify trends and preferences among viewers.

8. Audience Engagement Analysis
Engagement metrics such as likes, dislikes, and comments are analyzed to understand audience behavior and engagement patterns.

9. Top Trending Channels
The analysis identifies channels with the largest number of trending videos, providing insights into popular content creators.

10. Punctuation and Engagement
The relationship between the presence of punctuation in video titles/tags and engagement metrics such as views and likes is explored.

Conclusion
The analysis provides valuable insights into user behavior, content preferences, and engagement trends on YouTube.
