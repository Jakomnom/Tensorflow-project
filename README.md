# Tensorflow-project

### Audiobook Customer Churn Prediction
#### Overview
This project involves creating a machine learning algorithm to predict whether a customer will make another purchase from an Audiobook company. The goal is to identify customers who are likely to return and focus marketing efforts on them. This not only saves resources but also helps identify key metrics that influence customer retention.

#### Problem Statement
You are provided with a dataset in a CSV format containing various customer-related variables. These variables include Book length in minutes (average and sum), Price paid (average and sum), Review (as a Boolean variable and out of 10), Total minutes listened, Completion rate (ranging from 0 to 1), Support requests (number), and the time elapsed since the last visit minus the purchase date (in days).

The objective is to create a machine learning model that predicts whether a customer will make another purchase within the next 6 months based on their activity and engagement over the past 2 years. Customers are divided into two classes: those who will buy again (1) and those who won't (0).

#### Dataset
The dataset provided contains the following fields:

Customer ID (arbitrary identifier)<br> 
Book length in minutes (average and sum)<br> 
Price paid (average and sum)<br> 
Review (Boolean and out of 10)<br> 
Total minutes listened<br> 
Completion rate (0 to 1)<br> 
Support requests (number)<br> 
Last visited minus purchase date (days)<br> 

#### Target
The target variable is binary, representing whether a customer will make another purchase:

1: The customer is likely to buy again<br> 
0: The customer is unlikely to buy again

#### Timeframe
The prediction window spans the next 6 months following a 2-year period of customer activity. If a customer does not convert within these 6 months, it's assumed they may have switched to a competitor or are no longer interested in the Audiobook service.

#### Implementation
This is a classification problem, and the primary task is to develop a machine learning algorithm capable of predicting whether a customer will make another purchase. Various classification algorithms and techniques can be explored to achieve this goal.
