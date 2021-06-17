# Coronavirus-Tweet-Sentiment-Analysis

Our objective is to build a classification model to predict the sentiment of COVID-19 tweets.The tweets have been pulled from Twitter and manual tagging has been done then.
The names and usernames have been given codes to avoid any privacy concerns.

We are given the following information:
* Username: Unique user-IDs of the users
* Location: Location of the user
* Tweet At: Date at which the tweet was made
* Original Tweet: The exact tweet
* Sentiment: Sentiment of the tweet



<h3><b> Approaching the Problem Statement: </b></h3>

* Built a LSTM RNN model to predict the sentiment associated with a particular tweet consisting of neutral, positive and negative sentiments
* Employed essential text preprocessing techniques such as text cleaning, calculation of document complexity, used WordCloud to check token frequency.
* Optimized the model using an optimal vocabulary size, followed by OneHot encode, padding, used Embedding layers to vectorize our tokens before feeding it to the LSTM.
* Achieved an overall precision of 78%, 76% and 64% for positive, negative and neutral sentiments respectively and an overall accuracy of 75%.
