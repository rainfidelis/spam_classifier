## Project Description

Spam detection is a major application of Machine Learning today. Mostly used by email providers, spam detection systems enable them catch fishy and potentially fraudulent emails, typically sending them over to 'Junk Mail' or 'Spam' folders.

In this project, I will be building a spam detection classifier for SMS messages using the Naive Bayes algorithm. The classifier should be able to look at an SMS and classify it either as spam or as 'ham' (a category reserved for messages that are not spam). 

Before we progress, it's important to note what spammy messages could look like. These are often unsolicited messages mass sent to individuals for advertising, phishing, or other fraudulent purposes. Designed to be enticing, spam messages often contain words like 'win', 'winner', 'free', 'cash', 'prize', etc. to ensure you open them. They may also use a lot of exclamation marks or be written in all-caps to make them noticeable.

The goal of this project is to build a model that correctly identifies these messages, making it easier to filter them out and keep them from getting to unsuspecting recipients. This is a binary classification problem where each message will be classified as 'Spam' or 'Not Spam'. The resulting model should be useful for predicting spam messages on data it hasn't "seen" before.


## The Data

The data for this project is a collection of SMS messages from mobile phones made publicly available by their recipients for research purposes. The data is available for download on the UCI Machine Learning Repository, and can be found [here](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection). 

For this project, the file has been downloaded and is named `SMSSpamCollection`.


## Requirements
The following packages were required for this project:
+ python
+ pandas
+ numpy
+ matplotlib
+ seaborn
+ sklearn