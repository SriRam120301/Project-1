# 🛒 Olist E-Commerce Delivery Delay Prediction & Business Intelligence Dashboard

![Python](https://img.shields.io/badge/Python-3.11-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

This project is an end-to-end Data Analytics and Machine Learning solution built using the **Olist Brazilian E-Commerce Dataset**.

The project combines:

- SQL for data extraction and transformation
- Python for data cleaning, feature engineering, exploratory data analysis, and machine learning
- Tableau for interactive business intelligence dashboards

The primary objective is to analyze e-commerce operations and predict delivery delays using multiple regression models.

---

# 🎯 Business Problem

Late deliveries negatively impact customer satisfaction, increase operational costs, and reduce seller ratings.

This project aims to:

- Analyze order and delivery performance
- Identify factors affecting delivery delays
- Build predictive machine learning models
- Create executive dashboards for business decision-making

---

# 📂 Dataset

**Source**

Olist Brazilian E-Commerce Public Dataset

Dataset includes information about:

- Customers
- Orders
- Products
- Sellers
- Payments
- Reviews
- Geolocation

Multiple datasets were merged into one analytical dataset for modeling.

---

# 🛠 Technologies Used

| Category | Tools |
|-----------|-------|
| Programming | Python |
| Database | PostgreSQL |
| Data Processing | Pandas, NumPy |
| Visualization | Tableau |
| Machine Learning | Scikit-learn, XGBoost |
| Version Control | Git & GitHub |

---

# 📊 Project Workflow

```
Raw CSV Files
        │
        ▼
PostgreSQL Database
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Machine Learning Models
        │
        ▼
Business Dashboard (Tableau)
```

---

# 📁 Project Structure

```
Olist-Delivery-Delay-Prediction/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   ├── model_training.ipynb
│
├── sql/
│   ├── schema.sql
│   ├── queries.sql
│
├── tableau/
│   ├── olist_bi.pbix
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

# 🔍 Exploratory Data Analysis

The analysis includes:

- Order Status Distribution
- Monthly Sales Trend
- Delivery Time Analysis
- Payment Type Distribution
- Customer State Analysis
- Product Category Analysis
- Seller Performance
- Correlation Heatmap

---

# ⚙️ Feature Engineering

Features created include:

- Purchase Hour
- Purchase Day
- Purchase Month
- Delivery Duration
- Estimated Delivery Time
- Product Volume
- Payment Information
- Freight Value

---

# 🤖 Machine Learning Models

The following regression algorithms were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

Evaluation Metrics:

- MAE
- RMSE
- R² Score

---

# 📈 Model Comparison

| Model | MAE | RMSE | R² |
|--------|-----|------|----|
| Linear Regression | ✔ | ✔ | ✔ |
| Decision Tree | ✔ | ✔ | ✔ |
| Random Forest | ⭐ Best | ⭐ Best | ⭐ Highest |
| XGBoost | ✔ | ✔ | ✔ |

**Best Performing Model:** Random Forest Regressor

---

# 📊 Tableau Dashboard

The dashboard includes:

- KPI Cards
- Sales Overview
- Order Status Analysis
- Customer Distribution
- Delivery Performance
- Payment Analysis
- Seller Insights
- Interactive Filters

---

# 💡 Key Business Insights

- Delivery delays significantly affect customer satisfaction.
- Freight value influences delivery time.
- Certain states experience longer delivery durations.
- Product dimensions impact shipping efficiency.
- Random Forest provided the highest prediction accuracy.

---

# 🚀 Future Improvements

- Deploy model using Streamlit
- Hyperparameter tuning
- Real-time prediction API
- Cloud deployment
- Automated ETL Pipeline

---

# ▶️ How to Run

## Clone Repository

```bash
git clone https://github.com/YourUsername/YourRepository.git
```

## Install Requirements

```bash
pip install -r requirements.txt
```

## Run Notebook

```bash
jupyter notebook
```

---

# 📷 Dashboard Preview

> Add screenshots here.

Example:

```
images/dashboard.png
```

---

# 👨‍💻 Author

**KANDHI SRIRAM REDDY**

MSc Data Science & Business Analysis

EDC Paris Business School

GitHub:
https://github.com/SriRam120301

LinkedIn:
(Add your LinkedIn URL)

---

# ⭐ If you found this project useful, consider giving it a Star.
