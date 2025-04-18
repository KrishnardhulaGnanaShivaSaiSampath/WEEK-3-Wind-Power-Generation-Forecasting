# ⚡ Week 3 Internship Project - Power Prediction using Regression Models

## 🔍 Project Overview

This project was completed as part of Week 3 of the internship at **Edunet Foundation**.  
The goal is to predict **Power Output** using regression models trained on environmental and location-based features.

We implemented and compared the following models:

- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  
- Artificial Neural Network (ANN)  
- Hyperparameter-Tuned XGBoost (GridSearchCV)

---

## 📁 Dataset Description

The dataset used contains various numerical and categorical features including:

- Environmental variables: temperature, wind speed, wind direction  
- Location-based encoded columns (e.g., Hyderabad, Mumbai, etc.)  
- Target variable: Power Output (continuous)

---

## ⚙️ Preprocessing Steps

- Separated features (X) and target (y)  
- Split the dataset into training and testing sets (80/20 split)  
- Scaled numerical and boolean columns using standard scaling  
- Encoded categorical columns as required

---

## 🧠 Models Used

### 1. Linear Regression  
A simple and interpretable baseline model for power prediction.

### 2. Random Forest Regressor  
An ensemble model that captures non-linear relationships using multiple decision trees.

### 3. XGBoost Regressor  
A high-performance gradient boosting technique suitable for structured data.

### 4. Artificial Neural Network (ANN)  
A deep learning model built with dense layers to capture complex patterns in the data.

### 5. Hyperparameter-Tuned XGBoost  
Utilized GridSearchCV to fine-tune the XGBoost model for optimal performance.

---

## 📊 Model Evaluation

Each model was evaluated using the following metrics:

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- R-squared Score (R²)

### 📈 Comparative Performance

| Model              | MAE     | MSE     | R² Score |
|-------------------|---------|---------|----------|
| Linear Regression | 0.1377  | 0.0325  | 0.5128   |
| Random Forest     | 0.1068  | 0.0217  | 0.6755   |
| XGBoost           | 0.1157  | 0.0248  | 0.6280   |
| ANN               | 0.1192  | 0.0260  | 0.6106   |



---

## 📌 Key Observations

- **Random Forest** delivered the best overall performance, achieving the lowest MAE and highest R² score.
- **XGBoost** and **ANN** also performed well, especially with limited training.
- **Linear Regression**, while simple and fast, had the lowest performance.
- Hyperparameter tuning is expected to further enhance the XGBoost model.

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries/Tools:**  
  - scikit-learn  
  - xgboost  
  - tensorflow / keras  
  - pandas, numpy  
  - matplotlib / seaborn (optional for visualization)

---


## ✅ Acknowledgements

Special thanks to **Edunet Foundation** and our mentors for their guidance and support throughout this internship project.
