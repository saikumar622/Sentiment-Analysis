# Sentiment-Analysis
We are using Amazon Alexa Reviews dataset (3150 reviews), that contains: customer reviews, rating out of 5, date of review, Alexa variant
First we generate sentiment labels: positive/negative, by marking positive for reviews with rating >3 and negative for remaining
Then, we clean dataset through Vectorization Feature Engineering (TF-IDF) - a popular technique
Post that, we use Support Vector Classifier for Model Fitting and check for model performance (we are getting >90% accuracy)
Last, we use our model to do predictions on real Amazon reviews using: a simple way and then a fancy way 

#Deployment 
