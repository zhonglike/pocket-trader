# Pocket Trader

A stock-trading **practice game** with live quotes for **A-shares, Hong Kong and US stocks**.

Start with **USD 2,000** in a multi-currency wallet (USD / HKD / CNY — exchange between them yourself at live FX rates), then practise buying and selling real stocks at real, quasi-real-time prices. All progress is saved locally in your browser/app; a sign-in and cloud-sync interface is reserved for a future version.

## Play it

- **Web:** https://zhonglike.tech/pocket-trader/
- **Android:** download the APK from the [latest release](../../releases/latest)
- **Windows:** download the installer/portable build from the [latest release](../../releases/latest)

## Features

- Live quotes (Tencent primary, Sina backup), batched per market, auto-refresh every 5 seconds with the data delay shown on screen
- Stock detail pages in the style of Chinese trading apps: red = up, green = down, intraday chart with average-price line, daily K-line with MA5/MA10/MA20, five-level order book, limit-up / limit-down prices for A-shares
- Simulated trading: buy and sell at live prices, 1-share minimum, no T+1, no fees (practice rules)
- Multi-currency wallet: trades settle in each stock's own currency — no automatic conversion; use the built-in exchange at live FX rates
- Portfolio with cost / current price / P&L per position, full trade history, watchlist
- Light and dark themes; requires an internet connection; checks GitHub for new versions and prompts to update

## Notes

Quotes come from public endpoints (Tencent / Sina) and are quasi-real-time with a few seconds of delay — for practice only, not investment advice. This is a game: no real money, no real orders.

Current version: **1.0.0** (see `version.json`, which the app polls for update checks).
