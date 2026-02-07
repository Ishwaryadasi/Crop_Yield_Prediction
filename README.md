# Crop Yield Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting crop yield using machine learning techniques based on agricultural and environmental factors. The goal is to demonstrate the complete machine learning workflow including data preprocessing, visualization, model training, and evaluation.

---

## 🎯 Problem Statement
To develop a machine learning model that predicts crop yield (hg/ha) using parameters such as rainfall, temperature, pesticide usage, crop type, and region.

---

## 📊 Dataset
- Source: Kaggle – Crop Yield Prediction Dataset
- File: `yield_df.csv`
- Number of records: ~28,000
- Features include:
  - Area
  - Crop (Item)
  - Year
  - Average rainfall (mm/year)
  - Pesticides usage (tonnes)
  - Average temperature (°C)
- Target variable:
  - `hg/ha_yield`

---

## 🧠 Methodology
1. Loaded and explored the dataset  
2. Removed unnecessary columns  
3. Handled categorical variables using label encoding  
4. Visualized important feature relationships  
5. Split data into training and testing sets  
6. Trained a Linear Regression model  
7. Evaluated the model using regression metrics  

---

## 📈 Data Visualization
Basic visualizations were used to understand the dataset:
- Distribution of crop yield
- Relationship between rainfall and crop yield
- Relationship between temperature and crop yield

These visualizations help in understanding data patterns before model training.

---

## 🤖 Model Used
- **Linear Regression**

### Why Linear Regression?
- Suitable for predicting continuous values
- Easy to interpret
- Acts as a strong baseline regression model
- Efficient for structured tabular data

---

## 📊 Model Evaluation
Since this is a regression problem, accuracy is not used.

Evaluation metrics:
- Mean Squared Error (MSE)
- R² Score (acts as an accuracy-like metric)

A higher R² score indicates better prediction performance.

---

## 🛠️ Tools & Technologies
- Programming Language: Python
- Libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
- Platform:
  - Jupyter Notebook

---

## 📂 Project Structure
