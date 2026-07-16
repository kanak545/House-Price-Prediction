# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using machine learning techniques on the California Housing dataset. It demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and hyperparameter tuning.

The objective is to build an accurate regression model capable of estimating median house values based on various housing and demographic features.

---

## 🚀 Features

- Data loading and exploration
- Exploratory Data Analysis (EDA)
- Missing value handling
- Feature scaling and preprocessing
- Categorical feature encoding
- Machine Learning Pipeline
- Training multiple regression models
- Cross-validation for model comparison
- Hyperparameter tuning
- Performance evaluation using multiple metrics
- Predicting house prices for new input data

---

## 📂 Project Structure

```
House-Price-Prediction/
│
├── house_price_prediction.ipynb
├── housing.csv
├──.ipynb_checkpoints
├── README.md
```

---

## 📊 Dataset

The project uses the **California Housing Dataset**, which contains information about housing districts in California.

### Features

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity

### Target Variable

- Median House Value

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 🔍 Machine Learning Workflow

### 1. Data Exploration

- Load the dataset
- Inspect data types
- Check missing values
- Analyze feature distributions

### 2. Data Preprocessing

- Handle missing values
- Scale numerical features
- Encode categorical variables
- Create preprocessing pipeline

### 3. Model Training

The following regression models were trained and compared:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- HistGradientBoostingRegressor

### 4. Model Evaluation

Models were evaluated using:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score
- Cross-validation

### 5. Hyperparameter Tuning

Hyperparameter tuning was performed to improve model performance and select the best-performing model.

---

## 📈 Results

The project compares multiple regression algorithms and selects the best-performing model based on evaluation metrics. The final optimized model is used to predict house prices for unseen data.

---


## 📚 Learning Outcomes

Through this project, I learned:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Building machine learning pipelines
- Feature scaling and encoding
- Training and comparing multiple regression models
- Cross-validation techniques
- Hyperparameter tuning
- Model evaluation using regression metrics

---

## 🔮 Future Improvements

- Deploy the model using Flask or Streamlit
- Build a web interface for predictions
- Experiment with XGBoost and LightGBM
- Perform advanced feature engineering
- Add model persistence using Joblib or Pickle

---

## 👤 Author

**Kanak Kirti Sharma**

B.Tech Computer Science and Engineering  
Aspiring Data Analyst | Machine Learning Enthusiast

---
