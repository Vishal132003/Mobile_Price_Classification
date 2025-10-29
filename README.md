📱 Mobile Price Range Prediction
🧩 Problem Statement

Bob has started his own mobile company and wants to compete with big brands like Apple and Samsung.
However, he struggles to estimate the price range of the mobile phones his company develops.
In the competitive smartphone market, pricing cannot be done by guesswork.

To solve this, Bob collected sales data from various companies and wants to find the relationship between mobile features (like RAM, internal memory, battery power, etc.) and their selling price.

Your task is to build a machine learning model that predicts the price range of a mobile phone rather than the exact price.

🚀 Solution Approach

This project implements a machine learning pipeline to predict the price range of mobile phones based on their features.

1. Data Loading and Exploration

Load the training and testing datasets.

Examine their structure, data types, and distributions.

Understand the relationships between features and the target variable (price_range).

2. Data Preprocessing

Handle differences between the training and test datasets:

Remove unnecessary columns such as id from the test set.

Ensure both datasets have the same feature structure and order.

Perform any necessary normalization or feature scaling.

3. Model Selection and Training

Train multiple machine learning classification models to identify the one with the best performance:

K-Nearest Neighbors (KNN)

Naive Bayes

Logistic Regression

Support Vector Machine (SVM)

4. Model Evaluation

Evaluate model performance using metrics like:

Accuracy

Precision

Recall

F1-Score

Generate a classification report for comparison.

5. Prediction on Test Data

Use the best-performing model (SVM) to predict the price range of mobiles in the test dataset.

6. Output Generation

Add the predicted price_range column to the test dataset.

Save the final output to a CSV file named Final_price.csv.

🧠 Technologies Used

Python

NumPy

Pandas
