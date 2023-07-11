README
# Practical Application Assignment 5.1: Will the Customer Accept the Coupon?

This repo contains practical application assignment 5.1 from Berkeley Engineering & Berkeley Haas Professional Certificate in Machine Learning and Artificial Intelligence.

## News article classification
Named Entity Recognition
1. News article classification
Background
The data used in this project comes from the Sharing News Online project which investigates why people share news on social media. (It is not a NLP/machine learning related research, but if you're interested in political economics or journalism, go ahead and check out their book.)
The authors also ask an interesting question: which topics of articles get shared?
The task of classifying news articles into different topics has to be done to perform this type of research.

Objectives
The goal for this project is to explore different feature extraction methods for supervised text classification of news articles. The workflow looks like:

Train a statistical text classification system.
Evaluate the prediction and analyze errors.
Imporve the model through experiments with different feature extraction methods.
Data
2284 news articles which are annotated with one of ten categories: Business, Entertainment, Health, Politics, Science/Technology, Society, Sports, War, Other and Error.

Data is not shared in this repo.

Method
I used logistic regression for the statistical model used different feature extraction methods for each experiment. 10-fold cross validation is used for testing.

Baseline system: bag-of-words
Experiment 1: Cleaning and treating abbreviations
Experiment 2: N-grams
Experiment 3: Stop words, TF-IDF
Experiment 4: Stemming
Experiment 5: WordNet synsets, hypernyms
Results
2. Named Entity Recognition