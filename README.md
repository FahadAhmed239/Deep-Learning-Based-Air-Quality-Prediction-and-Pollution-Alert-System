Final(Week1+Week2+week3)

Deep-Learning-Based-Air-Quality-Prediction-and-Pollution-Alert-System
Deep Learning project to predict air quality index (AQI) and generate pollution alerts.


## Project Overview
This project aims to develop a **Deep Learning model** for predicting Air Quality Index (AQI) and pollutant levels to provide **early alerts** for pollution control. By analyzing historical pollution and weather data, the model will predict future air quality conditions and generate warnings when pollution exceeds safe thresholds.

---

##  Dataset Information

- **Source:**
  - [OpenAQ](https://openaq.org/)
  - [Kaggle: Air Quality & Pollution Dataset](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)
- **Features:**
  - PM2.5, PM10, NO₂, SO₂, CO, O₃
  - Temperature, Humidity, Wind Speed
- **Target Variable:**
  - AQI (Air Quality Index)

The dataset used here (`dataset/air_quality_dataset.csv`) is a sample generated for demonstration purposes.

---

##  AI / Deep Learning Approach
- Preprocessing: Handling missing values, normalization
- Models: Deep Neural Network (DNN), LSTM for time-series AQI prediction
- Output: Predicted AQI values and pollution alert system

---

##  Expected Outcomes
- Accurate AQI predictions
- Classification into categories: Good, Moderate, Poor, Very Poor, Hazardous
- Early-warning pollution alert system for smart cities

---

##  Progress (30% Submission)
- Dataset collected and added to repository (`dataset/air_quality_dataset.csv`)
- Initial data exploration completed (`notebooks/data_exploration.ipynb`)

---

##  Next Steps
1. Perform Exploratory Data Analysis (EDA)
2. Train deep learning models
3. Evaluate prediction accuracy
4. Build pollution alert dashboard







WEEK2


# Deep Learning-Based Air Quality Prediction and Pollution Alert System

## 📌 Project Overview
This project aims to monitor and predict air quality using Machine Learning and Deep Learning models.  
The system predicts **PM2.5 pollutant levels** and can generate pollution alerts based on predictions.  

---

## ✅ Week 1 Progress
1. **Dataset Search** → Air Quality dataset added inside `dataset/`.  
2. **Problem Statement Defined** → Predict and alert air pollution using ML/DL.  
3. **Data Preparation** → Basic exploration and visualization done in `data_exploration.ipynb`.

---

## 🚀 Week 2 Progress
4. **Model Selection** → Random Forest (baseline) and LSTM (Deep Learning for time-series).  
5. **Model Implementation** → Implemented Random Forest and LSTM models in `model_training.ipynb`.  
6. **Model Evaluation** → Compared using RMSE, MAE, R² and plotted Actual vs Predicted.  

---

## 📂 Repository Structure

