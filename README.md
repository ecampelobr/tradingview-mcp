# bot-data

Sync branch for the paper-trade-bot's Layer 1 screen output and fundamentals watchlist.

- `last-screen.json` — written by the local bot every ~5 min cycle (top Layer-1 candidates).
- `watchlist.json` — written by a separate cloud-scheduled agent every ~4h (fundamentals blocked/boosted symbols), read by the local bot.

This branch intentionally has no relation to `main`'s history — it exists only as a data handoff point between the local bot and the cloud fundamentals agent.
