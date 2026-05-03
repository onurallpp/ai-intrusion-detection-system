# AI-Based Intrusion Detection System

This project is an anomaly detection system developed using K-Means clustering to identify abnormal network traffic patterns.

## Overview

The system processes network traffic data, applies preprocessing and normalization, and detects anomalies using distance-based thresholding.

## Features

- Detects abnormal network traffic patterns  
- Uses K-Means clustering for anomaly detection  
- Applies preprocessing and normalization  
- Uses distance-based thresholding to identify anomalies  
- Saves trained model and parameters  

## Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Joblib  

## Project File

- `AI_Intrusion_Detection_System_Clean.ipynb`  
  Contains data preprocessing, model training, anomaly detection, and evaluation steps.

## How to Run

1. Open the notebook:
   AI_Intrusion_Detection_System_Clean.ipynb  
2. Run all cells step by step  
3. If the dataset is not available, the system uses synthetic data  

## Dataset

This project is designed to work with the NSL-KDD dataset.

Expected file:
KDDTrain+.txt

If the dataset is not found, synthetic data is used for demonstration.

## Output

- Detects anomalies in network traffic  
- Shows classification results  
- Saves trained model and parameters  

## Purpose

This project was developed to understand anomaly detection, clustering, and basic AI-based intrusion detection systems.
