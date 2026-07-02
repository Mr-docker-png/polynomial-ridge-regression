# 🏠 House Price Prediction using Polynomial Features & Ridge Regression

A complete Machine Learning project demonstrating how **Feature Engineering** and **Regularization** improve the performance of linear models for regression tasks.

This project uses the **California Housing Dataset** from Scikit-Learn to predict house prices and compares three different regression models.

---

# 📌 Project Overview

Linear Regression is simple and easy to interpret, but it struggles to model complex non-linear relationships.

In this project we improve Linear Regression by applying:

- Polynomial Feature Engineering
- Interaction Features
- Ridge Regularization

Finally, we compare all models using R² Score and RMSE.

---

# 🎯 Objectives

- Understand Polynomial Features
- Learn Interaction Features
- Apply Ridge Regression
- Compare different regression models
- Evaluate model performance
- Visualize predictions and coefficients

---

# 📂 Project Structure

```
polynomial-ridge-regression/
│
├── data/
│   └── model_results.csv
│
├── images/
│   ├── correlation_heatmap.png
│   ├── model_comparison.png
│   ├── actual_vs_predicted_linear.png
│   ├── actual_vs_predicted_poly.png
│   ├── actual_vs_predicted_ridge.png
│   └── coefficient_comparison.png
│
├──polynomial_ridge_regression.ipynb
│ 
│
|── README.md

```

---

# 📊 Dataset

**Dataset:** California Housing Dataset

Source:
Scikit-Learn

Target Variable:

- House Price

Features:

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

---

# 🧠 Machine Learning Workflow

```
Load Dataset
      │
      ▼
Data Exploration (EDA)
      │
      ▼
Train/Test Split
      │
      ▼
Baseline Linear Regression
      │
      ▼
Polynomial Feature Engineering
      │
      ▼
Linear Regression
      │
      ▼
Ridge Regression
      │
      ▼
Model Evaluation
      │
      ▼
Visualization
```

---

# 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

# 📚 Concepts Covered

## Feature Engineering

- Polynomial Features
- Interaction Features

## Regression Models

- Linear Regression
- Ridge Regression

## Evaluation Metrics

- R² Score
- Root Mean Squared Error (RMSE)

---

# 📈 Models Compared

| Model | Description |
|--------|-------------|
| Linear Regression | Baseline model |
| Polynomial + Linear Regression | Uses polynomial and interaction features |
| Polynomial + Ridge Regression | Uses feature engineering with L2 regularization |

---

# 📷 Project Visualizations

The project includes:

- Correlation Heatmap
- Model Performance Comparison
- Actual vs Predicted Scatter Plots
- Coefficient Comparison

---

# 💡 Key Learning

### Linear Regression

- Simple model
- Assumes linear relationships

### Polynomial Features

Creates new features such as:

- x²
- x³
- x₁ × x₂

This allows linear models to learn non-linear relationships.

### Ridge Regression

Ridge Regression applies **L2 Regularization** to reduce overfitting by shrinking large coefficients.

It improves the model's ability to generalize to unseen data.

---

# 📊 Results

The project compares all models using:

- Training R²
- Testing R²
- Training RMSE
- Testing RMSE

Example comparison table:

| Model | Train R² | Test R² | Train RMSE | Test RMSE |
|--------|---------:|--------:|-----------:|----------:|
| Linear Regression | ... | ... | ... | ... |
| Polynomial Linear | ... | ... | ... | ... |
| Polynomial Ridge | ... | ... | ... | ... |

---

# 🎓 What I Learned

Through this project I learned:

- The importance of Feature Engineering
- How Polynomial Features increase model flexibility
- Why Interaction Features help capture feature relationships
- How Ridge Regression reduces overfitting
- How to evaluate regression models using R² Score and RMSE
- How to compare multiple machine learning models

---

# 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross Validation
- Pipeline implementation
- Feature Scaling
- Lasso Regression
- ElasticNet Regression
- Model Deployment with Streamlit

---

# 📖 References

- Introduction to Machine Learning with Python
- Scikit-Learn Documentation

---

# ⭐ Connect With Me

I'm documenting my Machine Learning journey by building practical projects while learning the mathematics behind ML.

If you found this project helpful, consider giving it a ⭐ and following my learning journey!
