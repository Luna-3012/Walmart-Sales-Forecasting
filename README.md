# Walmart Sales Forecasting
A project to forecast Walmart’s weekly sales using historical data, structured across four stages for clarity and reproducibility.

---

## 🌐 Live Dashboard
Check out the live Walmart Sales Dashboard: 
[![View Dashboard](https://img.shields.io/badge/View-Dashboard-blue?style=for-the-badge)](https://luna-3012.github.io/Walmart-Sales-Forecasting/)

---

## 📂 Project Structure

1. Data Preparation: Cleans and organizes the raw dataset, handling missing values and formatting for analysis.
2. Exploratory Data Analysis (EDA): Explores trends, patterns, and correlations through visualizations and summary statistics.
3. Feature Engineering: Creates and transforms features to enhance predictive performance.
4. Model Training Evaluation: Trains machine learning models, evaluates results, and compares performance.

---

## 🛠️ Tech Stack

- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn 
- **Machine Learning Models:** XGBoost, Random Forest
- **Time Series Forecasting:** STL Forecasting, Exponential Smoothing

---

### 📊 Model Performance

The performance of different models was evaluated on key metrics: **RMSE**, **R²**, and **WMAE**.

| Model                 |    RMSE   |      R²    |   WMAE    |
|-----------------------|-----------|------------|-----------|
| Random Forest         |  4319.09  |   0.9463   |  1555.39  |
| XGBoost               |  4149.39  |   0.9504   |  1575.30  |
| Exponential Smoothing | 270399.12 | -209.6525  | 237559.44 |


---

## 🔮 Future Scope

- Deploying a simple prediction app (e.g., Streamlit/Dash).
- Expanding to more advanced models (LSTM, Prophet).
- Automating data pipeline and evaluation reports.


