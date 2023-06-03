# What Social Media Platform is This?

This repository holds the data and code for Team OSU Math's submission for the Erdős institute's Spring 2023 Data Science Bootcamp.

## Cleaning and Exploratory Analysis

Cleaning and EDA for each data source is performed in the instagram_data, reddit_data, sentiment140-twitter_data, twitter_stream, and youtube_data folders. The data sources are synthesized and features are computed in the full_data folder. The data is down-sampled to give balanced class labels in the max72k_data.


## Training Models

Logistic regression models are trained in the logistic_regression folder, while decision trees and random forests are trained in the tree-forest folder.


## Data Sources

Reddit data link: https://www.kaggle.com/datasets/jerryqu/reddit-conversations
All subreddit and user tags are removed. E.g. '/r/pizza' -> ''

YouTube data: https://www.kaggle.com/datasets/gaurav2022/youtube-scrapped-data  (NOT USED ANYMORE)

YouTube comment scraper: https://github.com/egbertbouman/youtube-comment-downloader/archive/master.zip

Random YouTube video generator: https://perchance.org/youtube-video
