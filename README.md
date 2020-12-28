# Twitter-Trending-NER-Sentiment-Analysis
Mining Tweets from twitter & perform NLP analysis & Pulse check


![preview](https://cdn.pixabay.com/photo/2013/06/07/09/53/twitter-117595_960_720.png)
This is a quick and dirty way to get a sense of what's trending on Twitter related to a particular Topic. For my use case, I am focusing on the city of Seattle but you can easily apply this to any topic.



This Notebook:

*   Scrapes Tweets related to the Topic mentioned.
*   Extracts relevant Tags from the text (NER: Named Entity Recognition).
*   Does Sentiment Analysis on those Tweets.
*   Provides some visualizations in an interactive format to get a 'pulse' of what's happening.

Tweepy - scrape Twitter data.

Flair - NER / Sentiment Analysis. 

Seaborn - visualizations.


The Twitter scrape code here was taken from: https://bhaskarvk.github.io/2015/01/how-to-use-twitters-search-rest-api-most-effectively.
My thanks to the author.

We need to provide a Search term and a Max Tweet count. Twitter lets you to request 45,000 tweets every 15 minutes so setting something below that works.

 
