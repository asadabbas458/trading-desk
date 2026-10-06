# Trading Bot + Asad: paper-trading desk

A single-page dashboard where a team of simulated "agents" (CHIEF, SCAN, VET, SOCIAL, SIZE, FILLS, RISK, CRAWLER) scan live Solana memecoin data from the public DexScreener API, vet each coin against the rules in the `thresholds.py` panel, and place **pretend** trades.

**Live site:** https://asadabbas458.github.io/trading-desk/

## Important

- **Paper trading only.** It starts with a simulated $10,000 balance. It never connects a wallet, holds no keys, and never places real orders.
- **Not financial advice.** The agents are simple heuristics for fun and learning. Memecoins are extremely risky.
- Progress (balance, trades, edited thresholds) is saved only in your own browser's localStorage.
- An optional xAI/Grok API key can be entered in Settings; it is stored only in your browser and is never part of this repo.

## Data sources

- Market data: DexScreener public API
- Candles: GeckoTerminal public API
- Charts: TradingView Lightweight Charts
