# Building-a-Spam-Filter-with-Naive-Bayes

#### **Context:**

In this guided project, we're going to apply the Naive Bayes algorithm to build a spam filter for SMS messages.  

To classify messages as spam or non-spam, we need to:  

1. Provide a computer with information of what spam looks like and what non-spam looks like.
2. The computer uses that knowledge to estimate probabilities for new messages - probabilities for spam and non-spam.
3. Finally, the computer classifies a new message based on the values of probabilities calculated in step 2 - if the probability for a spam is greater, then it classifies the message as spam. Otherwise, it classifies it as non-spam. In cases where these probabilities are near-equal, we may want a human to classify the message. 

#### **Goal:**

Our project here is a machine learning problem, specifically a classification problem. The goal of our project is to maximize the predictive ability of our algorithm. 

#### **Dataset:**  

Our task is to provide a computer with information on how to classify messages. To do that, we'll use the Naive Bayses algorithm on a dataset of 5,572 messages that have already been classified by humans.

This dataset can be downloaded from [The UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). For this project, I used a modified version of the dataset which contains fewer rows and is provided as an option to reduce code execution time. 

Note that due to the nature of spam messages, the dataset contains content that may be offensive to some users. 

**Note:** This code was written on RStudio.  
**Language:** R.  
**Packages:** readr, dplyr, stringr, purrr, tidyr.
