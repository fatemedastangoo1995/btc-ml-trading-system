# BTC ML Trading System 

This project develops an end-to-end machine-learning pipeline for predicting meaningful Bitcoin price movements using hourly BTCUSDT market data.

## Project goals

- collect and validate BTC hourly data
- create financial features without data leakage
- train Logistic Regression and CatBoost models
- use chronological and walk-forward validation
- create financial features without data leakage
- train Logistic Regression and CatBoost models
- use chronological and walk-forward validation
- include transaction fees and slippage
- compare ML models with simple trading baselines
- deploy the final strategy in QuantConnect paper trading
- apply strict position sizing and risk controls

## Initial research question

Can information available at the close of the current hourly candle help predict whether Bitcoin will move meaningfully during the following four hours?

## Current status

- project repository created
- Python virtual environment created
- required Python packages installed
- data pipeline not yet implemented

## Important note

This project is educational and experimental. Backtest results do not guarantee future profitability.
