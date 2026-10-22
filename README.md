# Cryptovexxing

Multi-desk crypto terminal for research and paper trading.

**Live:** https://golddexzy-create.github.io/Cryptovexxing.com/

## What it is

Not a clone of Axiom or GMGN. The differentiator is **Pre-Noise Score** — rank launches by structure (authorities, age, source) *before* social volume spikes.

## Desks

| Desk | Status |
|------|--------|
| **Pulse** | Live SolanaForge launches + simulated pad density, Pre-Noise ranked |
| **Audit** | Structure / rug checklist; live authority flags when mint is from SolanaForge |
| **Paper trade** | Buy / sell / sim burn — no real orders |
| **Perps** | Leverage ticket UI — paper only |
| **Predictions** | Event / sports board template |
| **Majors** | Live BTC/SOL/ETH/XRP/DOGE via CoinGecko |

## Stack

- Static HTML/CSS/JS on GitHub Pages
- [SolanaForge public API](https://solanaforge.app/api) (CC-BY-4.0, attribution)
- CoinGecko simple price API

## Not included (yet)

- Real Jupiter / pump.fun execution
- Full pump.fun firehose (needs paid indexer: Helius, Solana Tracker, etc.)
- Live Hyperliquid perps or Polymarket odds

## Local

Open `index.html` in a browser or any static server.

## Related

- **UseCaseAgents:** https://github.com/golddexzy-create/usecaseagents  
  Live: https://usecaseagents-2ti5.vercel.app

## Disclaimer

Not financial advice. Paper mode does not send transactions. Live feeds can lag or fail. Verify everything on-chain yourself.
