# InkyPi Finance Tracker Plugin

An [InkyPi](https://github.com/fatihak/InkyPi) plugin that displays live prices, percentage changes, and sparkline charts for crypto, stocks, commodities, and market indices on your e-ink display.

## Screenshot

<!-- Add a screenshot of the plugin running on your display here -->

## Supported Assets

| Type | Examples |
|---|---|
| Crypto | `bitcoin`, `ethereum`, `solana`, `btc`, `eth`, `doge`, `xrp`, … |
| Stocks / ETFs | `AAPL`, `MSFT`, `TSLA`, `SPY`, … |
| Commodities | `gold`, `silver`, `oil` |
| Indices | `dow`, `nasdaq`, `sp500` |

Enter assets as a comma-separated list in the settings, e.g. `bitcoin,dow,AAPL,gold`.

## APIs Used

- **[Yahoo Finance](https://finance.yahoo.com)** — used for crypto, stocks, commodities, and indices. No API key required.
- **[CoinGecko](https://www.coingecko.com/en/api)** — used as fallback for obscure crypto coins not available on Yahoo Finance. No API key required for basic usage, but the free public API is rate-limited. A free [Demo API key](https://www.coingecko.com/en/api/pricing) is recommended if you rely on this path heavily.

## Installation

Run the following command on your Raspberry Pi:

```bash
inkypi plugin install finance_tracker https://github.com/BloodAkatsuki/InkyPi-FinanceTracker
```

## Status

Actively maintained.
