# 🏠 Real Estate Housing Price Prediction 🏡

## 📖 Project Overview
This project predicts **housing prices** based on features like size, number of bedrooms, bathrooms, location, and amenities. Using **machine learning**, we aim to help buyers, sellers, and real estate agents make **data-driven decisions**. 📊💡

## 🗂 Dataset
The dataset contains house features such as:

- 📏 **Square_Feet**: Size of the house in sq.ft  
- 🛏 **Num_Bedrooms**: Number of bedrooms  
- 🛁 **Num_Bathrooms**: Number of bathrooms  
- 🏢 **Num_Floors**: Number of floors  
- 🏗 **Year_Built**: Year the house was built  
- 🌳 **Has_Garden**: 1 if house has a garden, else 0  
- 🏊 **Has_Pool**: 1 if house has a pool, else 0  
- 🚗 **Garage_Size**: Size of the garage  
- 📍 **Location_Score**: Desirability of the location  
- 🏙 **Distance_to_Center**: Distance to city center in km  

## 🧹 Data Preprocessing
- ✨ Handled missing values (imputation or removal)  
- 📏 Scaled numerical features  
- 🧪 Split data into **training 80%** and **testing 20%** sets  

## 🤖 Models & Results
| Model                         | Training Accuracy | Testing Accuracy | MSE |
|--------------------------------|-----------------|----------------|----------|
| 📈 Linear Regression  (10 features) | 0.97  | 0.97 | 0.02 |
| 📈 Linear Regression  (6 features)  | 0.88  | 0.90 | 0.12|
| 🌲 Random Forest Regressor (10 features) | 0.98 | 0.81 | 0.17 |
| 🌲 Random Forest Regressor (6 features) | 0.95 | 0.88 | 0.15 |
| ⚡ Gradient Boosting Regressor (10 features) | 0.99 | 0.93 | 0.06 |
| ⚡ Gradient Boosting Regressor (7 features) | 0.98 | 0.89 | 0.108 |

> ✅ **Observation**: Multiple Linear Regression with 10 features gives the best test accuracy and lowest MSE, making it the most reliable model for this dataset

## 🌟 Future Enhancements
- Include additional location-based features (schools, crime rate, amenities) 🏫
- Deploy as a web app for real-time predictions 🌐

## ✍️ Author
Aldous Dsouza
Data Science Aspirant

