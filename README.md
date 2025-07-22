
# 🏠 House Price Prediction Using Machine Learning

In today’s volatile real estate market, **accurate property valuation** is crucial for both buyers and sellers. This project builds a robust **Linear Regression model** to predict house prices based on key features like square footage, number of bedrooms (BHK), number of bathrooms, furnishing status, and air conditioning availability.

This end-to-end machine learning pipeline covers everything from **data preprocessing** to **model deployment-ready outputs**, and is built entirely in **Google Colab** using **Python** and **Scikit-learn**.

---

## 📌 Problem Statement

How can we accurately predict house prices in a dynamic market where properties vary greatly in terms of size, layout, and amenities?

---

## 🧠 Solution Overview

We use **Supervised Machine Learning** (Linear Regression) to learn from historical property data and estimate prices for new listings.

---

## 🧩 Features of This Project

- ✅ **Google Colab Notebook** with clean step-by-step implementation
- 🧹 Data cleaning & preprocessing (missing values, outliers, inconsistent entries)
- 🔍 Feature extraction (e.g., extracting `BHK` from “size” column)
- 💰 Created new feature: **price per square foot** to capture valuation trends
- 📈 Trained **Linear Regression model** using `scikit-learn`
- 💾 Saved model using `joblib` for future deployment (API/Streamlit app-ready)

---

## 📂 Dataset Summary

- Source: Cleaned housing dataset (e.g., from Kaggle or local CSV)
- Key Columns:
  - `size` (e.g., "2 BHK")
  - `total_sqft` (area in sq.ft.)
  - `bath` (number of bathrooms)
  - `price` (target variable)
  - `furnishing_status`, `airconditioning`

---

## 🛠️ Tech Stack

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Python      | Core programming language        |
| Pandas      | Data manipulation                |
| NumPy       | Numerical operations             |
| Scikit-learn| ML modeling & preprocessing      |
| Matplotlib  | Visualizations                   |
| Seaborn     | Statistical plotting             |
| Joblib      | Model serialization              |

---
