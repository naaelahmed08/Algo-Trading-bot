# Algo-Trading-bot
This project implements a basic trading bot using Python, with a **simple moving average (SMA) trading strategy**. It simulates market data fetching, generates trade signals, and executes trades using a **mock trading API.** This bot fetches price data for a specified stock symbol using the **yfinance library**, and it supports real-time decision-making based on defined strategies.

Key Components:
1) Trading Strategies: Base class (TradingStrategy) and a simple moving average strategy (SMAStrategy).
2) Trade Management: Manages trade signals and execution via the Trade class.
3) Mock API: Simulates order placement and balance management via MockTradingAPI.
4) Trading System: Handles integration of strategy, API, and price data via TradingSystem.
