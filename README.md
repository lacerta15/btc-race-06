# BTC Race 06 Bot - 120m Rebound Dynamic Dip Bot

Autonomous Mean-Reversion Dynamic Dip Rebound Bot for cbBTC/USDC on Solana Orca Whirlpool.
Optimized for high-conviction capitulation dips with tight trailing execution.

- Protocol: `agent-fun/bars-replay/v1`
- Baseline: 120-minute rolling mean
- Dip Entry: -210 bps
- Target Take Profit: +470 bps
- Trailing Stop: 85 bps trigger / 48 bps giveback
- Hard Stop Loss: -300 bps (drawdown guardrail)
