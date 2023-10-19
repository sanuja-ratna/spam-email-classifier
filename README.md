# spam-email-classifier
This repository contains the Python code and documentation for the process of classifying spam emails.

Creating a spam email classification tool involves building a machine learning model to classify emails as either spam or not spam (ham). Here, we'll use Python and a common dataset for email classification known as the "SpamAssassin Public Corpus." We'll use a popular machine learning library, scikit-learn, for building and training the model. 

These are the steps that were taken to complete this project:
1. Import Libraries - import necessary libraries
2. Load the Dataset - download SpamAssassin Public Corpus dataset and load it into the Pandas DataFrame
3. Preprocess the Data - clean and preprocess the email text data (can use CountVectorizer to convert text into numerical format)
4. Split the Dataset - split the dataset into training and testing sets
5. Train the Model - train the machine learning model on the training data (for instance, Multinomial Naive Bayes classifier)
6. Evaluate the Model - evaluate the models' performance on the test data
7. Make Predictions - use trained model to classify new emails as spam or not spam by transforming email text and using the predict method 
