# WeRateDogs-Twitter-Data-Wrangling

### Date Created
This project has been created at 15/02/2021.

### Description
In this project, We will use [tweepy](https://docs.tweepy.org/en/v3.2.0/api.html#API) library to query Twitter's API for data included in the [WeRateDogs](https://twitter.com/dog_rates) Twitter archive. This data will include retweet count and favorite count. We will develop some code to create an API object that will be used to gather Twitter data. After querying each tweet ID, we will write its JSON data to a tweet_json.txt file with each tweet's JSON data on its own line. We will then read this file, line by line, to create a pandas DataFrame that will be assessed and cleaned. Finally, we will work on analyzing our wrangled data.
This project is a part of 'Data Analyst Nanodegree Program' on Udacity

### Jupyter Notebook File
wrangle_act.ipynb

### Data Files Used
twitter_archive_enhanced.csv, image-predictions.tsv, tweet_json.txt

### Note
For running the project the data files should be put in the same parent folder with the Jupyter notebook file
