# STRIKE//ZERO

An original, mobile-first browser puzzle game that teaches multi-leg **options strategies** for buyers who want **defined risk**.

You take contracts from a fixer in a neon city. Each contract is a market view ("up big", "flat", "volatility spike"...). Assemble a payload of option legs (buy/sell, call/put, strike, quantity, expiry), watch the glowing 3D profit/loss surface reshape in real time, and execute once every rule is green. Any leg combination with unlimited loss trips the **firewall**, and the game explains why.

**Play:** open `index.html` (single self-contained file, works offline, portrait phone first; desktop mouse works too).

## Contracts
1. Long call  2. Long put  3. Bull call spread  4. Bear put spread  5. Long straddle (earnings / IV crush)
6. Long strangle  7. Long call butterfly  8. Long calendar (time & IV)  9. Protective put / collar
10. Call backspread  + Free build sandbox with a market-scenario simulator

## Model
Black-Scholes (European, no dividends, 3% rate, no fees, no early exercise), contract multiplier 100. Payoff, max loss/gain, breakevens and greeks are computed in code and unit-tested.

## Disclaimer
**Educational simulation only. Not financial advice.** Real markets have fees, spreads, assignment risk, dividends and changing volatility that this model simplifies.

Inspired by the general look of neon-noir sci-fi and hacker fiction. All names, art, text and sound are original; no third-party game or film assets, logos, or characters are used. Rendering uses three.js (MIT), inlined.
