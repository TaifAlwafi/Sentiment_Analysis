
# Abstract
This project aimed to use classification models to predict how a person feels about the coronavirus. Impacts of the pandemic, such as economic strife, and unprecedented restrictions on social contact have threatened people's mental health. By tweets data provided from [Kaggle](https://www.kaggle.com/gpreda/covid19-tweets) with logistic regression model. the clinics will be able to identify those needing help and treatment by classifying them tweets.

# Design

This project was developed during the online data science bootcamp at SDAIA. I obtained the data from [Kaggle](https://www.kaggle.com/gpreda/covid19-tweets), and it presents tweets about Coronavirus which contain words such as Corona-19, Coronavirus etc. I used ``SentimentIntensityAnalyzer`` to be labelling data.
Machine learning techniques are useful in understanding the sentiment of the people about a this virus. I classify tweets them as either positive or negative, I can help people detect sentiment about pandemic and contacting with clinic to avoid risk mental health.

# Data
The dataset contains 179108 tweets (179108 rows × 13 columns). A features include location of user and hashtags and retweet and etc. The dataset contains 13 features although I used one feature ``text``  and I added  ``Label`` column contain the tweet sentiment.
# Algorithms

### Data Preprocessing
Preprocessing the ``text`` feature using the following NLP techniques : Converting to lowercase, remove text in square brackets, remove links, Remove punctuation, remove words containing numbers, removing stop words and Lemmatization.

### Models
Logistic regression,Support vector machine, Naive bayes, and neural network classifiers were used and after training  the logistics regression model got the highest accuracy.

 
### Model Evaluation and Selection

The score for logistic regression is <br />
- Training:  99.07%
- Test set:  94.44%

The score for svm is  <br />
- Training:  96.22%
- Test set:  93.96% 

The score for Naive bayes is <br />
- Training:  91.23%
- Test set:  84.40%

accuracy for Neural network : 0.8672 

# Tools
- Numpy and Pandas for data manipulation
- Scikit-learn for modeling
- re for clean data 
- tensorflow and keras for neural network model
- nltk for natural language processing
- Matplotlib, Seaborn and plotly for plotting


