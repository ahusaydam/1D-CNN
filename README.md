# 1D-CNN

1D CNN for Anomaly Detection in 4G Cellular Networks

2. Project Description
This project implements a 1D Convolutional Neural Network (1D CNN) for anomaly detection in 4G cellular network data. The dataset used for this project was obtained from Kaggle's Anomaly Detection in 4G Cellular Networks competition. The goal is to identify anomalies in network performance based on sequential data.
([https://www.kaggle.com/c/anomaly-detection-in-4g-cellular-networks/data?select=ML-MATT-CompetitionQT2021_train.csv](https://www.kaggle.com/c/anomaly-detection-in-4g-cellular-networks/overview))
3. Dataset
The dataset includes network performance metrics that track various aspects of 4G cellular network activity over time. Each sample consists of time-series data, and the task is to detect anomalies in these sequences.

Source: Kaggle
Type: Time-series data
Problem Type: Anomaly detection
4. Model
A 1D Convolutional Neural Network (1D CNN) is designed to detect anomalies in time-series data by capturing important sequential patterns. The model uses convolutional layers to extract features from the network performance metrics and a fully connected layer for the final classification.
5. Results
The model successfully detects anomalies in the 4G network data. Below are some key performance metrics:
Accuracy: 

