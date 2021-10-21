
Taif Alwafi 

# Abstract
This project aimed to use classification models to predict how a person feels about the coronavirus. Impacts of the pandemic, such as economic strife, and unprecedented restrictions on social contact have threatened people's mental health. By tweets data provided from [Kaggle](https://www.kaggle.com/gpreda/covid19-tweets) with logistic regression model. the clinics will be able to identify those needing help and treatment by classifying them tweets.

# Design

This project was developed during the online data science bootcamp at SDAIA. I obtained the data from [Kaggle](https://www.kaggle.com/gpreda/covid19-tweets), and it presents tweets about Coronavirus which contain words such as Corona-19, Coronavirus etc. I used ``SentimentIntensityAnalyzer`` to be labelling data.
Machine learning techniques are useful in understanding the sentiment of the people about a this virus. I classify tweets them as either positive or negative, I can help people detect sentiment about pandemic and contacting with clinic to avoid risk mental health.

# Data
The dataset contains 179108 tweets and 13 features : ``user_name``, ``user_location``, ``user_description``, ``user_created``,
       ``user_followers``, ``user_friends``, ``user_favourites``, ``user_verified``,
       ``date``, ``text``, ``hashtags``, ``source``, ``is_retweet`` . Although I used one feature ``text``  and I added  ``Label`` column contain the tweet sentiment.
# Algorithms

### Data Preprocessing
- Preprocessing the ``text`` feature using the following NLP techniques : Converting to lowercase, remove text in square brackets, remove links, Remove punctuation, remove words containing numbers, removing stop words and Lemmatization.
- labelling ``text`` feature using ``SentimentIntensityAnalyzer`` 0 for negative and 1 for positive.
### Models
Logistic regression,Support vector machine, Bernoulli naive bayes, and neural network classifiers were used and after training  the logistics regression model got the highest accuracy.

 
### Model Evaluation and Selection
All models were trained on 80/20 train vs test and based on the result of this experiment the logistics regression model was the best model according to accuracy metric. 
after choosing the logistics regression I applied Repeated Stratified KFold with 5-fold and gridsearch in order to tune the model.
The final result : 

The score for logistic regression is <br/>
- Training:  99.07%  <br/>
- Test set:  94.45%

The score for svm is  <br />
- Training:  96.22%
- Test set:  93.96% 

The score for Bernoulli naive bayes is <br />
- Training:  91.23%
- Test set:  84.40%

The score for Neural network is <br />
- Training:  91.23%
- Test set:  84.40%

# Tools
-  Pandas for data manipulation
- Scikit-learn for modeling
- re for clean data 
- tensorflow and keras for neural network model
- nltk for natural language processing
- Matplotlib, Seaborn and plotly for plotting


