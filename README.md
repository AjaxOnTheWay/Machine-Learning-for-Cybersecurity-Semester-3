Machine Learning for Cyber Security

Course Overview

This repository contains practical implementations and labs focused on applying machine learning techniques to solve cybersecurity challenges. The course covers time series analysis, classification algorithms, anomaly detection, and specialized security tasks such as URL classification, spam detection, and CAPTCHA solving.

Repository Structure

Exp1_time_series_decomposition.ipynb: Lab notebook for decomposing seasonal and trend components.

Exp2_ddos_prediction_arima.ipynb: Lab notebook for DDoS attack prediction using ARIMA time series forecasting.

Exp3_cyber_attack_ensemble.ipynb: Lab notebook for classifying cyber-attacks using Random Forest and Gradient Boosting.

Exp4_url_logistic_regression.ipynb: Lab notebook for malicious URL classification using Logistic Regression.

Exp5_url_svm_classification.ipynb: Lab notebook for malicious URL classification using Support Vector Machines (SVM).

Exp6_url_feature_engineering_anomaly.ipynb: Lab notebook for detecting abnormal URL patterns via feature engineering and Isolation Forest.

Exp7_captcha_solver.ipynb: Lab notebook for solving CAPTCHA challenges using image segmentation and an MLP Neural Network.

Exp8_email_spoofing_detection.ipynb: Lab notebook for detecting email spoofing patterns via SPF/DKIM/DMARC header analysis.

Exp9_email_spam_classification.ipynb: Lab notebook for email spam classification using TF-IDF, Multinomial Naive Bayes, and Linear SVM.

Exp10_kmeans_network_events.ipynb: Lab notebook for clustering network events into normal and abnormal categories using K-Means.

Exp11_decision_tree_db_injection.ipynb: Lab notebook for detecting malicious database SQL injections using a Decision Tree classifier.

Exp12_wsn_context_detection.ipynb: Lab notebook for context-based malicious event detection in Wireless Sensor Networks (WSN).

README.md: Documentation and setup instructions for the lab repository.

Lab Exercises

1. Time Series Analysis & Forecasting

Task 1: Perform a time series decomposition of a dataset with seasonal and trend components. [CO1]

Task 2: Apply time series forecasting methods (ARIMA or Prophet) on historical network traffic data to predict potential DDoS attacks. [CO1]

2. Classification & Ensemble Methods

Task 3: Implement an ensemble learning method (e.g., Random Forest or Gradient Boosting) to classify cyber-attacks. [CO2]

Task 4: Build a logistic regression model to classify URLs as either legitimate or malicious. [CO2]

Task 5: Apply a Support Vector Machine (SVM) to classify URLs into legitimate and malicious categories. [CO2]

Task 11: Develop a decision tree classifier to detect malicious data injections within databases. [CO5]

3. Anomaly Detection & Feature Engineering

Task 6: Detect abnormal patterns in a set of URLs using feature engineering techniques. [CO3]

Task 10: Use k-means clustering to classify network events into normal and abnormal categories. [CO4]

Task 12: Develop a model using context (timestamp, source IP, event type) to detect malicious events in wireless sensor networks. [CO5]

4. Text & Pattern Analysis

Task 7: Build a machine learning model capable of solving CAPTCHA challenges. [CO3]

Task 8: Analyze an email dataset to detect patterns of email spoofing. [CO3]

Task 9: Implement a text classification algorithm (e.g., Naive Bayes or SVM) to classify emails as spam or not spam. [CO4]

Setup Instructions

Clone the repository:

git clone https://github.com/AjaxOnTheWay/Machine-Learning-for-Cybersecurity.git
cd Machine-Learning-for-Cybersecurity


Install the required dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn statsmodels pillow jupyter


Launch Jupyter Notebook:

jupyter notebook
