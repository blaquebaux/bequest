# Blaque Baux Bequest

**Systematic Dividend Capture (Friction-Adjusted) — STUB (blocked on data).**

Long high-yield stable dividend stocks one day before ex-date, short a sector ETF to hedge beta, capturing the dividend; tested with real friction (borrow, tax, ex-date gap).

> **Status: STUB / DATA-BLOCKED.** This sleeve is specified and queued but **not yet built** — it needs ex-dividend dates and per-share dividend amounts. Our total-return bars (adjustment=all) deliberately fold dividends into price, so the ex-date event is invisible without a raw dividend calendar.

> **Not investment advice.** Educational/research software. See [DISCLAIMER](DISCLAIMER.md) and [LICENSE](LICENSE).

## Honest null (to be tested once the feed exists)

The ex-date drop is mathematically efficient — after bid-ask, short-ETF borrow, and qualified-vs-ordinary tax treatment, is there any net alpha, or a guaranteed transfer to market makers?

## Why it's a stub

The Blaque Baux research stack runs on Alpaca SIP **daily OHLCV + crypto**. Systematic Dividend Capture (Friction-Adjusted) cannot be tested faithfully on
price bars alone — it requires ex-dividend dates and per-share dividend amounts. Our total-return bars (adjustment=all) deliberately fold dividends into price, so the ex-date event is invisible without a raw dividend calendar. When that feed is wired in, this becomes `bequest_1` with the family's standard
fat-tail scorecard (Sharpe / CAGR / maxDD / skew / Jensen's alpha / M-squared), causal signals, and an honest verdict.

## Status

**Stub.** Placeholder for a queued sleeve awaiting a data source beyond price. No code, no backtest, no live capital yet.
