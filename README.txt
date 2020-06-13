SMS Spam Filter & Naive Bayes to predict flower species

Language: R
Editor: RStudio (v1.2.1335)
Description:Performed NLP to classify legitimate and spam SMS using Naive Bayes.
Used Naive Bayes Classifier to predict the species of flowers.

NOTE: 
For the model of predicting flower species in-built dataset called 'iris' was used from RStudio.
Link for SMS text dataset: https://drive.google.com/file/d/1odIytheawV5KAxVCQHvCn4p2BvWXyPAc/view?usp=sharing
Packages: tm, wordcloud, e1071, gmodels, klaR
Model: Naive Bayes, tm (Text Mining)

OVERVIEW:
SMS Spam Filter:
-Load data
-Use tm to clean sms text
-Split into train and test datasets
-Subset spam and ham datasets
-Visualize word frequency and find frequent words
-Train Naive Bayes on training data
-Use trained model to predicted cases from test set
-Create Confusion Matrix to evaluate model

Predicting flower species:
-Load data
-Split dataset into train and test set
-Apply Naive Bayes on train set
-Predict species from test set using trained model
-Check the accuracy by creating a table for actual and predicted species
