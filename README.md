# Twitter Sentiment Analysis

This code performs Twitter sentiment analysis, allowing you to analyze the sentiment of tweets containing specific keywords, and then visualize the results using graphs. The sentiment analysis is done using the TextBlob library, which performs a basic Natural Language Processing (NLP) technique called sentiment analysis.

Firstly, it imports necessary libraries including tweepy for connecting to the Twitter API, textblob for sentiment analysis, matplotlib and numpy for data visualization, pandas for data manipulation, and sys and re for system functionality and regular expressions. It also imports Twitter authentication credentials from a separate file called twitter_credentials.

The code then defines three classes: TwitterClient, TwitterAuthenticator, and TwitterStreamer. TwitterClient is used to access various methods of the Twitter API to retrieve tweets and user information, while TwitterAuthenticator is used to authenticate the Twitter application using OAuthHandler. TwitterStreamer is used to stream and process live tweets based on a set of keywords.

The TweetAnalyzer class is used to perform sentiment analysis on tweets using the TextBlob library, as well as cleaning and organizing the data into a pandas DataFrame.

The code then defines a geocode variable which specifies the location and radius to search for tweets. It loops through each geocode and retrieves tweets containing a set of keywords, which are specified later in the code. It then applies sentiment analysis to the tweets and visualizes the results using a scatter plot.
