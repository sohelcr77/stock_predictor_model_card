# 📊 Stock Price Prediction using LSTM

This project presents a **Long Short-Term Memory (LSTM)-based model** for predicting next-day stock prices using historical time-series data. It combines machine learning modelling, a deployed web application, and a structured model card for transparency and evaluation.

---

## 🚀 Live Application

🔗 https://stockpricepredictor-s25013941com763.streamlit.app/

---

## 🌐 Project Website (Model Card)

🔗 https://sohelcr77.github.

---

## 💻 GitHub Repository

🔗 https://github.com/sohelcr77/stock_price_predictor

---

## 📌 Project Overview

Stock price prediction is a challenging task due to market volatility and non-linear patterns.
This project applies an LSTM neural network to learn temporal dependencies in stock data and generate short-term forecasts.

The model is designed as a **decision-support tool**, not for direct financial decision-making.

---

## 🧠 Model Details

* **Model Type:** Time-series regression
* **Architecture:** LSTM (Recurrent Neural Network)
* **Input Features:** Open, High, Low, Close, Volume (OHLCV)
* **Output:** Next-day stock price prediction

---

## 📊 Performance Metrics

| Metric    | Value  |
| --------- | ------ |
| Test Loss | 0.1951 |
| MAE       | 0.2293 |
| MAPE      | 56.75% |

👉 The model captures overall trends but shows limitations in precise prediction accuracy.

---

## 🗂 Dataset

* **Source:** Dhaka Stock Exchange
* **Time Range:** 2014 – 2023
* **Type:** Daily stock market data

---

## ⚠️ Limitations

* Sensitive to market volatility
* Does not include external factors (news, sentiment, macroeconomics)
* Trained on a single stock (limited generalisation)

---

## ⚖️ Responsible Use

This model should be used **only for analysis and educational purposes**.
Predictions must be interpreted cautiously and combined with domain knowledge and additional financial information.

---

## 🖥️ Application Features

The Streamlit application provides:

* Interactive user interface
* Input-based prediction system
* Visual representation of stock trends
* Easy access for non-technical users

---

## 📸 Application Preview

*(Add your screenshot here)*
![App Screenshot](screenshot.png)

---

## 📚 References

* Lo & MacKinlay (1999) – *A Non-Random Walk Down Wall Street*
* Nelson et al. (2017) – LSTM stock prediction
* Box et al. (2015) – Time Series Analysis
* Hochreiter & Schmidhuber (1997) – LSTM
* Fischer & Krauss (2018) – Deep learning in finance

---

## 👨‍🎓 Author

**Md. Shohel Rana**
Student ID: S25013941
Module: COM763 – Advanced Machine Learning

---

## ⭐ Notes

* This project demonstrates the application of deep learning in financial forecasting
* Emphasis is placed on **model transparency, evaluation, and responsible use**
* The work includes both **technical implementation and ethical considerations**

---
