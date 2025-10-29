##Mobile Price Range Prediction
Problem Statement
Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.

He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.

Bob wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.

In this problem you do not have to predict actual price but a price range indicating how high the price is

Solution Approach
This notebook addresses the problem by implementing a machine learning pipeline to predict the price range of mobile phones. The key steps involved are:

Data Loading and Exploration: Loading the training and testing datasets and examining their structure and content.
Data Preprocessing: Handling differences between the training and testing datasets, such as the presence of an 'id' column in the test set and ensuring consistent column order.
Model Selection and Training: Training several classification models (KNN, Naive Bayes, Logistic Regression, and SVM) on the training data to determine which model performs best at predicting the price range.
Model Evaluation: Assessing the performance of each trained model using appropriate metrics (e.g., classification report).
Prediction on Test Data: Using the best-performing model (SVM in this case) to predict the price range for the mobile phones in the test dataset.
Output Generation: Adding the predicted price range to the test dataset and saving the results to a new CSV file (Final_price.csv).
This approach allows Bob to utilize the insights gained from the sales data to estimate the price range of his company's mobile phones effectively.
