# 🍷 Wine Quality Prediction App

A machine learning web application built using Streamlit to predict wine quality based on physicochemical properties. This project uses the Wine Quality Dataset from Kaggle.

## 📌 Project Overview

This project demonstrates the end-to-end machine learning pipeline:
- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Model training and evaluation
- Streamlit web app development
- Deployment to Streamlit Cloud

## 📊 Dataset

**Dataset:** Wine Quality Dataset  
**Source:** [Kaggle - Wine Quality Dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)  
**Features:**  
The dataset includes 11 physicochemical input variables:
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

**Target Variable:**
- Quality (score between 0 and 10)

## 🧪 Model Training

Two models were trained and compared using scikit-learn:
- Logistic Regression
- Random Forest Classifier ✅ (selected for best performance)

Evaluation metrics used:
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix

The best-performing model is saved using `pickle`.

## 🚀 Streamlit App Features

The web app allows users to:
- Explore the dataset
- View interactive data visualizations
- Enter values for each feature to get wine quality predictions
- View model performance and metrics

### ⚙️ Streamlit Widgets Used:
- Sliders
- Number inputs
- Buttons
- Interactive plots

## 🧱 Project Structure

