# Deep-learning-challenge Report

# Overview:

The purpose of this analysis was to "create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup".

# Results: 

N/A; model was not running, could not produce evaluation metrics

# Data Preprocessing

The features for this model consisted of applicationo type, affiliatino, classification, use case, organizatino type, status, income classification, special cnosideration, and ask amount. Using these features, the model aimed to predict whether or not an orginzation was/will be "successful" (if the money was used effectively). The ein and name columns were removed because they were not a measure of success. Certain rare classifications and application types were removed below a certain threshold, as their infrequency made them irrelevant. 

# Compiling, Training, and Evaluating the Model

I used 3 dense layers, 2 hidden with relu activatino functions and 1 output with a sigmooiod activation function. Unfortunately, I tried changing the activatino functions, adding layers, changing the amuont of epochs, but was not able to get the model running. 
