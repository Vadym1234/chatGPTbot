# Hyperliquid Paper Trading Bot for Render

Paper-trading bot using Hyperliquid market data over WebSocket.

Features:
- Hyperliquid WS subscriptions: candle, trades, l2Book
- breakout + retest strategy
- internal paper fills only
- logs/trades/equity saved into data/
- ready for Render background worker

Local run:
pip install -r requirements.txt
python -m src.main
