
# Abstract
This project aimed to use classification models to predict how a person feels about the coronavirus.  Impacts of the pandemic, such as economic strife, and unprecedented restrictions on social contact have threatened people's mental health. This need led to the development of an intervention strategy. A logistic regression model was developed on data provided from Kaggle.  Using machine learning models, the clinics will be able to identify those needing help and treatment by classifying tweets. 

# Design
This project was developed during the online data science bootcamp at SDAIA. I obtained the data from Kaggle, and it presents tweets about Coronavirus which contain words such as Corona-19, Coronavirus etc. I used ``SentimentIntensityAnalyzer`` to be labelling data. Classifying tweets to positive negative helps developed clinic intervention strategy to avoid risk mental health.

# Data
The dataset contains 179108 tweets (179108 rows × 13 columns). A few features include location of user and hashtags and retweet. Nearly the dataset contains 13 features although I used one feature 'text' in training model

# Algorithms

### Data Preprocessing
preprocess ``text`` feature using some NLP techniques like: Converting to lowercase, remove text in square brackets, Remove links, Remove punctuation, Remove words containing numbers, Removing stop words and Lemmatization.
<!-- 
### Models
Logistic regression, naive bayes, neural Network, and support vector machine classifiers were used before settling on logistic regression as the model with strongest cross-validation performance.

### Model Evaluation and Selection
<!--  -->
<!-- 
Final Logistic regression scores: 99 features (7 numeric) with class weights

Accuracy 0.797
F1 0.791 micro, 0.679 macro
precision 0.792 micro, 0.722 macro
recall 0.797 micro, 0.658 macro
Holdout

Accuracy: 0.802
F1: 0.795 micro, 0.685 macro
Precision: 0.796 micro, 0.725 macro
Recall: 0.802 micro, 0.664 macro


# Tools
Numpy and Pandas for data manipulation
Scikit-learn for modeling
Matplotlib and Seaborn for plotting
Tableau for interactive visualizations -->

 -->
