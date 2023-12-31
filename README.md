# Cryptocurrency Trading Bot

This project is a basic framework for creating a cryptocurrency trading bot that automates trading using popular technical indicators like the Relative Strength Index (RSI) and Moving Average Convergence Divergence (MACD).

## Overview

Cryptocurrency is a digital asset traded on various exchanges. This trading bot fetches live data from an exchange, applies a simple trading algorithm, and executes buy and sell orders based on the algorithm's signals.

## Building the Trading Bot

The project follows a three-step process:

### Step 1: Connect to an Exchange to Fetch Live Data

We use the CCXT library to connect to the Binance exchange, for example, and fetch cryptocurrency price data. You can use other exchanges and APIs as well.

### Step 2: Apply the Trading Strategy

The trading strategy implemented here is a basic one. It uses the RSI and MACD indicators to make buy and sell decisions. This strategy can be improved by adding more technical indicators, candlestick patterns, and setting minimum profit percentages and stop-loss levels.

### Step 3: Execute the Trade

To execute trades programmatically, you need an exchange that provides trading APIs, an account with that exchange, and API keys. We demonstrate this using WazirX as an example.

## Requirements

- An exchange with trading APIs
- An account with the exchange
- API keys to access your trading account
- Sufficient funds in your trading account

## Usage

- Clone this repository.
- Set up your API keys and trading preferences in the configuration file.
- Run the bot to start trading.

## Further Improvements

This project provides a simple framework for creating a trading bot. You can further enhance it by:

- Adding more technical indicators
- Incorporating candlestick patterns
- Implementing profit percentage thresholds for sell orders
- Setting stop-loss levels
- Implementing multiple order placement strategies

## Conclusion

This basic trading bot framework is a starting point for building your own trading algorithm. Feel free to explore, enhance, and adapt it to your specific trading needs.

**Note:** Keep in mind that external factors beyond technical analysis can significantly impact trading results.



