
# 🏡 House Price Prediction

## 📌 Overview
This project aims to predict house prices using **machine learning models**. It covers the full data science pipeline, including **data scraping, preprocessing, feature engineering, modeling, and evaluation**. 

## 🎯 Objective
The goal is to **build an accurate house price prediction model** using structured data collected from the website **[batdongsan.vn](https://batdongsan.vn/ban-nha/)**.

## 📊 Dataset
### 📌 **Data Collection**
- Data is scraped from **[batdongsan.vn](https://batdongsan.vn/ban-nha/)**.
- The dataset includes various features such as **location, area, number of rooms, price, property type, and more**.
- The collected dataset is stored in `data/house_prices.csv`.

### 📌 **Data Preprocessing & Feature Engineering**
- **Handling missing values**.
- **Encoding categorical variables**.
- **Scaling numerical features**.
- **Feature engineering** to enhance the predictive power.

## 🏗️ Methodology
1. **Data Exploration**:
   - Visualizing price distributions.
   - Creating a **heatmap** of house prices by location using **kernel density estimation**.
  
2. **Machine Learning Models**:
   - **Linear Regression** (Baseline model).
   - **Random Forest** (For tree-based learning).
   - **Gradient Boosting Models** (XGBoost, LightGBM).

3. **Model Evaluation**:
   - Metrics: **RMSE, MAE, R² Score**.
   - Benchmarking different models to find the best-performing one.

## 🚀 Implementation
- The entire project is implemented in **Python** using:
  - **Jupyter Notebook**
  - **Scikit-learn**
  - **Pandas, NumPy, Matplotlib, Seaborn**
  - **BeautifulSoup, Selenium (For web scraping)**
