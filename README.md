# UDACITY | Data Analyst Nanodegree Program
# Project 4 Wrangle and Analyze Data

## Overview

The dataset used in this project is the tweet archive of twitter user [@dog_rates](https://twitter.com/dog_rates), also known as WeRateDogs. It is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10, and the numerators are very often greater than 10. WeRateDogs has over 4 million followers and has received international media coverage.

The main goal of the project is wrangling WeRateDogs Twitter data to create interesting analysis and visualizations. Since the twitter archive contains very basic tweet information, there was additional data gathering for getting more useful for further analysis information.

I gathered, assessed and cleaned data, analyzed the dataset and then communicated my findings about it in [act_report.pdf](https://github.com/aquamila/UDACITY_Wrangle_and_Analyze_Data/blob/master/act_report.pdf). 

I shared all the steps in the Jupiter Notebook file [wrangle_act.ipynb](https://github.com/aquamila/UDACITY_Wrangle_and_Analyze_Data/blob/master/wrangle_act.ipynb) and in [wrangle_report.pdf](https://github.com/aquamila/UDACITY_Wrangle_and_Analyze_Data/blob/master/wrangle_report.pdf) in a summary form..

## Data

1. [twitter_archive_enhanced.csv](https://github.com/aquamila/UDACITY_Wrangle_and_Analyze_Data/blob/master/twitter_archive_enhanced.csv) which is the WeRateDogs twitter account archive in csv-format and was downloaded manually [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced.csv). 

2. [image_predictions.tsv](https://github.com/aquamila/UDACITY_Wrangle_and_Analyze_Data/blob/master/image_predictions.tsv) with predictions what breed of dog (or other object, animal, etc.) is present in each tweet. This file was downloaded programmatically using the Requests library from the [following url](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv). 

3. [tweet_json.txt](https://github.com/aquamila/UDACITY_Wrangle_and_Analyze_Data/blob/master/tweet_json.txt) which contains entire tweets from WeRateDogs Twitter archive since *twitter_archive_enhanced.csv* contains only basic information. tweet_json.txt was created programmatically by quering the Twitter API for entire tweet's JSON data using the tweet IDs in the WeRateDogs Twitter archive and Python's Tweepy library.

4. [twitter_archive_master.csv](https://github.com/aquamila/UDACITY_Wrangle_and_Analyze_Data/blob/master/twitter_archive_master.csv) containing all that data assesed and clean.

## Technologies Used

- Jupiter Notebook
- Python with the following libraries and modules:
  - NumPy
  - pandas
  - Matplotlib
  - Seaborn
  - Requests
  - Tweepy
  - json
  - sys 
  - time
  - datetime
  - re
  - BeautifulSoup
- Twitter API
