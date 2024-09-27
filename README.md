## NLP with Disaster Tweets

![cover](https://github.com/user-attachments/assets/dc97846f-31b5-4789-9e53-7bd91c3e02dc)

## Objective

The goal of this competition is to predict which tweets are about real disasters and which ones are not. The process involves data cleaning and data preprocessing and developing a predictive model using Natural Language Processing (NLP) Techniques.

## Data Collection

I have sourced the "NLP with Disaster Tweets" dataset from kaggle.

https://www.kaggle.com/competitions/nlp-getting-started

This dataset contains 10000 records of tweets about disaster in different locations.

## Data Pre-Processing

- Imported the data and did some basic analysis.
- Cleaned the data with the help of RegEx (Regular Expression).
- Removed the stopwords with the help of nltk (Natural Language Toolkid Library).
- I have used Lemmatization to reduce words to their root form.
- Used Tfidf vectorizer to convert the text data into numeric form.

## Winning Model

- Applied various models and got the best f1 score of 79.65% in Random forest Classifier.
