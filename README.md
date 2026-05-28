# 🚖 Uber Ride Analytics & Demand Forecasting System

## 📌 Project Overview

This project focuses on analyzing ride-booking operations, predicting booking completion/cancellation behavior using machine learning, and forecasting ride demand trends.

The project combines:

- Exploratory Data Analysis (EDA)
- Machine Learning Classification
- Feature Importance Analysis
- Time Series Forecasting
- Business Intelligence Insights

to simulate a real-world ride-sharing analytics system.

---

# 🎯 Objectives

- Analyze operational ride-booking trends
- Understand customer and payment behavior
- Predict booking outcomes using ML models
- Forecast future ride demand patterns
- Generate business insights for decision-making

---

# 📂 Dataset Information

Dataset includes:

- Booking Information
- Ride Distance
- Payment Methods
- Vehicle Types
- Customer Ratings
- Driver Ratings
- Booking Status
- Pickup & Drop Locations

Total records analyzed:

**49,294 rides**

---

# 🔄 Project Workflow

Dataset  
↓  
Data Cleaning  
↓  
Feature Engineering  
↓  
EDA & Visualization  
↓  
ML Model Training  
↓  
Model Comparison  
↓  
Feature Importance Analysis  
↓  
Demand Forecasting  
↓  
Business Insights  

---

# 📊 Exploratory Data Analysis

Key analyses performed:

- Booking Status Distribution
- Payment Method Analysis
- Vehicle Type Distribution
- Ride Demand by Hour
- Ride Demand by Weekday
- Booking Value Distribution
- Correlation Analysis

---

# 🤖 Machine Learning Models Used

### 1. Logistic Regression

Used as baseline classification model.

Accuracy:

**90.7%**

---

### 2. Random Forest Classifier

Best-performing ensemble model.

Accuracy:

**99.84%**

---

### 3. XGBoost Classifier

Gradient boosting based model.

Accuracy:

**99.83%**

---

# 📈 Model Comparison

| Model | Accuracy |
|------|------|
| Logistic Regression | 90.7% |
| Random Forest | 99.84% |
| XGBoost | 99.83% |

---

# ⚠️ Important Observation

Feature importance analysis suggests potential **target leakage**.

Highly influential features include:

- Payment Method
- Customer Ratings
- Driver Ratings

These variables may become available after ride completion and could artificially increase model accuracy.

---

# 📉 Forecasting Analysis

Demand forecasting was performed using:

- Daily Ride Trend Analysis
- Moving Average Smoothing
- Linear Regression Forecasting

The analysis indicates relatively stable ride demand patterns across time.

---

# 📊 Key Business Insights

- Completed rides dominate operations
- Driver cancellations exceed customer cancellations
- UPI is the most frequently used payment method
- Budget ride categories receive highest demand
- Peak ride demand occurs during evening hours

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Google Colab
- Power BI (planned)

---

# 📁 Project Structure

```text
Uber-Ride-Analytics/
│
├── dashboard/
├── dataset/
├── images/
├── notebook/
├── requirements.txt
└── README.md
