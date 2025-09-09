# TRADING_BOT
Binance Futures Testnet Trading Bot A Python-based trading bot with a Gradio web interface for Binance Futures Testnet. Connect your account, check balances, and place MARKET, LIMIT, or STOP_MARKET orders safely. Perfect for testing trading strategies without real funds.
# Binance Futures Testnet Trading Bot

A Python-based trading bot with a **Gradio web interface** for Binance Futures Testnet.  
This bot allows you to **connect to your testnet account**, **check balances**, and **place MARKET, LIMIT, or STOP_MARKET orders** safely.  
Perfect for testing trading strategies without risking real funds.

---

## Features

- Connect to Binance Futures Testnet using your API keys  
- Check account balance (USDT or other assets)  
- Place orders:
  - **MARKET**: Buy/sell immediately at market price  
  - **LIMIT**: Buy/sell at a specific price  
  - **STOP_MARKET**: Trigger a market order when a stop price is reached  
- Simple and interactive **Gradio-based web interface**  
- Logging of all API requests and errors for debugging

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/binance-futures-testnet-bot.git
cd binance-futures-testnet-bot
pip install -r requirements.txt
python-binance
gradio
to run the bot "python trading_bot_ui.py"

Usage

Connect tab:

Enter your Binance Testnet API Key and API Secret.

Click Connect to Testnet. Your USDT balance will be displayed.

Trade tab:

Enter the trading pair (e.g., BTCUSDT)

Select BUY or SELL

Choose Order Type: MARKET, LIMIT, or STOP_MARKET

Enter Quantity

Enter Price for LIMIT orders (optional for others)

Enter Stop Price for STOP_MARKET orders (optional for others)
