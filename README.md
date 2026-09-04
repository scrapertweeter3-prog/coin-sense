# Coin Sense

Real-time cryptocurrency portfolio tracker. A CLI tool that watches your holdings
and prints P/L, allocation, and 24h moves.

## What it does
- Fetches live prices from public exchange APIs (no key needed for the top coins)
- Computes allocation % and realized/unrealized P/L from a cost-basis file
- Alerts when a coin moves more than a set % in a window
- Exports a weekly markdown report

## Stack
Python, requests, selenium for the odd exchange that blocks plain HTTP, rich for the TUI.

Built as a side project that later went into the [Poket Dev](https://www.poketdev.com/) portfolio.

[Portfolio](https://www.poketdev.com/).
