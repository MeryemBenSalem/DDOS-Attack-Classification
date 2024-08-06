DDoS Attack Classification Project
Overview
This project focuses on classifying Distributed Denial of Service (DDoS) attacks using various machine learning models. The primary goal is to leverage different algorithms to accurately detect and classify DDoS attacks from network traffic data.

Tools and Environment
This project is developed using Amazon SageMaker Studio Lab, a robust and scalable environment for machine learning and data analysis. SageMaker Studio Lab provides a convenient platform with integrated tools for model training, evaluation, and experimentation.

Dataset
The dataset used for this project is the IDS 2017 dataset. It is publicly available and provides a comprehensive set of features necessary for detecting DDoS attacks. This dataset includes network traffic data that contains various types of attacks and normal traffic, making it suitable for building and evaluating classification models.

Dataset Details:
Dataset Name: IDS 2017
Description: Contains labeled network traffic data for DDoS and other types of attacks.
Source: IDS 2017 Dataset
Features: Includes a wide range of features related to network traffic such as packet size, duration, and protocol type.
Models Used
The following machine learning models are utilized in this project for the classification of DDoS attacks:

Random Forest
Logistic Regression
Gradient Boosting Machine (GBM)
Support Vector Machine (SVM)
XGBoost
Neural Network
Each model is trained and evaluated on the IDS 2017 dataset to assess its performance in detecting DDoS attacks.

Evaluation Metrics
The performance of each model is evaluated using the Receiver Operating Characteristic (ROC) curve and Area Under the Curve (AUC) scores. These metrics help in understanding how well each model discriminates between DDoS attacks and normal traffic.
