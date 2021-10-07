
 T5: Online Data Science Bootcamp 

# COVID-19 Sentiment Analysis


## Introduction 

 - Background  <br />  
In late December 2019 a new (novel) coronavirus was identified in China causing severe respiratory disease including pneumonia. The disease caused as a result of infection is named - coronavirus disease (COVID-19). it has been categorised as an airborne High Consequence Infections Disease.
 
- Motivation <br />  
Nowadays, the Internet age has changed the way people express their opinions. This is mainly done through posts via social media etc. To express their emotions and opinions and exchange views on their daily lives, social media generates a large volume of sentiment data in the form of tweets, updates, etc. I used tweets contain the word Covid-19 to analyze their feelings and classify them into (positive-negative) .

- Importance <br />  
 Machine learning techniques are useful in understanding the sentiment of the people about a this virus.

## Problem statement

In this project, I try to implement a Twitter sentiment analysis model that helps to overcome the challenges of identifying the sentiments of the tweets. The necessary details regarding the dataset are:
The provided dataset **(COVID19 Tweets)** consists of 179108 tweets (179108 rows × 13 columns). The dataset can be found at [Kaggle](https://www.kaggle.com/gpreda/covid19-tweets). <br /> 

<!-- - Location: it refers location  <br /> 
- Tweet At: It refers to the name of the user that tweeted <br /> 
- Original Tweet: It refers to the text of the tweet  <br /> 
- Label:  the polarity of the tweet (positive or negative) <br /> 
 -->
```'user_name'`, 'user_location', 'user_description', 'user_created',
       'user_followers', 'user_friends', 'user_favourites', 'user_verified',
       'date', 'text', 'hashtags', 'source', 'is_retweet' ```
 
            
## Objective 

The use of data analysis that is one of the most important branches of the NLP and the goal in general: <br />

that the questionnaires and surveys are no longer sufficient to know the opinions of people in the presence of big data, so we now use sentiment analysis, In the sense of analyzing people's feelings and perspectives through what they write and benefiting from the experiences of others, and in particular, we want to know the people's Sentiment and emotions in the pandemic Covid -19

## Tools


- Model : Logistic Regression or Recurrent neural network  <br /> 
- Library : nltk  , re , pandas, numpy, seaborn and matplotlib  <br /> 
- Cloud service : Google colab


