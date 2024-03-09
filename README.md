# Twitter Spam Bot Detection Script

## Overview
This Python script is designed to identify potential spam bots on Twitter based on certain characteristics commonly associated with such accounts. It utilizes the Twitter API through Tweepy library to search for tweets containing a specific keyword and then checks the users who posted those tweets for spam bot characteristics.

## Requirements
- Python 3.x
- Tweepy library
- Twitter API credentials (consumer key, consumer secret, access token, access token secret)

## Installation
1. Install Python 3.x if you haven't already: https://www.python.org/downloads/
2. Install Tweepy library using pip:

3. Obtain Twitter API credentials by creating a Twitter Developer account and creating a new app: https://developer.twitter.com/en/apps
4. Replace the placeholders in the script (YOUR_CONSUMER_KEY, YOUR_CONSUMER_SECRET, YOUR_ACCESS_TOKEN, YOUR_ACCESS_TOKEN_SECRET) with your actual API credentials.

## Usage
1. Open the script in a text editor or Python IDE.
2. Modify the `keyword` variable to specify the keyword you want to search for.
3. Adjust the `num_tweets` variable to set the number of tweets to search through.
4. Run the script using Python:

3. Obtain Twitter API credentials by creating a Twitter Developer account and creating a new app: https://developer.twitter.com/en/apps
4. Replace the placeholders in the script (YOUR_CONSUMER_KEY, YOUR_CONSUMER_SECRET, YOUR_ACCESS_TOKEN, YOUR_ACCESS_TOKEN_SECRET) with your actual API credentials.

## Usage
1. Open the script in a text editor or Python IDE.
2. Modify the `keyword` variable to specify the keyword you want to search for.
3. Adjust the `num_tweets` variable to set the number of tweets to search through.
4. Run the script using Python: python twitter_spam.py
