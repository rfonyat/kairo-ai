# KAIRO

**A multi-agent AI system that researches the stock market every day and monitors it live.**

`Python` `Claude multi-agent` `PyTorch` `scikit-learn` `SQLite` `WebSockets` `JavaScript / WebGL`

<!-- Add a 60-90 second demo GIF or video here (tickers blurred) -->

## What it does

- 🔎 **Researches** thousands of US stocks every day and turns them into a short, explained watchlist, using AI agents
  for chart vision and news research
- ⚡ **Monitors** live market data all day and alerts my phone within seconds
- 📊 **Measures itself**: every output is logged before the outcome is known, then scored

## What I built

- A **multi-agent AI pipeline** that runs every day without supervision, within fixed AI-usage limits
- **ML research** with walk-forward testing and locked holdout sets. My first model's skill turned out to be mostly a
  simple market effect, so I retired it and rebuilt the system around AI agents.
- A **real-time monitoring service** with alert de-duplication and a health watchdog
- A **self-hosted web app** for desktop and phone (private network, push notifications, WebGL)

> Research project, in daily use. **Not proven profitable**, not a trading system. I make my own decisions.

**More:** [System overview](docs/system-overview.md) · [Full details](docs/details.md)

---
<sub>Trading rules, prompts, models and data are private. Not financial advice. © 2026 Rafael Fonyat. All rights reserved.</sub>
