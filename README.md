# Classifier-Comparison
Comparison of different classification models 

## Overview 

The lecture "Data Mining" at University introduced a variety of different classification algorithms. Naturally, I wanted to apply what I had learned, so the Kaggle Titanic Dataset seemed to be the perfect place to start. I, however, found myself confronted with a couple of problems before I could even get started:

* How to deal with missing values? Though the lecture introduced efficent ways of handling missing values, which of those should I use for best performance? 
* Which model should I use? A simple Decision Tree, a Support Vector Machine or a Naive Bayes? Perhaps a Random Forest? 

I decided to deal with missing values in four different ways:

* Dropping the entrys which contain missing values
* Impute with 0
* Impute with the attribute mean
* Impute using linear regression

The idea now is to train a model for each of those and compare them. The best performing model will then be used to make a contribution to the actual Kaggle Challange.
