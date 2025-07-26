# amazon-stock-prediction
Predicting Amazon stock price using machine learning

This project involves analyzing and forecasting Amazon's stock prices using historical data. The goal is to explore trends, engineer meaningful features, and use machine learning to predict the next day's closing price.

## 📁 Dataset

- Source: Amazon historical stock prices (CSV inside a ZIP file).
- Features include: `date`, `open`, `high`, `low`, `close`, `volume`.

## 🛠️ Features & Processing

- **Date parsing** and chronological sorting.
- **Missing value handling**.
- **Feature Engineering**:
  - `MA50`: 50-day moving average
  - `MA200`: 200-day moving average
  - `daily_return`: % change in closing price
  - `target`: next day closing price (prediction target)

## 📊 Visualizations

- **Closing Price vs Moving Averages** – Trend insight
- **Daily Returns Distribution** – Volatility overview
- **Actual vs Predicted Closing Prices** – Model performance

## 🤖 Machine Learning

- **Model Used**: Linear Regression
- **Train-Test Split**: 80/20 (no shuffle, due to time series nature)
- **Feature Scaling**: StandardScaler
- **Evaluation Metrics**:
  - RMSE: 3.24
  - R² Score: 0.9902

## 📈 Results

The Linear Regression model performs exceptionally well, with an R² of 0.99, indicating a strong ability to predict future stock prices based on selected features.

## 📎 Future Improvements

- Add other models like **Random Forest**, **XGBoost**, or **LSTM**.
- Explore more advanced **time series techniques**.
- Include **technical indicators** (RSI, MACD).
- Build a **streamlit dashboard** for interactive visualization.

## 💻 Libraries Used

- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn (modeling & evaluation)

## 📬 Contact

**Sello Evans Matjila**  
📧 evanssello04@gmail.com  
📍 Johannesburg, South Africa

---

> This project is part of my portfolio to demonstrate skills in data preprocessing, visualization, and predictive modeling.
