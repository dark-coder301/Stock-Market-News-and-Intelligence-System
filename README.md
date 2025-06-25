# Stock-Market-News-and-Intelligence-System
 A Python-based real-time stock monitoring and alert app with GUI, graph, and SMS support
# 📈 Real-Time Stock Alert System

A Python-based desktop application that monitors live stock prices, plots trend charts, fetches financial news, and sends instant SMS alerts for significant price changes using Twilio.

---

## 🔧 Features

- 📊 **Real-time stock tracking** via [Alpha Vantage API](https://www.alphavantage.co/)
- 📰 **Latest news headlines** via [NewsAPI](https://newsapi.org/)
- 📈 **7-day trend graph** generated using `matplotlib`
- 💬 **SMS alerts** sent instantly via `Twilio API`
- 🖥️ **User-friendly GUI** with multi-tab layout using `Tkinter`

---

## 🚀 How It Works

1. Enter a stock symbol (e.g. `TSLA`) and company name.
2. Set your custom alert threshold (e.g. 5%).
3. Provide your phone number.
4. The app:
   - Checks for price change using Alpha Vantage
   - If change ≥ threshold, fetches news + plots graph
   - Sends an SMS with stock direction + news summary

---

## 🖼️ GUI Preview

![App Screenshot](stock_trend_plot.png)

---

## 🛠️ Tech Stack

- Python 3
- Tkinter
- Matplotlib
- Twilio REST API
- Requests
- PIL (for image display)
- Alpha Vantage & NewsAPI

---

## 📦 Installation

```bash
pip install requests twilio matplotlib pillow
python stock_alert_app.py
