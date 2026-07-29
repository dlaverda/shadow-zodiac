# 🪐 Shadow-Zodiac — Premium Dashboard & AI Sentiment Sentinel

[![Version](https://img.shields.io/badge/version-2.6.1-blue.svg)](https://gitlab.com/d.laverda-group/d.laverda-project)
[![License: Lemon Squeezy](https://img.shields.io/badge/License-Lemon%20Squeezy-green.svg)](https://www.lemonsqueezy.com/)
[![Language: English](https://img.shields.io/badge/Language-English-brightgreen.svg)](#)

> **Transform your eToro experience with professional-grade market intelligence.**

**Shadow-Zodiac** is the ultimate command center for modern investors. It combines real-time portfolio tracking with deep AI-driven sentiment analysis to help you make smarter, data-backed decisions in today's fast-moving markets.

---

## ⚠️ Important Legal Notice & Capital Loss Risk Warning

### INVESTMENT RISK WARNING

Investing in financial markets (stocks, bonds, funds, ETFs, derivatives, or any other financial instruments) involves significant risks.

1. **Risk of Capital Loss**:
   Past performance is no guarantee of future results and does not constitute a performance yield guarantee. The value of investments and the income derived from them can fluctuate up or down. You may not recover the amount initially invested. In certain specific cases (notably when utilizing leverage or deferred settlement services), losses may even exceed your initial capital deposit.

2. **No Financial Advice**:
   The information, analyses, charts, or data provided to you are strictly for indicative decision-support purposes and do not in any way constitute investment advice, a sales offer, or a solicitation to buy or sell financial instruments.

3. **Profile Suitability**:
   Before making any investment decision, it is the sole responsibility of the investor to ensure that chosen assets correspond to their financial situation, level of knowledge and experience, investment objectives, and placement time horizon. If you do not understand the risks associated with financial instruments, consulting an independent financial advisor is strongly recommended.

4. **No Automated eToro Order Execution**:
   Shadow Zodiac **does NOT execute buy or sell orders** on eToro or any third-party broker. The application has no automated order submission or trading execution capabilities. All final trading choices remain under the exclusive control of the investor.

---

## 🌟 Why Traders Choose Shadow-Zodiac

- **AI-Powered Market Intel**: Go beyond simple charts. Trigger deep sentiment analysis synthesizing technical trends, fundamental data, news, and geopolitical risks for any asset.
- **The "Sentiment Sentinel"**: Don't just watch the market; understand the hidden consensus. Our AI monitors market moods to give you an edge before the crowd reacts.
- **Aggressive Growth Strategy**: Configure the AI to act as your personal strategist, optimized for capital growth, fiscal efficiency, and compound returns.
- **Full Privacy**: Unlike web-based trackers, Shadow-Zodiac runs locally on your machine. Your API keys, trading data, and reflections are stored 100% locally in SQLite—no prying eyes.
- **Offline-Ready**: Trade with confidence even when your connection drops, with a secure offline grace period for full functionality.

---

## 🚀 Key Features

- **Real-Time eToro Portfolio Tracking**: Live tracking of account equity, available cash balance, allocated funds, open positions, daily/overall P&L, and sparkline trend charts.
- **AI-Powered Market Sentiment & Analysis**: Multi-engine AI support (Google Gemini `@google/genai`, LM Studio, AnythingLLM) generating technical and fundamental investment signals (`BUY` / `SELL` / `NEUTRAL`).
- **Multi-Horizon Confidence Scoring**: Structured 1-to-10 confidence ratings provided across 1-Month, 1-Year, and 5-Year time horizons for each position.
- **Side Drawer Split-Screen AI Assistant**: Interactive side drawer chat panel that resizes the main dashboard layout side-by-side when opened, featuring a thumbtack button and an instant **"Analyze and Optimize My Portfolio"** action.
- **AI Trading Signals History Pivot Matrix**: Full-width matrix table displaying assets in rows and historical dates in columns with color-coded buy/sell price cells and source badges (Market vs. AI).
- **Matrix Row Actions & License-Gated Targeted News**: Delete asset rows directly from the table (Free access) or click "View News" to redirect to asset-specific news (`/news?ticker=TICKER`, Licensed access).
- **Market News & Financial Feed**: Free global news stream with active filter badge ("Filtre actif : TICKER") and a "Voir toutes les news" reset button.
- **Digital Eco-Design & Token Savings**: System instructions enforce telegraphic, direct summaries to minimize token consumption and speed up execution.
- **Integrated License Security & Optional Login**: Optional Lemon Squeezy license key entry on an always-on startup login window with local offline caching.

---

## ⚠️ Important Note regarding Installation (Windows SmartScreen)

As an independent developer, Shadow-Zodiac is distributed without a paid commercial code-signing certificate. When you run the installer for the first time, Windows might display a blue window stating: **"Windows protected your PC"** (SmartScreen).

This is a standard warning for independent software. To install Shadow-Zodiac:

1. Click on **"More info"** in the blue SmartScreen window.
2. Click on the **"Run anyway"** button that appears.

*Your data privacy is our priority; all your analysis, local database (SQLite), and configurations remain entirely on your computer.*

---

## 🛠️ Getting Started & Installation

1. **Purchase & License Key**: Purchase your active license key at [https://shadow-zodiac.lemonsqueezy.com/checkout/buy/01bd75ff-2bb2-40dd-a9ea-e349b37cffa7](https://shadow-zodiac.lemonsqueezy.com/checkout/buy/01bd75ff-2bb2-40dd-a9ea-e349b37cffa7) (Optional for basic features, required for AI chat & dynamic asset management). 💡 Special Offer: Get 50% off for 3 months with code C1MDQ3NQ (Offer valid through end of 2026).
2. **eToro Credentials**: Obtain your eToro API Key and User Key from your eToro developer portal.
3. **Alpha Vantage API Key**: To enable financial market history and technical indicator analysis, claim your free API key at [https://www.alphavantage.co/support/#api-key](https://www.alphavantage.co/support/#api-key) and configure it in the **Settings** panel under *Market Data / Python Strategy*.
4. **Run the Installer**:
   Execute **`Shadow-Zodiac Setup 2.4.0.exe`**.
5. **Login & Setup**:
   - Open **Shadow-Zodiac** from your Desktop or Start Menu (the login screen **always** appears on startup).
   - Enter your **Lemon Squeezy License Key** in clear text (Optional).
   - Enter your **eToro API Credentials** and check *Remember credentials on this device*.
6. **Usage**: Access the dashboard to view live insights, browse market news, manage analysis settings, or open the side drawer AI Assistant to analyze and optimize your portfolio.

---

## 💡 Example AI Strategy Prompt (Configurable in Settings)

You can customize your AI Assistant's investment rules and analysis methodology in **Settings** under *AI Analysis Prompt*. Below is a recommended **Global Growth Strategy** prompt template:

```text
1. ROLE AND IDENTITY

You are the strategic expert managing a portfolio on eToro. Your sole objective is aggressive capital maximization (Growth). You are not seeking passive security, but consistent outperformance against the S&P 500 by exploiting global technology cycles and momentum, all while fully neutralizing "tax friction."


2. GOLDEN RULES & TAX CONSTRAINTS


- Zero Direct FR Stocks: Strict prohibition against buying French securities on eToro (25% withholding tax at source). Systematically redirect to the PEA (Plan d'Épargne en Actions) for these assets.
- Dividend Efficiency: Prioritize "Acc" (accumulating) assets or low-dividend / high-growth stocks to minimize tax withholdings (W-8BEN 15%).
- Zero Leverage: Purchases made strictly at X1 (unleveraged, no long CFDs).
- Single Currency: All analyses, amounts, and targets must be expressed in USD ($).
- Risk Management: Every buy recommendation must be accompanied by an invalidation level (price or fundamental metric) triggering a partial or full exit.


3. TARGET PORTFOLIO STRUCTURE (75% OFFENSIVE / 25% RESILIENT)


The overall allocation must lean toward this "Global Growth" balance:
- A. THE OFFENSIVE ENGINE (75%): Semiconductors, AI, Hyper-growth Software, Mega-cap Tech, Big Data, Global Momentum.
- B. THE RESILIENT SHIELD (25%): S&P 500 / Nasdaq Core ETFs, Mature Healthcare/Biotech, or high Free Cash Flow (FCF) stocks resilient to high interest rates.


4. MARKET INTELLIGENCE & ANALYSIS METHODOLOGY


Before any recommendation or rebalancing, you must conduct recent financial data research:
1. Live Technicals & Momentum: Verification of the current price, position relative to ATH/Dip, RSI (14), 50-day SMA, and 200-day SMA.
2. Retrospective Check (1 year): Is the asset overheating or in a healthy correction?
3. Strategic Projections:
   - 1 year: Price target (immediate catalysts: Earnings, rate cycles).
   - 3 years: Market share capture potential.
   - 5 years: "Multi-bagger" vision (ability to double or triple).
4. Contrarian Analysis (Bear Case): What is the main risk that could void the thesis?
5. Macro & Geopolitical Impact: Consideration of recent macroeconomic conditions and earnings reports.


5. MANDATORY RESPONSE FORMAT


For every interaction, structure your response exactly as follows:


1. 🟢 Tax Check & Eligibility (eToro vs PEA validation / W-8BEN treatment).
2. 📊 Live Technical & Momentum Analysis (Current price, RSI, SMAs, market situation).
3. 🎯 Investment Thesis & Projections (Why this asset? 1, 3, and 5-year targets).
4. ⚠️ Bear Case & Invalidation Threshold (Major risk + price level / exit trigger).
5. 💰 Precise Action Plan (Exact order to execute on eToro in USD: Buy / Sell / Rebalance to match the target allocation).
```

---

## 📜 Update History

- **v2.6.1 (2026-07-22)**:
  - **Prompt Template Refinement**: Removed personal name references from default AI system prompt configurations.
  - **Cross-Session Settings & API Key Persistence**: Added `/api/settings` REST endpoints and disk configuration synchronization (`data/settings.json`) to guarantee API keys (Google Gemini, Alpha Vantage, eToro credentials) persist across `npm start` and Electron sessions.
  - **Full Reflections History Pagination**: Implemented interactive pagination controls (Page X of Y, Prev/Next buttons, 5/10/20/50 items per page selector) on the Reflections History widget.
  - **Full English Translation Audit**: Standardized 100% of UI text, tooltips, buttons, toasts, and error notices to strict English.
  - **Dropdown Option Contrast Fix**: Styled HTML `<select>` and `<option>` elements with dark background and crisp white text for complete legibility across operating systems.
  - **Build Security Audit**: Verified zero hardcoded API keys, license tokens, or secrets exist in repository source code or dist bundles.
  - **AI Signal Generation & Top Trend Sync**: Guaranteed signal persistence into SQLite `trade_signals` for all newly added assets and fallback scenarios with immediate UI re-rendering.
- **v2.6.0 (2026-07-22)**:
  - **Asset Price Cell Rendering**: Ensured asset prices are continuously saved alongside AI reflections and rendered in matrix cells with automatic fallback price lookup.
  - **Instant AI Re-Analysis Button (`⚡`)**: Added a direct AI re-analysis action icon on each asset row in the Signal History pivot matrix to trigger an immediate fresh AI analysis on demand.
- **v2.5.1 (2026-07-22)**:
  - **Prompt Template Refinement**: Removed personal name references from default AI system prompt configurations.
  - **Cross-Session Settings Persistence**: Added `/api/settings` REST endpoints and disk configuration synchronization (`data/settings.json`) to prevent API key resets across `npm start` and Electron sessions.
  - **AI Reflections Table Pagination**: Added interactive pagination controls (Page X of Y, Prev/Next buttons, 5/10/20/50 items per page selector) on the Reflections History widget.
  - **Full English Translation Audit**: Standardized 100% of UI text, tooltips, buttons, toasts, and error notices to strict English.
  - **Dropdown Option Contrast Fix**: Styled HTML `<select>` and `<option>` elements with dark background and crisp white text for complete legibility across operating systems.
  - **Build Security Audit**: Verified zero hardcoded API keys, license tokens, or secrets exist in repository source code or dist bundles.
  - **AI Signal Generation & Top Trend Sync**: Guaranteed signal persistence into SQLite `trade_signals` for all newly added assets and fallback scenarios with immediate UI re-rendering.
- **v2.5.0 (2026-07-22)**:
  - **Full Article News Reader Modal**: Clicking any news card opens a rich modal view displaying the complete news article text, key takeaways, and source details.
  - **Navigation Menu Streamlining**: Removed redundant "Watchlist" / "Ma Liste de suivi" entries across sidebar navigation menus for a cleaner interface.
- **v2.4.0 (2026-07-22)**:
  - **Signal Matrix Row Actions**: Added "Delete" (accessible in Free mode) and "View News" (licensed feature) action controls on each asset row in the "IA Trading Signal History" pivot table.
  - **Targeted Ticker News Navigation**: Clicking "View News" redirects to the News view with query parameters (`?ticker=TICKER`), displaying asset-specific updates.
  - **Active Filter & Reset in News View**: Added "Filtre actif : TICKER" badge on the News page with a "Voir toutes les news" button to reset back to the global market feed.
  - **License Gating for Targeted News**: Non-licensed users clicking "View News" are presented with an explanatory toast notice.
- **v2.3.0 (2026-07-22)**:
  - **Always-On Startup Login Screen**: The login window is now presented on every application startup.
  - **Optional License Key Input**: Entering a Lemon Squeezy license key on login/settings is optional; basic dashboard features remain accessible in Free Mode.
  - **Dynamic Signal Matrix Asset Management**: Added controls to add or remove asset tickers in the Signal History pivot table, automatically triggering AI analysis for newly added tickers.
  - **Split-Screen Side Drawer AI Panel**: Replaced popups/modals with a side drawer panel that resizes the main dashboard layout side-by-side when opened.
  - **Paywall Feature Gating**: Restricted AI chat side panel access and dynamic asset management controls behind valid Lemon Squeezy license keys with user notification toasts in Free Mode.
- **v2.2.0 (2026-07-22)**:
  - **Automated Versioning System**: Integrated `package.json`, `version.json`, `/api/version`, and footer version badge.
  - **Lemon Squeezy License Control**: Startup license verification across Node server, PowerShell, Python agent, and SPA.
  - **Gemini Eco-Conception**: Injected strict `system_instruction` commanding telegraphic, zero-politeness, concise responses for token efficiency.
  - **Strict English Documentation**: Standardized `AGENTS.md`, `README.md`, `DOCUMENTATION.md`, and `SYSTEM_REQUIREMENTS.md` in English.
  - **Legal Notice & Investment Risk Disclaimer**: Added capital loss risk notice across documentation and login UI.
- **v2.1.0 (2026-03-29)**:
  - **Multi-Horizon Confidence Scoring**: Structured 1M / 1Y / 5Y ratings.
  - **Google Gemini Ticker Fallback**: Automatic failover to Gemini for unlisted or missing market tickers.
  - **Dynamic Table Column Filtering**: Self-populating dropdown filters across all dashboard tables.
- **v2.0.0 (2026-01-15)**:
  - Real-time eToro tracking, SQLite persistence server on port `3456`.
  - Multi-backend LLM integration (Gemini, LM Studio, AnythingLLM).
- **v1.0.0 (2025-07-14)**:
  - Initial commercial release. Full Lemon Squeezy integration, native Windows NSIS packaging, and 72-hour secure offline grace period.

Check for the latest updates and binaries at: `https://gitlab.com/d.laverda-group/d.laverda-project.git`

---

## 💬 Need Help?

If you have any questions, encounter a bug, or need assistance with your license key, please contact support via the email provided in your purchase confirmation.

**Happy Trading!**
