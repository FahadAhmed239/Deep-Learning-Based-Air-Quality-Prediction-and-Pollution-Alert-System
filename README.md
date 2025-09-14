# Deep Learning-Based Air Quality Prediction and Pollution Alert System

## Project Overview
This project aims to monitor and predict air quality using Machine Learning (Random Forest) and Deep Learning (LSTM) models.  
The system predicts **PM2.5 pollutant levels** and generates **pollution category alerts**.  
A simple **Streamlit web application** is also built for deployment and real-time interaction.  

---

##  Week 1 Progress
1. **Dataset Search & Collection** → Air Quality dataset added inside `dataset/`.  
2. **Problem Statement Defined** → Predict and alert air pollution using ML/DL.  
3. **Data Preparation** → Basic exploration and visualization (`data_exploration.ipynb`).  

---

##  Week 2 Progress
4. **Model Selection** → Random Forest (baseline ML) and LSTM (Deep Learning for time-series).  
5. **Model Implementation** → Implemented Random Forest and LSTM models in `model_training.ipynb`.  
6. **Model Evaluation** → Compared models using RMSE, MAE, R².  
   - **Random Forest** → Simple & interpretable baseline.  
   - **LSTM** → Time-series prediction for PM2.5.  
7. **Data Cleaning** → Added `data_cleaning.ipynb` to handle missing values, duplicates, and normalization.  

---

##  Week 3 Progress
7. **Model Deployment** → Created **Streamlit app** (`app_streamlit.py`) for real-time predictions.  
   - Input: PM10, NO2, SO2, CO, O3, Temperature, Humidity, Wind Speed  
   - Output: Predicted PM2.5 level + AQI Category (Good / Moderate / Poor / Very Poor / Hazardous).  
8. **PPT Prepared** → `Week_3_Project_PPT_Fahad.pptx` with:  
   - Problem Statement  
   - Objectives & Methodology  
   - Model Results (Random Forest + LSTM Plots)  
   - Streamlit App UI & Screenshots  
   - Conclusion  

---

