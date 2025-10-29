📱 Mobile Price Range Prediction
🧩 Problem Statement

Bob has started his own mobile company and wants to compete with big brands like Apple and Samsung. However, he struggles to estimate the price range of the mobile phones his company develops. In this competitive smartphone market, pricing cannot be done by guesswork.

To solve this, Bob collected sales data from various companies and wants to find the relationship between mobile features (like RAM, internal memory, battery power, etc.) and their selling price.

Your task is to build a machine learning model that predicts the price range of a mobile phone rather than the exact price.

🚀 Solution Approach

This project implements a machine learning pipeline to predict the price range of mobile phones based on their features.

1️⃣ Data Loading and Exploration

Load the training and testing datasets

Examine their structure, data types, and distributions

Understand relationships between features and the target variable (price_range)

2️⃣ Data Preprocessing

Handle differences between the training and test datasets:

Remove unnecessary columns like id from the test set

Ensure both datasets have consistent feature structures

Perform feature scaling or normalization if necessary

3️⃣ Model Selection and Training

Train and compare multiple classification models:

K-Nearest Neighbors (KNN)

Naive Bayes

Logistic Regression

Support Vector Machine (SVM)

4️⃣ Model Evaluation

Evaluate each model using metrics such as:

Accuracy

Precision

Recall

F1-Score

Generate and analyze the classification report

5️⃣ Prediction on Test Data

Use the best-performing model (SVM) to predict the price_range for mobiles in the test dataset

6️⃣ Output Generation

Add predicted price range to the test dataset

Save the results as Final_price.csv

🧠 Technologies Used

Python

NumPy

Pandas
