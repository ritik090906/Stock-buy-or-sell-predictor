# 📈 Stock Price Prediction using KNN

A machine learning project for **predicting stock prices** using the **K-Nearest Neighbors (KNN)** algorithm.  
This notebook demonstrates the full workflow — from **data collection**, **feature engineering**, and **model training**, to **visualization and evaluation** of prediction performance.

---

## 🧠 Overview

This project explores how **KNN** can be applied to **stock market prediction** using historical data.  
The model predicts future prices (or trends) based on similarity with past observations.

### The notebook includes:
- Data collection from **Kaggle** or **Quandl**
- Preprocessing & feature extraction
- KNN model training and **GridSearchCV** tuning
- Model evaluation using **Accuracy**, **MSE**, and **RMSE**
- Visualization of **predicted vs. actual stock prices**

---

## ⚙️ Tech Stack

- **Language:** Python 3.8+
- **Environment:** Jupyter Notebook  
- **Libraries Used:**
  - `pandas`, `numpy` — data processing  
  - `matplotlib` — data visualization  
  - `scikit-learn` — machine learning (KNN Classifier & Regressor, GridSearchCV)  
  - `quandl` — financial data API  

---

## 📊 Model Performance Metrics

| Model Type     | Metric                             | Description                                                                |
|----------------|------------------------------------|----------------------------------------------------------------------------|
| KNN Classifier | **Accuracy**                       | % of correct up/down predictions                                           |
| KNN Regressor  | **MSE (Mean Squared Error)**       | Average squared difference between actual & predicted values               |
| KNN Regressor  | **RMSE (Root Mean Squared Error)** | Square root of MSE — shows average prediction error in same units as price |

---

## 📉 Visualizations

### 📊 Visualizing the Closing Price of the Stock
<p align="center">
  <img src="Screenshot 2025-11-09 162037.png" width="600" alt="Stock Closing Price Visualization">
</p>

---

### ✅ Calculating the Accuracy of KNN Classifier
<p align="center">
  <img src=""Screenshot 2025-11-09 160937.png width="600" alt="KNN Classifier Accuracy Graph">
</p>

---

### 🔍 Predicted vs Actual Stock Prices
<p align="center">
  <img src="Screenshot 2025-11-09 170133.png" width="600" alt="Predicted vs Actual Stock Prices">
</p>

*(Replace the image URLs above with your actual uploaded image links or notebook plot screenshots.)*

---

## 🔮 Future Insights

- Use **TimeSeriesSplit** for time-based cross-validation  
- Compare KNN with **LSTM**, **Random Forest**, and **XGBoost**  
- Add **technical indicators** (RSI, EMA, MACD) as input features  
- Deploy as a **Streamlit** dashboard for interactive predictions  
- Integrate **live market data** for real-time forecasting  

---

## 🧾 Requirements


## 👨‍💻Author
- Ritik Sharma
- 📧[ritikh0309@gmail.com]
- 💼[www.linkedin.com/in/ritik-sharma-47789924a] 




