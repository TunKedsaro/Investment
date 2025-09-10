💰💸 Investment with IBKR API — Trading Chatbot

A production-ready starter for building a chatbot that talks to Interactive Brokers (IBKR) via the TWS / IB Gateway API to fetch quotes, place paper trades, and run portfolio utilities — with strong safety rails, logging, and tests.

⚠️ Disclaimer
For education and paper trading. Markets are risky. You are responsible for all usage.

✨ Features

Chatbot layer: natural-language → trading intents (quotes, order status, positions, P/L).

IBKR integration: ibapi event loop with clean async handoff.

Paper trading first: easy toggle to live later.

Risk controls: max order size, symbol allowlist, trading windows.

Config: .env for ports, accounts, and risk limits.

Logging & metrics: rotating logs, request/response correlation IDs.

FastAPI webhook (optional) for chat UI or messaging platforms.