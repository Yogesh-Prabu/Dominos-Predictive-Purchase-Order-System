# 🍕 Dominos - Predictive Purchase Order System

## 📌 Project Overview
Dominos wants to optimize its ingredient ordering process by predicting future pizza sales. This project leverages **time series forecasting** to generate an efficient **purchase order system**, ensuring optimal inventory levels while minimizing waste and stockouts.

## 🏆 Key Features
- **Sales Forecasting**: Predict future pizza sales using machine learning models.
- **Inventory Optimization**: Generate purchase orders based on sales forecasts.
- **Cost Reduction**: Prevent overstocking and minimize ingredient wastage.
- **Business Decision Support**: Helps Dominos streamline its supply chain management.

## 🛠 Tech Stack
- **Python**
- **Pandas, NumPy** (Data Preprocessing)
- **Matplotlib, Seaborn** (Data Visualization)
- **Statsmodels (ARIMA, SARIMA), Prophet** (Time Series Forecasting)
- **Scikit-learn** (Model Evaluation)

## 📊 Approach
### 1️⃣ Data Preprocessing & Exploration
- Cleaned sales and ingredient datasets
- Handled missing values and outliers
- Conducted **Exploratory Data Analysis (EDA)** to identify trends & seasonality

### 2️⃣ Time Series Forecasting
- Feature Engineering: Created relevant date-based features (day, month, holidays, promotions)
- Model Selection: **ARIMA, SARIMA, Prophet**
- Model Training & Evaluation: Used **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)** for performance assessment

### 3️⃣ Purchase Order Generation
- Predicted sales for the next **one week**
- Mapped ingredient requirements for each pizza type
- Generated an automated **purchase order**

## 🚀 Installation & Usage
### Prerequisites
Make sure you have Python installed along with the required libraries:
```bash
pip install pandas numpy matplotlib seaborn statsmodels prophet scikit-learn
```

### Run the Project
```bash
python main.py
```

## 📈 Model Performance
| Model   | MAE  | RMSE  |
|---------|------|-------|
| **ARIMA**  | 1.70 | 2.05  |
| **SARIMAX** | 1.74 | 2.00  |
| **Prophet** | **1.48** | **1.62**  |

> Prophet gave the best performance in predicting future sales.

## 📜 Project Deliverables
- ✅ Cleaned and Preprocessed Datasets
- ✅ Exploratory Data Analysis Report
- ✅ Trained Time Series Models (ARIMA, SARIMA, Prophet)
- ✅ Generated Purchase Order System
- ✅ GitHub Repository with Full Code & Documentation

## 📝 Future Enhancements
- Implement **LSTM (Deep Learning)** for better long-term forecasting.
- Integrate **Real-time Sales Data** for dynamic predictions.
- Automate the purchase order system using **APIs**.

## 🤝 Contributing
Pull requests are welcome! Feel free to raise issues or suggest improvements.

## 📬 Contact
For any queries, feel free to reach out!

---
⭐ **If you found this project helpful, don't forget to star the repository!** ⭐
