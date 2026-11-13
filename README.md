# Machine Learning for Cyber Security

## Course Overview
This repository contains practical implementations and labs focused on applying machine learning techniques to solve cybersecurity challenges. The course covers time series analysis, classification algorithms, anomaly detection, and specialized security tasks such as URL classification, spam detection, and CAPTCHA solving.

## Repository Structure
- `dataset/`: Contains the datasets used for time series decomposition and forecasting.
- `1.time_series_decomposition.ipynb`: Lab notebook for decomposing seasonal and trend components.
- `2.ARIMA-Prophet.ipynb`: Lab notebook for DDoS attack prediction using ARIMA and Prophet.
- `Exp3_cyber_attack_ensemble.ipynb`: Lab notebook for cyber-attack classification using Random Forest and Gradient Boosting.
- `Exp4_url_logistic_regression.ipynb`: Lab notebook for classifying URLs using Logistic Regression.
- `Exp5_url_svm_classification.ipynb`: Lab notebook for classifying URLs using Support Vector Machine (SVM).
- `Exp6_url_feature_engineering_anomaly.ipynb`: Lab notebook for detecting abnormal URL patterns using feature engineering.
- `Exp7_captcha_solver.ipynb`: Lab notebook for solving CAPTCHA challenges using machine learning.
- `Exp8_email_spoofing_detection.ipynb`: Lab notebook for detecting email spoofing patterns.
- `Exp9_email_spam_classification.ipynb`: Lab notebook for classifying spam vs. legitimate emails using Naive Bayes and SVM.
- `Exp10_kmeans_network_events.ipynb`: Lab notebook for clustering network events into normal and abnormal categories using K-Means.
- `Exp11_decision_tree_db_injection.ipynb`: Lab notebook for detecting malicious database injections using Decision Trees.
- `Exp12_wsn_context_detection.ipynb`: Lab notebook for context-based malicious event detection in wireless sensor networks.
- `requirements.txt`: Python dependencies required to run the notebooks.

## Lab Exercises
- **Task 1:** Perform a time series decomposition of a dataset with seasonal and trend components.
- **Task 2:** Using historical network traffic data, apply time series forecasting methods (like ARIMA or Prophet) to predict potential DDoS attacks.
- **Task 3:** Implement an ensemble learning method (e.g., Random Forest or Gradient Boosting) to classify cyber-attacks.
- **Task 4:** Build a logistic regression model to classify URLs as either legitimate or malicious.
- **Task 5:** Apply a Support Vector Machine (SVM) to classify URLs into legitimate and malicious categories.
- **Task 6:** Using a set of URLs, detect abnormal patterns using feature engineering.
- **Task 7:** Build a machine learning model to solve CAPTCHA challenges.
- **Task 8:** Using an email dataset, detect patterns of email spoofing.
- **Task 9:** Implement a text classification algorithm (e.g., Naive Bayes or SVM) to classify emails as spam or not spam.
- **Task 10:** Use k-means to classify network events into normal and abnormal categories.
- **Task 11:** Develop a decision tree classifier to detect malicious data injections within databases.
- **Task 12:** Develop a model that uses context (e.g., timestamp, source IP, and event type) to detect malicious events within wireless sensor networks.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/AjaxOnTheWay/Machine-Learning-for-Cybersecurity.git](https://github.com/AjaxOnTheWay/Machine-Learning-for-Cybersecurity.git)
   cd Machine-Learning-for-Cybersecurity
