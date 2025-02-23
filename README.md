# MSAAI-530-Final-Project
**Smart EV Charging Network Optimization System**

**Project Overview**

The Smart EV Charging Network Optimization System is a machine learning-driven IoT solution designed to enhance the efficiency of electric vehicle (EV) charging stations. This project utilizes deep learning classification to predict charging speeds and time series forecasting (LSTM) to estimate future energy demand.By analyzing real-world EV charging data, our system optimizes station resource allocation, improves user experience, and enhances energy distribution strategies.

**Team Members**

Narendra Fadnavis
Samantha Colbert-Neal
Peter Ogunrinde
Course: AAI-530: Data Analytics and Internet of Things
Instructor: Professor An Tran
University: University of San Diego
Date: February 23, 2025

**Key Features & Objectives**

Predict Charging Speed (Fast, Medium, Slow) using a Deep Learning Classification Model
Forecast Future Charging Demand using a Time Series Prediction Model (LSTM)
Analyze Station Usage Patterns using clustering & exploratory data analysis (EDA)
Optimize Charging Station Performance with interactive Tableau dashboards
Improve Sustainability & Energy Efficiency through data-driven insights.

**Datasets Used**

The dataset is sourced from Kaggle’s "Electric Vehicle Charging Station Usage" and contains:
EV Charging Sessions Data:
Session details (kWh consumed, timestamps, duration, cost)
Charging station metadata (location, facility type, availability)

**Preprocessed IoT Data:**

Includes cleaned & formatted records for machine learning modeling.

**File Paths in Google Drive**(Local Google Drive)

IoT Charging Data: /content/drive/MyDrive/Collab_finalprj/Smart_EV/preprocessed_iot_data.csv
Charging Station Metadata: /content/drive/MyDrive/Collab_finalprj/Smart_EV/station_data_dataverse.csv

**Machine Learning Models**

This project implements two key machine learning models for EV charging optimization:

**Model 1: Deep Learning Classification - Charging Speed Prediction**

Goal: Classifies charging sessions into Fast, Medium, or Slow categories.
Algorithm Used: Multi-Layer Perceptron (MLP) Neural Network
Key Features Used:
Charging Session Duration
Energy Consumed (kWh)
Facility Type
Cost per Session
Performance: Achieved 95.2% accuracy on the test dataset.

**Model 2: Time Series Prediction - Charging Demand (LSTM)**

Goal: Predicts future EV charging demand using time-series analysis.
Algorithm Used: Long Short-Term Memory (LSTM) Neural Network
Key Features Used:
Timestamped charging sessions
kWh consumed per session
Temporal trends & seasonal patterns
Performance: Mean Squared Error (MSE) of 2.03, ensuring high prediction accuracy.

**Key Visualizations & Insights**
The project includes interactive visualizations to analyze EV charging patterns, station utilization, and predictive insights. The following Tableau dashboards provide in-depth analytics:
Deep Learning Classification Dashboard
Charging speed classification (Fast, Medium, Slow)
Distribution of session durations
Charging cost analysis based on facility type
Time Series Forecasting Dashboard
LSTM-based energy consumption forecasts
Peak charging demand hours visualization
Station-level energy utilization trends
Charging Behavior & Trends Dashboard
Weekly and monthly charging patterns
High-usage vs. underutilized charging stations
User behavior analytics

**AAI-530 EV Charging Usage - Tableau Dashboard**
https://public.tableau.com/views/AAI530EVChargingUsage/DeepLearningClassificationDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

**Results & Findings**

The Deep Learning Classification Model achieved 95.2% accuracy in predicting charging speed categories.
The LSTM Model successfully forecasted EV charging demand trends with MSE = 2.03.
Clustering analysis revealed high-demand vs. underutilized charging stations, helping optimize infrastructure.
Tableau dashboards provide real-time monitoring & insights for energy distribution planning.

**Future Enhancements**

Deploy real-time prediction models using IoT streaming data
Enhance LSTM model with weather conditions & dynamic pricing factors
Develop a web-based dashboard for station operators & EV users
Optimize reinforcement learning techniques for dynamic load balancing

**Contributors**

Samantha Colbert-Neal
Peter Ogunrinde
Narendra Fadnavis

