# John Wick 4 Twitter Analysis

![John Wick 4](johnwick4_video.gif)

Welcome to the John Wick 4 Twitter Analysis repository, where we delve into the dynamic world of Twitter to perform an in-depth analysis of conversations, sentiments, and trends surrounding the movie "John Wick 4." This analysis is conducted within two days of the movie's release, providing valuable insights into the immediate public reception of this action-packed film.

This repository contains Python scripts for scraping and analyzing tweets related to "John Wick 4," as well as a Power BI dashboard for visualizing the Twitter data.

## Table of Contents

1. [Overview](#overview)
2. [Scraping Tweets](#scraping-tweets)
3. [Analyzing Tweets](#analyzing-tweets)
4. [Power BI Dashboard](#power-bi-dashboard)
5. [Usage](#usage)
6. [Inference](#inference)

## Overview

The "John Wick 4 Twitter Analysis" project focuses on gathering and analyzing Twitter data related to the movie "John Wick 4." The project includes three main components:

- **Scraping Tweets**: Python script (`johnwick4_twitter_scraping.ipynb`) that scrapes tweets using the `snscrape` library and saves them to a CSV file.

- **Analyzing Tweets**: Python script (`johnwick4_twitter_analysis.ipynb`) that analyzes the scraped Twitter data, including sentiment analysis, hashtag extraction, character mentions, and more.

- **Power BI Dashboard**: A Power BI file (`johnwick4_powerbi.pbix`) that provides interactive visualizations of the Twitter data, allowing you to explore various aspects of the tweets, including countries, popular characters, sentiment, and more.

## Scraping Tweets

The `johnwick4_twitter_scraping.py` script uses the `snscrape` library to scrape tweets related to "John Wick 4." It collects data such as tweet content, date, location, retweets, likes, and views and stores them in a CSV file.

## Analyzing Tweets

The `johnwick4_twitter_analysis.ipynb` notebook is designed to provide comprehensive insights into the Twitter data related to "John Wick 4." It performs a variety of data analysis tasks, enabling you to gain a deeper understanding of the collected tweets:

- **Sentiment Analysis** : The script utilizes the VADER sentiment analysis tool to determine the sentiment of each tweet. Sentiment scores are categorized as positive or negative, allowing you to gauge the overall sentiment of Twitter users regarding the movie.

- **Hashtag Extraction** : It extracts hashtags from each tweet, helping you identify the most popular hashtags associated with "John Wick 4." These hashtags provide valuable insights into trending topics and discussions related to the movie.

- **Character Mentions** : The analysis script identifies mentions of characters from the movie, such as "John Wick," "Bowery King," and others. You can explore which characters are most frequently mentioned in tweets.

- **Word Processing** : To enhance data quality, the script processes tweet text by removing URLs, mentions, hashtags, stop words, and emojis. This results in cleaner and more informative text data for further analysis.

- **Top Words Used** : The script compiles a list of the top 10 most frequently used words in the tweets. This information gives you an idea of the common themes and topics discussed in the Twitter conversations.

- **Country-Based Analysis** : Although it's slower due to API usage, the script attempts to determine the user's country based on their location data. It provides insights into which countries have the most significant Twitter activity related to "John Wick 4."

- **Top Liked and Retweeted Tweets** : You can explore the tweets that received the most likes and retweets. This section highlights the most engaging content related to the movie.

- **Total Tweets by Hours** : The script categorizes tweets by the hour they were posted, allowing you to visualize how Twitter activity varies throughout the day.

The results of these analyses are saved in CSV files, enabling further exploration and visualization using tools like Excel or, more conveniently, the included Power BI dashboard.


## Power BI Dashboard

The `johnwick4_powerbi.pbix` Power BI file provides an interactive dashboard for visualizing the Twitter data. You can explore:

- Tweets by country
- Most popular characters mentioned in tweets
- Most liked tweets
- Most retweeted tweets
- Sentiment analysis in a pie chart
- Total tweets by hours

The dashboard offers a visually stunning way to understand and explore the Twitter data related to "John Wick 4."

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Run the `johnwick4_twitter_scraping.ipynb` script to scrape Twitter data and save it to a CSV file.
3. Run the `johnwick4_twitter_analysis.ipynb` script to analyze the data and generate CSV files with the results.
4. Open the `johnwick4_powerbi.pbix` file in Power BI to explore the visualizations.

## Inference

The sentiment analysis of the tweets revealed that the majority of the tweets about the movie were positive. There was a significant amount of engagement surrounding the movie on Twitter.

Furthermore, the analysis of the most popular characters revealed that John Wick was the most talked-about character, followed by Bowery King. The data can also be filtered by country, providing insights into the regional popularity of the movie.

Overall, this project provides a comprehensive analysis of the Twitter activity surrounding the release of "John Wick 4." The insights gained from this analysis could be useful for marketing and advertising purposes, as well as for understanding audience reactions to the movie.


Enjoy exploring and analyzing Twitter data related to "John Wick 4" with this project!

