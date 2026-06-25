# DevelopersHub AI-ML Internship Projects

Welcome to the DevelopersHub AI-ML Internship repository! This collection contains three comprehensive machine learning projects showcasing key data science techniques and skills.

## 📋 Project Overview

### Task 1: Iris Classification

**File:** `task1_Iris.ipynb`

A foundational machine learning project that demonstrates classification using the famous Iris dataset.

**Objectives:**

- Perform exploratory data analysis (EDA) on the Iris dataset
- Classify iris flowers into three species (Setosa, Versicolor, Virginica)
- Train and compare multiple classification models (Logistic Regression, Decision Tree, etc.)
- Evaluate models using accuracy, precision, recall, and F1-score
- Visualize decision boundaries and feature relationships

**Skills Covered:**

- Dataset exploration and visualization
- Multi-class classification
- Model evaluation metrics
- Feature analysis

---

### Task 2: Stock Price Prediction

**File:** `task2_stock_price_prediction.ipynb`

A time-series analysis and regression project focused on predicting future stock prices.

**Objectives:**

- Load and preprocess historical stock price data
- Perform time-series analysis to identify trends and patterns
- Train regression models (Linear Regression, Decision Tree, etc.)
- Make predictions on future stock prices
- Evaluate prediction accuracy using MSE, RMSE, and R² score
- Visualize historical prices and predictions

**Skills Covered:**

- Time-series data handling
- Regression modeling
- Trend analysis
- Model prediction and validation
- Financial data interpretation

---

### Task 3: Heart Disease Prediction

**File:** `task3_heart_disease_prediction.ipynb`
**Dataset:** `heart_disease_uci.csv`

A comprehensive medical prediction project using the UCI Heart Disease dataset for binary classification.

**Objectives:**

- Clean the dataset and handle missing values appropriately
- Perform exploratory data analysis (EDA) to understand trends
- Train a classification model (Logistic Regression or Decision Tree)
- Evaluate using accuracy, ROC curve, and confusion matrix
- Highlight important features affecting prediction

**Skills Covered:**

- Binary classification
- Medical data understanding and interpretation
- Model evaluation using ROC-AUC and confusion matrix
- Feature importance analysis
- Clinical data interpretation

**Model Performance:**

- **Accuracy:** 81.52%
- **AUC Score:** 0.8809
- **Sensitivity:** 78.90%
- **Specificity:** 85.33%

**Key Predictive Features:**

1. ST Depression (oldpeak) - Cardiac stress indicator
2. Number of Major Vessels (ca) - Vessel blockage extent
3. Chest Pain Type (cp) - Pain pattern indicators
4. Gender (sex) - Biological sex influence
5. Cholesterol Level (chol) - Risk factor

---

## 📊 Project Insights

### Task 1: Iris

- Demonstrates fundamental classification concepts
- Perfect for beginners learning ML workflows
- Includes model comparison and hyperparameter tuning

### Task 2: Stock Prediction

- Explores time-series analysis techniques
- Shows practical application in finance
- Demonstrates regression model evaluation

### Task 3: Heart Disease

- Tackles a real-world medical prediction problem
- Shows importance of feature selection in healthcare
- Demonstrates clinical model validation

### Task 4: House Price Prediction

**File:** `task4_house_price_prediction.ipynb`
**Dataset:** `Housing.csv`

A regression-based project to predict house prices using physical and amenity-based features from a structured housing dataset.

**Objectives:**

- Preprocess binary and categorical features for model compatibility
- Perform exploratory data analysis to understand price distribution and feature relationships
- Train and compare regression models (Linear Regression and Gradient Boosting)
- Evaluate using MAE, RMSE, and R² metrics
- Identify key features driving house price predictions

**Skills Covered:**

- Regression modeling and comparison
- Feature encoding (binary mapping, ordinal encoding)
- Model evaluation using error metrics and residual analysis
- Feature importance extraction from ensemble models
- Data preprocessing with StandardScaler

**Model Performance:**

- **Best Model:** Gradient Boosting Regressor
- **R² Score:** Higher than Linear Regression (non-linear relationships captured)
- **Top Features:** Area, Bathrooms, Air Conditioning
- **Price Distribution:** Right-skewed — model performs best in mid-range price bands
