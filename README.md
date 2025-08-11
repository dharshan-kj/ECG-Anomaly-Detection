# ECG-Anomaly-Detection

# Overview

This project implements machine learning techniques to detect anomalies in Electrocardiogram (ECG) signals. By analyzing ECG data, the system aims to identify irregular heartbeats, which can be indicative of various cardiac conditions.

# Problem Statement

Monitoring heart health is crucial, as abnormalities in heart activity can be early signs of serious medical events such as heart attacks or strokes. This project focuses on developing a model that can accurately detect such anomalies in ECG recordings.

# Dependencies

To replicate the analyses and models described in this project, ensure you have the following Python packages installed:

-> Python 3.7
-> scipy
-> pandas
-> numpy
-> matplotlib
-> scikit-learn (version 0.23.1)
-> imbalanced-learn
-> wfdb (for reading ECG data in .dat/.atr format)

# Project Structure

* The repository contains the following key components:

* Data Preprocessing: Scripts to read and preprocess ECG data, including baseline corrections, peak alignment, and amplitude scaling.

* Exploratory Data Analysis (EDA): Visualizations and analyses to understand the characteristics of the ECG signals and identify potential artifacts.

* Modeling: Implementation of machine learning models, such as k-Nearest Neighbors, Logistic Regression, and Random Forest, to classify normal and abnormal heartbeats.

* Evaluation: Metrics and techniques to assess model performance, especially considering the class imbalance between normal and abnormal heartbeats.

# Key Observations
-> ECG signals exhibit low-frequency amplitude fluctuations and occasional high-amplitude spikes.

-> Variability in peak latency and individual timing/amplitude of ECG components can occur from heartbeat to heartbeat.

-> Preprocessing steps like baseline correction, peak alignment, and amplitude scaling are crucial for accurate model performance.
