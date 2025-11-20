# YouTube-Data-Analytics-Project---Python---Pandas


## Overview

This repository explores and analyzes the Kaggle "Top 5000 YouTube Channels Dataset" covering channel rankings, video uploads, subscribers, video views, and grades. The process focuses on exploratory data analysis (EDA), data cleaning, and visualization to uncover insights about top-performing channels.

## Dataset Source

- [Kaggle: Top 5000 YouTube Channels](https://www.kaggle.com/rahuldogra/top-5000-youtube-channels)

## Project Steps

1. **Load Dataset**
   - Reads the CSV file into a pandas DataFrame.
2. **Initial Exploration**
   - Displays head/tail, shape, column types, and summary statistics.
3. **Data Cleaning**
   - Replaces missing/invalid values, converts columns to appropriate data types, and drops incomplete records.
4. **Null Value Inspection & Handling**
   - Summarizes missing values before cleaning.
5. **Feature Engineering**
   - Calculates new metrics (average views per video).
6. **Visualization & Analysis**
   - Uses seaborn/matplotlib to plot insights about video uploads, subscribers, views, and grade distributions.
   - Identifies top channels and analyzes relationships using correlation matrices.
7. **Conclusions**
   - Summarizes major findings and insights into what makes successful channels.

## Requirements

- Python 3.x
- pandas
- seaborn
- matplotlib
- numpy



## Key Insights

- Grades relate to overall channel performance, showing grouping effects in subscriber/view distribution.
- Channels with higher upload counts do not always correlate to higher subscribers/views.
- Correlation analysis helps understand relationships between channel activity and popularity.


