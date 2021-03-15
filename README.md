# Fake-or-Real-news

The latter is possible through a natural language processing pipeline followed by a machine learning pipeline. It is how we would implement our fake news detection project in Python. It is another one of the problems that are recognized as a machine learning problem posed as a natural language processing problem. 

## Dataset

There are many datasets out there for this type of application, but we would be using the one mentioned [here](https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view). The data contains about 7500+ news feeds with two target labels: fake or real. The dataset also consists of the title of the specific news piece. 

The steps in the pipeline for natural language processing would be as follows:

Acquiring and loading the data

TF-IDF vectorizer{Cleaning the dataset

Removing extra symbols

Removing punctuations

Removing the stopwords

Stemming

Tokenization

Feature extractions}

Counter vectorizer with TF-IDF transformer

Machine learning model training and verification

##Machine Learning models

In this project we have used passive aggressive classifier, Support Vector Machine and Logistic Regression
