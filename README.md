# Muhammad Ihsan — Trading Systems Engineer

I design, build, and operate **[hyperpetual.com](https://hyperpetual.com)** — a live perpetual-futures trading platform shipped solo, end-to-end:

- **Rust market-data engine** (axum/tokio) — Binance futures WebSocket ingestion for 30+ symbols: L2 order book, trades, klines, liquidations, into a 900 GB+ rolling history
- **Python/FastAPI execution backend** — real-money orders on Binance USDS-M Futures; 110 ms placement, 96.5% exchange-API-weight reduction via a WebSocket-primary mirror
- **Next.js real-time terminal** — 15-timeframe charting, order-flow analytics (CVD, absorption, footprint, depth heatmap), drag-to-place SL/TP

### Focus
market-data infrastructure · low-latency order execution · tick-level backtesting · risk & position sizing

### Stack
`Python` `Rust` `TypeScript` `FastAPI` `axum / tokio` `Next.js` `PostgreSQL` `WebSockets` `k6`

### Selected work
- **[tick-backtest-engine](https://github.com/yumelionaire/tick-backtest-engine)** — tick-by-tick SL/TP resolution with fee-inclusive sizing, byte-level parity harness, and no-lookahead guarantees
- **[hyperpetual.com](https://hyperpetual.com)** — the live platform (real-money execution, payments, ops)

> The full platform repository is private (commercial product) — happy to walk through the architecture in a call.
