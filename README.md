# WPS.AI | Institutional-Grade Stock Scorer

**WPS.AI** is a high-performance, client-side trading dashboard that utilizes **Gemini 2.0 Flash** to perform deep-dive technical and fundamental analysis on NSE (National Stock Exchange of India) stocks. The tool is built around the **7-Pillar WPS Methodology v2.0**, designed to identify high-conviction setups by correlating institutional data, technical structures, and market regime filters.

## ⚡ Key Features

* **AI Scorer:** Instant analysis of any NSE symbol across 7 weighted pillars.
* **Side-by-Side Compare:** Compare up to 4 symbols simultaneously with a winner-take-all metric table.
* **Weekly Checklist:** Pre-market routine tracker for Market Regime (Nifty 200 EMA), India VIX, and FII/DII flow analysis.
* **Trade Journal:** Persistent storage for saved analyses with P&L tracking and trade outcome logging.
* **Smart Watchlist:** Pipeline management with a "Rescan All" feature to batch-process symbols through the AI engine.

## 📊 The 7-Pillar Methodology

The tool calculates a Weighted Property Score (WPS) based on the following framework:

| Pillar | Focus | Weight |
| --- | --- | --- |
| **P1** | **Relative Strength** | RS Rating ≥70 & Trending |
| **P2** | **Technical (P&F)** | Point & Figure 45° trendline & Volume |
| **P3** | **Sector Rotation** | RS Ranking vs Nifty & FII Sector Flow |
| **P4** | **Fundamentals** | YoY Profit Growth, D/E Ratio, & Cash Flow |
| **P5** | **Institutional** | Bulk/Block deals & FII/DII Shareholding |
| **P6** | **Risk/Reward** | Minimum 2:1 R:R & Stop-Loss placement |
| **P7** | **Liquidity** | Daily turnover & Market Cap filters |

## 🛠 Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Grid System), Vanilla JavaScript.
* **LLM:** Gemini 2.0 Flash API (via Google AI Studio).
* **Data:** Live NSE price action via Yahoo Finance API proxy.
* **Storage:** Browser `localStorage` for persistent data (No database required).

## 🚀 Getting Started

1. **Clone/Host:** Simply run `index.html` locally or host it on GitHub Pages.
2. **API Key:** Obtain a free Gemini API key from [Google AI Studio](https://aistudio.google.com/apikey).
3. **Input:** Enter an NSE symbol (e.g., `RELIANCE`, `HAL`, or `HDFCBANK`).
4. **Analyze:** The AI will process the 7 pillars and return a conviction-based verdict.

---

### ⚠️ Disclaimer

*This tool is for educational and analytical purposes only. It does not constitute financial advice. Always consult with a SEBI-registered advisor before making investment decisions.*

---
