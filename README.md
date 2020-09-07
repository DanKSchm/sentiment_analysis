### Project description

By using tweepy the code extracts a wished number of last tweets given a twitter user name.
After that the tweets are collected into a dataframe and analysed by using a WordCloud and TextBlob for sentiment analysis.


## Requirements

you need to have installed following packages:

-> tweepy
-> textblob
-> wordcloud


## The workflow can basically be described as follows:

1) Create the authentication object
   Set the access token und access token secret
   Create the API object while passing in the auth information

2) Extract a number of tweets from a twitter user by using an input function

3) Create a dataframe with a column called Tweets

4) Create a function to clean the tweets

5) Create a function to get the subjectivity

6) Create a function to get the polarity

7) Plot a World Cloud

8) Create a funciton to compute the negative, neutral and positive analysis



Hint: 
Due to safety reason you have to use your own keys and secrets in order to be able to use the code.
