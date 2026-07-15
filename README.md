# 🛒 Olist E-Commerce Analytics & Delivery Delay Prediction

<p align="center">

An end-to-end **Data Analytics & Machine Learning** project built using the **Olist Brazilian E-Commerce Dataset**, integrating SQL, Python, Machine Learning, and Tableau to analyze business performance and predict delivery delays.

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-blue?logo=tableau)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-success?logo=github)

</p>

---

# 📖 Project Overview

This project demonstrates a complete **end-to-end Data Analytics workflow**, beginning with raw relational datasets and ending with predictive machine learning models and an interactive business intelligence dashboard.

Using the **Olist Brazilian E-Commerce Public Dataset**, the project integrates multiple datasets to uncover business insights, identify factors affecting delivery performance, and predict delivery delays using regression algorithms.

The project follows industry-standard data analytics practices including:

- SQL Data Preparation
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Machine Learning
- Business Intelligence Dashboard Development

---

# 🎯 Business Problem

Delivery delays are one of the biggest challenges in e-commerce logistics.

Late deliveries can result in:

- Customer dissatisfaction
- Poor seller ratings
- Increased logistics costs
- Lower customer retention

This project aims to identify the factors contributing to delivery delays and build predictive models to support better logistics planning.

---

# 🎯 Project Objectives

- Clean and preprocess raw e-commerce data
- Merge multiple relational datasets into a single analytical dataset
- Perform exploratory data analysis
- Engineer meaningful predictive features
- Train and compare multiple machine learning models
- Build an interactive Tableau dashboard
- Generate actionable business insights for stakeholders

---

# 📊 Dataset Information

**Dataset:** Olist Brazilian E-Commerce Public Dataset

The dataset contains information about:

- Customers
- Orders
- Products
- Sellers
- Payments
- Reviews
- Geolocation
- Order Items

Multiple datasets were joined together to create a unified analytical dataset suitable for predictive modeling.

---

# 🛠️ Technologies Used

| Category | Tools |
|------------|-----------------------------|
| Programming Language | Python |
| Database | PostgreSQL |
| Data Processing | Pandas, NumPy |
| Data Visualization | Tableau |
| Machine Learning | Scikit-learn, XGBoost |
| Version Control | Git & GitHub |
| Notebook Environment | Jupyter Notebook |

---

# 📂 Repository Structure

```
Olist-Delivery-Delay-Prediction/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_eda.ipynb
│   └── 04_model_training.ipynb
│
├── sql/
│   ├── schema.sql
│   ├── cleaning_queries.sql
│   └── analysis_queries.sql
│
├── dashboard/
│   └── olist_dashboard.pbix
│
├── images/
│   ├── dashboard.png
│   ├── sales_trend.png
│   ├── feature_importance.png
│   ├── correlation_heatmap.png
│   └── model_comparison.png
│
├── requirements.txt
├── LICENSE
└── README.md
```

---

# 🔄 Project Workflow

```
Raw CSV Files
        │
        ▼
 PostgreSQL Database
        │
        ▼
 SQL Data Cleaning
        │
        ▼
 Data Preprocessing
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
 Tableau Dashboard
        │
        ▼
 Business Insights
```

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Converted data types
- Parsed datetime columns
- Merged multiple datasets
- Removed irrelevant variables
- Checked data consistency

---

# ⚙️ Feature Engineering

Several new features were created, including:

- Purchase Hour
- Purchase Day
- Purchase Month
- Purchase Weekday
- Delivery Duration
- Estimated Delivery Duration
- Freight Ratio
- Product Volume
- Payment Features

These engineered features improved the predictive performance of the machine learning models.

---

# 📈 Exploratory Data Analysis

EDA was conducted to understand customer behavior and logistics performance.

Key analyses include:

- Monthly Sales Trend
- Order Status Distribution
- Delivery Time Analysis
- Customer Distribution
- Seller Performance
- Product Category Analysis
- Payment Method Analysis
- Correlation Heatmap
- Feature Distributions

---

# 🤖 Machine Learning Models

The following regression algorithms were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

# 📏 Evaluation Metrics

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Random Forest Regressor achieved the best overall predictive performance for delivery delay prediction.

---

# 📊 Tableau Dashboard

The interactive dashboard includes:

- Executive KPI Cards
- Sales Overview
- Monthly Trends
- Delivery Performance
- Customer Insights
- Seller Performance
- Payment Analysis
- Geographic Distribution
- Interactive Filters

---

# 💡 Key Business Insights

- Delivery delays vary across regions.
- Freight cost influences delivery performance.
- Product dimensions impact shipping duration.
- Certain sellers consistently achieve better delivery performance.
- Machine learning can accurately estimate delivery delays using historical order information.

---

# 🚀 Future Improvements

Future enhancements include:

- Streamlit Web Application
- FastAPI REST API
- Docker Deployment
- Cloud Deployment (AWS/Azure)
- Automated ETL Pipeline
- Hyperparameter Optimization
- CI/CD Integration using GitHub Actions

---

# ⚡ Installation

## Clone the Repository

```bash
git clone https://github.com/SriRam120301/YOUR_REPOSITORY_NAME.git
```

---

## Navigate to the Project

```bash
cd YOUR_REPOSITORY_NAME
```

---

## Create a Virtual Environment

Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

Mac/Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
notebooks/04_model_training.ipynb
```

---

# 📷 Dashboard Preview

> Add screenshots of your Tableau dashboard here.

Example:

```
images/dashboard.png
```

---

# 📌 Business Value

This project demonstrates practical skills in:

- Data Cleaning
- SQL
- Data Analysis
- Machine Learning
- Business Intelligence
- Dashboard Development
- Data Visualization
- Feature Engineering
- Predictive Analytics

It reflects an end-to-end analytics workflow commonly used in industry.

---

# 👨‍💻 Author

## KANDHI SRIRAM REDDY

**MSc Data Science & Business Analysis**

EDC Paris Business School

📧 Email: *(Add your email if you wish)*

🔗 GitHub

https://github.com/SriRam120301

🔗 LinkedIn

YOUR_LINKEDIN_URL

---

# 📄 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Feedback and suggestions are always welcome!
