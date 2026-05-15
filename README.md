# Customer Churn Prediction using Artificial Neural Network (ANN)

## Overview

This project focuses on predicting customer churn using an Artificial Neural Network (ANN). The model analyzes customer demographic and banking information to determine whether a customer is likely to leave the bank or continue using its services.

Customer churn prediction helps businesses identify high-risk customers early and take proactive retention measures to reduce revenue loss and improve customer satisfaction.

The project demonstrates the complete machine learning workflow including:

- Data preprocessing
- Feature engineering
- Encoding categorical variables
- Feature scaling
- ANN model building
- Model training and evaluation
- Customer churn prediction

---

## Problem Statement

Customer churn is a major challenge in the banking industry. Retaining existing customers is more cost-effective than acquiring new ones. This project aims to build a predictive deep learning model that can classify customers into:

- **0 → Customer Stays**
- **1 → Customer Leaves (Churns)**

---

## Dataset Information

The dataset contains customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target Variable)

Target Variable:
- `Exited = 1` → Customer churned
- `Exited = 0` → Customer retained

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras
- Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Preprocessing

Performed:
- Handling categorical variables
- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Train-Test Splitting

### 2. ANN Model Building

Built an Artificial Neural Network using:
- Dense hidden layers
- ReLU activation function
- Sigmoid output layer
- Adam optimizer
- Binary cross-entropy loss function

### 3. Model Training

The model was trained using:
- Training dataset
- Validation dataset
- Backpropagation
- Epoch optimization

### 4. Model Evaluation

Evaluated model performance using:
- Accuracy Score
- Confusion Matrix
- Prediction Probability

---

## Model Architecture

Input Layer → Hidden Layer → Hidden Layer → Output Layer

Example:
- Input Features
- Dense Layer (ReLU)
- Dense Layer (ReLU)
- Output Layer (Sigmoid)

---

## Results

- Achieved approximately **86% accuracy**
- Successfully predicted customer churn using ANN
- Generated probability-based predictions for customer retention analysis

Example Prediction:
```python
Prediction Output:
Customer is likely to stay
