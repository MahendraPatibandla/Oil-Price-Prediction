# 🛢️ Crude Oil Price Forecasting using Machine Learning & Deep Learning

## 📌 Project Overview
This project focuses on forecasting crude oil prices using Machine Learning and Deep Learning models. The system analyzes historical crude oil market data and predicts future price trends using advanced time-series forecasting techniques.

The project includes:
- Data preprocessing & feature engineering
- Exploratory Data Analysis (EDA)
- Time-series forecasting
- Machine Learning models
- Deep Learning (LSTM)
- Automated preprocessing pipelines
- Model evaluation & visualization

---

# 🚀 Features

✅ Historical crude oil trend analysis  
✅ Automated preprocessing pipeline  
✅ Feature engineering with lag features & moving averages  
✅ Time-series forecasting using LSTM  
✅ Machine Learning models:
- Random Forest
- XGBoost
- LSTM Neural Network

✅ Data visualization dashboards  
✅ Model comparison and evaluation  

---

# 🧠 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| XGBoost | Gradient Boosting |
| TensorFlow / Keras | Deep Learning |
| Jupyter Notebook | Development Environment |

---

# 📂 Dataset Information

The dataset contains historical crude oil market data including:
- Date
- Open Price
- High Price
- Low Price
- Close Price
- Trading Volume

---

# ⚙️ Project Workflow

## 1️⃣ Data Preprocessing
- Missing value handling
- Data cleaning
- Date formatting
- Scaling using MinMaxScaler
- Automated preprocessing pipelines

## 2️⃣ Exploratory Data Analysis (EDA)
- Oil price trend visualization
- Distribution analysis
- Correlation heatmaps
- Volatility analysis

## 3️⃣ Feature Engineering
Created advanced time-series features:
- Moving averages
- Lag features
- Volatility indicators

## 4️⃣ Machine Learning Models
Implemented:
- Random Forest Regressor
- XGBoost Regressor
- LSTM Neural Network

## 5️⃣ Model Evaluation
Evaluation metrics used:
- MAE
- RMSE
- R² Score

---

# 📊 Model Performance

| Model | Description |
|---|---|
| Random Forest | Handles non-linear relationships effectively |
| XGBoost | High-performance gradient boosting model |
| LSTM | Captures sequential time-series dependencies |

---

# 📈 Visualizations

The project includes:
- Actual vs Predicted Prices
- Oil Price Trend Analysis
- Feature Importance Graphs
- Correlation Heatmaps
- Forecast Visualization

---

# 🏗️ Pipeline Architecture

```python
Pipeline([
    ('imputer', SimpleImputer()),
    ('scaler', StandardScaler()),
    ('model', RandomForestRegressor())
])
