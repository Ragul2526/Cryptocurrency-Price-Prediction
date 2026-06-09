# Crypto Price Prediction

A machine learning project that fetches live cryptocurrency prices from the CoinGecko API and forecasts future prices using statistical and deep learning models.

## Coins covered
Bitcoin (BTC), Ethereum (ETH), Solana (SOL), XRP,LiteCoin (LTC)

## Models used
- Simple Exponential Smoothing (SES)
- Holt-Winters Exponential Smoothing (HWES)
- ARIMA & SARIMA
- LSTM (deep learning)

## How to run
Click the button below to open directly in Google Colab — no installation needed.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ragul2526/Cryptocurrency-Price-Prediction/blob/main/crypto_prediction.ipynb)

## Results
===RMSE Comparison (lower is better)===

| Coin | SES | HWES | ARIMA | SARIMA | LSTM |
|------|-----|------|-------|--------|------|
| BTC  | $45309 | $22129 | $45304 | $45481 | $3570 |
| ETH  | $857 | $985 | $855 | $857 | $164 |
| SOL  | $44 | $44 | $44 | $44 | $6 |
| XRP  | $1.61 | $1.58 | $1.61 | $1.61 | $0.41 |
| LTC  | $26 | $31 | $26 | $26 | $5.5|

HWES was the best statistical model. LSTM outperformed all statistical models.

### Sample prediction chart
<img width="1389" height="490" alt="image" src="https://github.com/user-attachments/assets/29ccd1fa-c07a-4e78-b69c-acc6817bcccc" />

