# Market Intelligence Dashboard


# by Nitya Jignasu

A live, interactive market intelligence dashboard built with vanilla HTML, CSS, and JavaScript. Pulls real-time financial data from the Finnhub API and runs entirely in the browser — no server, no build step, no dependencies to install.

Live Demo View Dashboard → 

# Features
# Overview Tab

Live index strip — S&P 500, Nasdaq 100, Dow Jones, Russell 2000, VIX proxy, 10-Yr Yield
Fear & Greed Composite — scored 0–100 gauge blending VIX, market momentum, put/call ratio, and 52-week breadth
Sector Performance — 11 S&P sectors ranked by 1-day return
Customisable Watchlist — add or remove any ticker, prices refresh every 30 seconds
Market Headlines — live news feed with bullish/bearish/neutral sentiment tagging
Key Macro Indicators — Fed rate, CPI, unemployment, GDP, Core PCE, ISM PMI
Economic Calendar — next 7 days of high-impact market events

# Analysis Tab

Watchlist + Technical Signals — RSI (14), vs SMA50 deviation, ML signal (BUY/HOLD/SELL), composite score
ML Signal Log — algorithmically generated signals with reasoning for tracked stocks
Sector Rotation — sectors ranked for rotation analysis
Macro Regime Indicators — equity trend, credit stress, dollar strength, rate pressure, global PMI
Portfolio Stress Tester — simulate your equity/bond/cash allocation against COVID-19, GFC 2008, Dot-com 2000, and a 10% correction
Key Price Levels — support and resistance for major assets
Market Catalysts — live news filtered for market-moving events


# Tech Stack
LayerChoiceFrontendVanilla HTML / CSS / JavaScriptDataFinnhub API (free tier)FontsDM Serif Display + DM Sans + DM MonoHostingGitHub PagesDependenciesNone

# How It Works
The dashboard connects to the Finnhub API to fetch live market prices. It is pre-configured with an API key — just open the live link above and it works immediately with no setup, no login, and no API key required from you.
Prices refresh automatically every 30 seconds. Your personal watchlist is saved to your browser's local storage, so your tickers persist across visits.


# Disclaimer
_This dashboard is built for educational purposes only. It is not financial advice and should not be used as the basis for any real investment decisions. Data may be delayed. Signals (RSI, ML scores) are algorithmically generated and unverified. Always consult a licensed financial advisor before investing._

# Related Projects
Starbucks DCF Valuation — Scenario-based DCF model
NVIDIA Monte Carlo Simulation — Python-based price simulation
