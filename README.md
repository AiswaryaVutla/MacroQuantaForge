# MacroQuantaForge
MacroQuant 2026 – Gold & Silver Forecasting
📌 Overview

This project builds a machine learning–driven trading system to forecast Gold returns using macroeconomic and market variables.
The goal is to achieve high directional accuracy and superior risk-adjusted trading performance.

📊 Data Used

Gold & Silver Prices

DXY (Dollar Index)

S&P 500

Oil Prices

CPI (Inflation)

M2 Money Supply

US 10Y Yield

🧠 Feature Engineering

Created predictive features including:

Lag Returns (Gold_lag1, Gold_lag5, Silver_lag1)

Rolling Volatility (20-day)

RSI & MACD Indicators

CPI YoY Growth

M2 Growth Rate

Market Returns (DXY, SP500, Oil)

Gold/SP500 & Gold/DXY Ratios

Target Variable: Next-Day Gold Return (t+1)

🤖 Models Used

Random Forest Regressor

XGBoost Regressor

Ridge Regression

Ensemble Model (Average of all three)

📈 Evaluation Metrics

RMSE

MAE

R² Score

Directional Accuracy

Confusion Matrix (Type 1 & Type 2 Errors)

Sharpe Ratio

Maximum Drawdown

💰 Trading Strategy

If Predicted Return > 0 → Buy

Else → Stay Out

Backtested against Buy & Hold

🚀 Results

Directional Accuracy: ~83%

RMSE: ~0.015

Sharpe Ratio: ~1.7

Strategy Outperformed Buy & Hold

🏁 Conclusion

Macro variables such as DXY and CPI significantly influence gold price movement.
The ensemble model delivered strong predictive performance and improved risk-adjusted returns.

