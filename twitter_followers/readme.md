# azfunc-twitter-followers
Azure function to get new followers and retweet tweets with particular hashtag

👉 A simple Azure Function based Twitter bot that retweets and follows based on a given #tag. Generates followers at approx. 200 per month. Choose a topic and update line 25 to query Twitter for a recent tweet, retweet it and follow the original tweeter.

Application settings / environment variables required:

📌TWITTER_CONSUMER_KEY   
📌WITTER_CONSUMER_SECRET   
📌TWITTER_ACCESS_TOKEN  
📌TWITTER_ACCESS_TOKEN_SECRET

Blot post : https://sajeetharan.com/2019/12/22/simple-azure-function-that-can-get-you-200-followers-in-a-month/