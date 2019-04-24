# Credit-Card-Defaults
A juptyer file in which I run several algorithms on various levels of pre-processed datasets to compare there performance

Predicting the Default of Taiwanese Credit Card Holders

Objective: 
To predict the probability of payment default in October 2005 among Taiwanese credit card holders. 
This is based on demographic data of 30,000 Taiwanese customers and 6 months of previous payment activity.

Dataset:
	The dataset was acquired from UCI.edu. It consists of the customer’s credit card limit, followed by 4 demographic variables, 
  sex (1=male, 2=female), education (1 = graduate school; 2 = university; 3 = high school; 4 = others), marital status (1 = married; 
  2 = single; 3 = others), and age in years. The next 6 variables are the number of months that client has made a late payment followed 
  by the next 6 months of statement balances and the amount of the payments made by the customer. The last column consists of the class 
  with 1 indicating there was a default in October 2005 and 0 indicating no default. 
  
https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

Methodology:
	Our methodology will consist of dividing our data into a training and testing set and running several algorithms on the dataset to
  determine which is the best predictor. Some of the possible algorithms we will use are K-nearest neighbors, Support Vector Machines, 
  Linear Regression and possibly Non-Linear Regression, Neural Networks and Naïve Bayes. We will also use principal component analysis 
  to determine the most important factors in whether an individual will default or not.
