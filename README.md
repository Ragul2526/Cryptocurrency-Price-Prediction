# Crypto Price Prediction

A machine learning project that fetches live cryptocurrency prices from the Yahoo finance and forecasts future prices using statistical and deep learning models.

## Coins covered
Bitcoin (BTC), Ethereum (ETH), Solana (SOL), XRP,LiteCoin (LTC)
## Data source 
Yahoo Finance via `yfinance` — no API key required

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
### Sample LSTM prediction chart

<img width="629" height="470" alt="image" src="https://github.com/user-attachments/assets/8e286b72-1db5-4d34-9a95-cf0ce36391d6" />

<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/a2a0207b-9834-480e-ba58-4d4c78d9226c" />

<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/d74303e4-c81f-4211-81c3-e5556bf7b0e0" />

<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/bed7d276-313f-41d5-9e56-a57a2aa3cf0f" />

<img width="629" height="470" alt="image" src="https://github.com/user-attachments/assets/0df23ede-ad47-452f-84d0-1da4973bfcc1" />

### Comparison chart

<img width="1389" height="490" alt="image" src="https://github.com/user-attachments/assets/29ccd1fa-c07a-4e78-b69c-acc6817bcccc" />

<img width="1389" height="490" alt="image" src="https://github.com/user-attachments/assets/c84066ca-4c4c-4ab4-b3f7-46f21b5abd6e" />

<img width="1390" height="490" alt="image" src="https://github.com/user-attachments/assets/741852d7-5d82-4d89-88fb-885a40834802" />

<img width="1389" height="490" alt="image" src="https://github.com/user-attachments/assets/404b0434-5f35-4871-b46c-576273935ba3" />

<img width="1389" height="490" alt="image" src="https://github.com/user-attachments/assets/76126cfa-b0cd-4036-b103-dd2d92dffe83" />


