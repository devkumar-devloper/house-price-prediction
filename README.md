# 🏠 House Price Prediction

This project predicts house prices using machine learning techniques. It demonstrates a complete ML workflow including data preprocessing, feature engineering, model training, and evaluation.

---

## 📌 Project Overview

The goal of this project is to build a regression model that can accurately predict house prices based on various features such as zoning, building type, and property characteristics.

---

## ⚙️ Tech Stack

- Python 🐍
- Pandas & NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

- Dataset used: `HousePricePrediction.csv`
- Contains various features related to residential homes
- Target variable: **SalePrice**

---

## 🔧 Workflow

### 1. Data Loading
- Loaded dataset using Pandas
- Basic exploration using `.head()`, `.info()`, `.describe()`

### 2. Data Preprocessing
- Dropped irrelevant columns (e.g., `Id`)
- Handled missing values
- Converted categorical features using **One-Hot Encoding**

### 3. Feature Engineering
- Selected important columns
- Converted categorical variables into numerical format

### 4. Train-Test Split
- Split dataset into training and testing sets using `train_test_split`

### 5. Model Training
- Used **Linear Regression** model from Scikit-learn

### 6. Model Evaluation
Evaluated model performance using:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Mean Absolute Percentage Error (MAPE)

### 7. Feature Scaling (Optional Improvement)
- Applied **StandardScaler** to improve model performance

---

## 📊 Results

- The Linear Regression model provides a baseline prediction.
- Performance can be improved with:
  - Advanced models (Random Forest, XGBoost)
  - Hyperparameter tuning
  - Better feature selection

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

2. Install dependencies:
``` bash
pip install pandas numpy scikit-learn jupyter
```

3. Run the notebook:
```bash
jupyter notebook house_price_predictor.ipynb
