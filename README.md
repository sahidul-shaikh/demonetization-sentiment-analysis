# Spcial Media (Twitter) Mining - Demonetization Sentiment Analysis

# Problem Statement

The objective is to identify the various narratives given a certain topic and to label the narratives using some characteristic words/phrases. We will also tag the narratives with sentiments such as positive, negative or neutral.

## Context

The demonetization of ₹500 and ₹1000 banknotes was a step taken by the Government of India on 8 November 2016, ceasing the usage of all ₹500 and ₹1000 banknotes of the Mahatma Gandhi Series as a form of legal tender in India from 9 November 2016.

The announcement was made by the Prime Minister of India Narendra Modi in an unscheduled live televised address to the nation at 20:15 Indian Standard Time (IST) the same day. In the announcement, Modi declared circulation of all ₹500 and ₹1000 banknotes of the Mahatma Gandhi Series as invalid and announced the issuance of new ₹500 and ₹2000 banknotes of the Mahatma Gandhi New Series in exchange for the old banknotes.

## Dataset

The data contains 6000 most recent tweets on #demonetization. There are 6000 rows(one for each tweet) and 14 columns. 

Note:- The dataset and the problem statement are also available in [Kaggle](https://www.kaggle.com/arathee2/demonetization-in-india-twitter-data)

## The process we will follow is summarised below:

- Getting tweets talking about a certain topic
- Cleaning the tweets (removing stop words etc.) 
- Computing embeddings of tweets using pre-trained word embeddings (such as wor2vec)
- Computing tweet embeddings with sentiment by appending a 'sentiment score' to the 'tweet embeddings'
- Clustering the tweet-sentiment embeddings (each cluster representing a 'narrative')
- Identifying key characteristic phrases of each narrative using TF-IDF frequencies of commonly occurring phrases 

