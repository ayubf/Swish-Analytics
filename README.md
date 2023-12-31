# Swish Analytics: A Deep Dive into NBA Statistics
<hr>

The objective of this project is to use statistical analysis methods on the [NBA Players dataset](https://www.kaggle.com/datasets/justinas/nba-players-data) to find patterns within player statistics, identify anomalies and outliers, and analyze trends in the data.

[View in NBViewer](https://nbviewer.org/github/ayubf/Swish-Analytics/blob/main/main.ipynb)

## Project Objectives

### Finding Patterns

1. **Correlation with Age:**
   - Explore the correlation between player performance and age.

2. **Top Producing Colleges:**
   - Investigate which college produces the most and best NBA players.

3. **Team Performance:**
   - Identify if there is a specific team that players perform the best on.

4. **Draft Number and Career Length:**
   - Analyze which draft numbers produce players with the longest careers.

### Anomaly Detection

1. **Breakout Seasons:**
   - Identify players who had the most exceptional seasons.

2. **Age Analysis:**
   - Determine the oldest and youngest teams to play in a season.

### Analyzing Trends

1. **Physical Attributes:**
   - Explore how the physical attributes of players have changed over time.

2. **International Player Trends:**
   - Analyze the trends in the number and performance of non-US players in the league.

3. **Undrafted Players:**
   - Investigate how the numbers and performance of undrafted players have changed.

## Methodology

- **Finding Patterns**: Linear Regression

    - For finding patterns in the data, I've chosen linear regression because of its ease of use and simplicity in finding correlations between features.

- **Anomaly Detection**: One-class SVM

    - One-class SVM is useful in finding abnormalities in datasets with high-dimensionality. 

- **Analyzing Trends**: ARIMA (AutoRegressive Integrated Moving Average) 

    - ARIMA is a powerful time series tool and it's ideal in finding and analyzing trends in temporal data.

## Sources:

- [NBA Players - kaggle.com](https://www.kaggle.com/datasets/justinas/nba-players-data)