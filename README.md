# AI-Driven Predictive Maintenance for Industrial Assets

This repository contains the source code, models, and implementation details for my Bachelor Thesis:  "AI Driven Predictive Maintenance."  The project focuses on predicting the  Remaining Useful Life (RUL)  of critical industrial components—specifically turbofan engines and Lithium-ion batteries—using a combination of traditional machine learning and advanced deep learning architectures.

# 📌 Project Overview
Predictive maintenance leverages AI to transition from reactive or fixed-schedule maintenance to  condition-based maintenance. By forecasting when a component will fail, industries can reduce unscheduled downtime by up to 25% and maintenance costs by 30%.

This research explores RUL prognostics for:
1.   NASA Turbofan Engines (C-MAPSS Dataset):  Analyzing degradation patterns across 21 sensor measurements.
2.   NASA Li-ion Batteries:  Monitoring voltage, current, and temperature to estimate battery health.

# 🛠 Tech Stack
 Languages:  Python, C (for ESP8266 deployment).
 Libraries:  TensorFlow/Keras, Scikit-learn, Pandas, NumPy, Matplotlib.
 Deployment:  TensorFlow Lite, ESP8266 Microcontroller, Android Studio.

## 🚀 Key Features
 Comparative Analysis:  Evaluation of multiple algorithms including Linear Regression, SVR, Random Forest, XGBoost, and LSTM.
 Advanced Feature Engineering:  Implementation of  Rolling Mean Features  (10-cycle windows) to capture temporal trend.
 Edge Computing Deployment:  Models are optimized via TensorFlow Lite and deployed onto an  ESP8266 module  for local, real-time inference.
 Android Interface:  A dedicated mobile application for users to input sensor data and receive real-time RUL predictions.

## 📊 Experimental Results
The study conducted multiple rounds of experiments, revealing that  Random Forest Regression  emerged as one of the most reliable models, while  LSTM networks  showed strong potential in capturing complex temporal dependencies.

##  Thesis Information
 Author:  Abdelrahman Ibrahim Fouad 
 Supervisor:  Prof. Amr Talaat Abdel-Hamid 
 Institution:  German University in Cairo 
 Submission Date:  19 May, 2024 

