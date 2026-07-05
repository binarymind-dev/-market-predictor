# 📈 Market Predictor

> AI-powered stock market prediction using LSTM Neural Network, FastAPI backend with WebSockets, and React frontend with real-time charts.

![Python](https://img.shields.io/badge/Python-3.14-blue) ![FastAPI](https://img.shields.io/badge/FastAPI-0.136-green) ![React](https://img.shields.io/badge/React-18-61DAFB) ![PyTorch](https://img.shields.io/badge/PyTorch-LSTM-red)

🔗 **Live Demo:** [market-predictor-silk.vercel.app](https://market-predictor-silk.vercel.app)

## 📸 Screenshot

![Dashboard](https://raw.githubusercontent.com/snehal-thombare08/-market-predictor/main/Screenshot%202026-06-01%20233026.png)

## 🚀 Features

- 🧠 LSTM Neural Network for stock price prediction
- 📊 Real-time price charts with Recharts
- ⚡ FastAPI backend with WebSocket support
- 📡 Live stock data via Yahoo Finance API
- 🎯 BUY/SELL signal generation
- 🌙 Dark theme professional UI

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| ML Model | PyTorch LSTM |
| Backend | FastAPI + WebSockets |
| Data | Yahoo Finance (yfinance) |
| Frontend | React + TypeScript |
| Charts | Recharts |
| Deployment | Vercel + Render |

## ⚙️ Setup

\```bash
cd backend
python -m venv venv
venv\Scripts\activate
pip install fastapi uvicorn websockets yfinance pandas numpy torch scikit-learn
uvicorn main:app --reload --port 8001

cd frontend
npm install
npm start
\```

## 📖 Usage

1. Open [market-predictor-silk.vercel.app](https://market-predictor-silk.vercel.app)
2. Enter stock symbol (AAPL, TSLA, GOOGL)
3. Click **Analyze**
4. View prediction + BUY/SELL signal + 30-day chart

👩‍💻 Author
Binary Mind — [GitHub](https://github.com/binarymind-dev)
