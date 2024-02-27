# X Sentiment Analysis

This project fetches tweets from X using the Tweepy library and performs sentiment analysis on them using TextBlob.

## Description

This Python script connects to the X API using Tweepy to fetch tweets containing a specified keyword. It then analyzes the sentiment of these tweets using TextBlob, which provides a polarity score indicating whether the sentiment is positive, negative, or neutral.

## Installation

1. Clone the repository:

```
git clone https://github.com/SSMarzooqi/X-sentiment-analysis.git
```

2. Install the required dependencies:

```
pip install tweepy textblob
```

3. Replace the placeholder X API credentials with your own in the script (`consumer_key`, `consumer_secret`, `access_token`, `access_token_secret`).

4. Run the script:

```
python sentiment_analysis.py
```

## Usage

Modify the `keyword` variable in the script to specify the keyword you want to search for in tweets. You can also adjust the `count` parameter to fetch more or fewer tweets.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
