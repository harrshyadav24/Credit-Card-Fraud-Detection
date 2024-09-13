
# Credit Card Fraud Detection

Fraud Transactions through Credit Cards have increased a lot nowadays which results in a loss of credit card companies. So, I have implemented machine learning models to predict these fraud transactions in realtime.


## Dataset

There are total 31 features – Time, Amount, Class (fraud (1) or non-fraud (0)), V1-V28 (might be name, age, place, transaction id, receiver’s account number, credit card number, etc scaled down between -5 to 5). Time and Amount were big numbers and rest of the features are small numbers mostly between (-5 to 5) so the time and amount were scaled down (-5 to 5) using robustscaler.

## Method

The dataset is divided into two parts: 80% for training and 20% for testing purpose. Now the Logistic Regression, Decision Tree Classifier, and Random Forest Classifier were trained on training data and tested on testing data.

## Results

Below are the results for these models:

- Logistic Regression
![App Screenshot](https://github.com/harrshyadav24/Credit-Card-Fraud-Detection/blob/main/Screenshot%202024-09-13%20140941.png)

- Decision Tree Classifier
![App Screenshot](https://github.com/harrshyadav24/Credit-Card-Fraud-Detection/blob/main/Screenshot%202024-09-13%20140959.png)

- Random Forest Classifier
![App Screenshot](https://github.com/harrshyadav24/Credit-Card-Fraud-Detection/blob/main/Screenshot%202024-09-13%20141017.png)

From Exploratory Data Analysis we have found that Fraudulent transactions happened only for small amounts (below 5000).