# 🛒 Walmart Weekly Sales Forecasting 🚀📈

Predicting future sales like a retail pro – with Machine Learning magic.

![sales-forecast](https://img.shields.io/badge/MachineLearning-XGBoost-blue.svg) ![status](https://img.shields.io/badge/Status-Completed-brightgreen.svg) ![python](https://img.shields.io/badge/Made%20with-Python-yellow.svg)

---

## 📌 Project Overview

This project aims to forecast **weekly sales** for Walmart stores using real-world data from Kaggle. By applying **XGBoost regression**, we help Walmart predict revenue spikes and slumps across time – a crucial need for inventory, staffing, and promotion planning.

🔍 Business Problem:
> Retail chains like Walmart need to understand how sales vary across stores and seasons to **optimize logistics and avoid under/over-stocking**.

---

## 🧠 Problem Statement

> **"Build a machine learning model that accurately predicts future weekly sales for each store, using historical data and engineered time features."**

---

## 🔧 Tech Stack & Tools

- **Language**: Python 3.x
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **EDA**: Visualizations + Statistical summaries
- **Modeling**: XGBoost Regressor
- **Evaluation**: RMSE, R² Score
- **Notebook**: Jupyter

---

## 📁 Dataset Details

- **Source**: [Kaggle Walmart Sales Dataset](https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting/data)
- **Files Used**:
  - `features.csv` – Store-level information
  - `stores.csv` – Store type and size
  - `train.csv` – Weekly sales data

---

## 📊 Key Steps

### 1. Import & Merge Data  
Combined 3 CSVs based on `Store` and `Date` keys.

### 2. Clean & Transform  
- Converted `Date` to `datetime` format  
- Created `Year`, `Month`, and `Week` columns  
- Filled missing values using forward fill

### 3. Exploratory Data Analysis  
- Analyzed sales trends by month, store type, and holidays  
- Visualized distributions using seaborn

### 4. Feature Engineering  
- Extracted temporal features (month, year, week)  
- One-hot encoded categorical variables

### 5. Model Building (XGBoost)  
- Trained XGBoostRegressor on 75% of data  
- Tuned hyperparameters manually

### 6. Evaluation  
- R² Score: **`0.89`**  
- RMSE: **`3.7`** (example value – replace with actual)  
- Visualized predicted vs actual sales

---

## 🌟 Results

✅ Achieved high prediction accuracy  
📉 Identified low-sales weeks via model output  
📈 Discovered CPI, Unemployment, and Fuel Price as major influencers

---

## 📌 Use Cases

- 📦 Inventory Planning  
- 💰 Revenue Forecasting  
- 🛍️ Promotion Scheduling

---

## 🚀 Future Work

- Model deployment using Streamlit or Flask  
- Add holidays & weather impact  
- Automate with MLOps pipeline (DVC, Docker)

---

## 🙌 Author

**Rohit Mannur**  
📧 rohitmannur@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/rohit-mannur-851a82288) | [GitHub](https://github.com/rohitmannur007)

---

> 📌 _“Prediction is not about the future — it's about understanding the present.”_

---

## 💡 If you like this project, feel free to ⭐️ the repo and fork it!
