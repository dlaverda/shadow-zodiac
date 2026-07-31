# 🪐 Shadow-Zodiac — eToro Financial Intelligence & AI Sentiment Sentinel

[![Version](https://img.shields.io/badge/version-3.3.0-blue.svg)](https://gitlab.com/d.laverda-group/d.laverda-project)
[![License: Lemon Squeezy](https://img.shields.io/badge/License-Lemon%20Squeezy-green.svg)](https://www.lemonsqueezy.com/)
[![Build: Windows Desktop](https://img.shields.io/badge/Platform-Windows%20Desktop-informational.svg)](#)
[![Language: English](https://img.shields.io/badge/Language-English-brightgreen.svg)](#)

> **Transform your eToro investment experience with 100% local, privacy-first AI market sentiment and real-time portfolio analytics.**

**Shadow-Zodiac** is the ultimate desktop command center for modern stock, crypto, and ETF investors. It bridges live eToro portfolio tracking with advanced Large Language Model (LLM) intelligence—analyzing technical momentum, fundamental reports, news streams, and macro risks to deliver actionable investment signals without compromising your financial data privacy.

---

## ⚠️ Important Legal Notice & Capital Loss Risk Warning

> ### 🛑 INVESTMENT RISK WARNING
>
> Investing in financial markets (stocks, bonds, funds, ETFs, derivatives, or any other financial instruments) involves significant risks.
>
> 1. **Risk of Capital Loss**: Past performance is no guarantee of future results and does not constitute a performance yield guarantee. The value of investments and the income derived from them can fluctuate up or down. You may not recover the amount initially invested. In certain specific cases (notably when utilizing leverage or deferred settlement services), losses may even exceed your initial capital deposit.
> 2. **No Financial Advice**: The information, analyses, charts, or data provided to you are strictly for indicative decision-support purposes and do not in any way constitute investment advice, a sales offer, or a solicitation to buy or sell financial instruments.
> 3. **Profile Suitability**: Before making any investment decision, it is the sole responsibility of the investor to ensure that chosen assets correspond to their financial situation, level of knowledge and experience, investment objectives, and placement time horizon. If you do not understand the risks associated with financial instruments, consulting an independent financial advisor is strongly recommended.
> 4. **No Automated eToro Order Execution**: Shadow Zodiac **does NOT execute buy or sell orders** on eToro or any third-party broker. The application has no automated order submission or trading execution capabilities. All final trading choices remain under the exclusive control of the investor.

---

## 🌟 Why Investors Choose Shadow-Zodiac

- 🔒 **100% Local-First & Privacy-First**: Unlike web-based trackers, Shadow-Zodiac runs entirely on your local machine. Your eToro API keys, portfolio values, trade signals, and AI reflections are stored 100% locally in SQLite (`database.sqlite`)—zero cloud telemetry, zero prying eyes.
- 🤖 **Multi-Engine AI Sentiment Analysis**: Native support for **Google Gemini (`@google/genai`)**, **LM Studio (100% offline local LLM)**, and **AnythingLLM**. Switch between cloud and local inference in a single click.
- 📊 **Multi-Horizon Decision Matrix**: Real-time `BUY`, `SELL`, and `NEUTRAL` signals paired with structured **1-Month, 1-Year, and 5-Year confidence ratings** (1-10 scale).
- 🎯 **100% Configurable AI Strategy Prompt**: Fully customizable system prompt in **Settings** (`"AI Analysis Prompt"`). Shipped with a pre-configured, high-performance "Global Growth & Tax Friction Neutralization" template.
- ⚡ **Digital Eco-Design & Fast Execution**: System prompts enforce a direct, telegraphic style to minimize token consumption, reduce latency, and lower environmental footprint.
- 🌐 **Offline-Ready Security**: Trade with confidence even when your connection drops, backed by a 24-hour offline cache grace period.

---

## ⚡ Free vs. Premium Licensed Comparison

Shadow-Zodiac operates on a transparent **Freemium** model. Basic portfolio tracking and market news are free forever, while advanced AI assistant features and dynamic asset management are unlocked with a Lemon Squeezy license key:

| Feature | 🆓 Free Tier | 🔑 Premium Licensed Tier |
|---|:---:|:---:|
| **Real-Time eToro Portfolio & Cash Tracking** | ✅ Included | ✅ Included |
| **Live World Indices & Market Quotes** | ✅ Included | ✅ Included |
| **Global Market News & Full Article Reader** | ✅ Included | ✅ Included |
| **AI Trade Signals History Matrix (Read-Only)** | ✅ Included | ✅ Included |
| **Dynamic Asset Ticker Management (+Add / Delete)** | 🔒 Restricted | ✅ **Unlocked** |
| **Targeted Asset News Filter (`?ticker=XYZ`)** | 🔒 Restricted | ✅ **Unlocked** |
| **Side Drawer Split-Screen AI Assistant Panel** | 🔒 Restricted | ✅ **Unlocked** |
| **Instant "Analyze and Optimize My Portfolio" Action** | 🔒 Restricted | ✅ **Unlocked** |
| **Customizable AI Strategy Prompt in Settings** | 🔒 Restricted | ✅ **Unlocked** |

---

## 🚀 Key Features Breakdown

- 📈 **Real-Time eToro Tracking**: Live tracking of account equity, available cash balance, allocated funds, open positions, daily/overall P&L, and sparkline trend charts.
- 🤖 **AI-Powered Sentiment Sentinel**: Multi-engine AI support (Google Gemini, LM Studio, AnythingLLM) generating technical and fundamental investment signals (`BUY` / `SELL` / `NEUTRAL`).
- 📐 **Multi-Horizon Confidence Scoring**: Structured 1-to-10 confidence ratings provided across 1-Month, 1-Year, and 5-Year time horizons for each position.
- 📐 **Side Drawer Split-Screen AI Assistant**: Interactive side drawer chat panel that resizes the main dashboard layout side-by-side when opened, featuring a thumbtack button and an instant **"Analyze and Optimize My Portfolio"** action.
- 📊 **AI Trading Signals History Pivot Matrix**: Full-width matrix table displaying assets in rows and historical dates in columns with color-coded buy/sell price cells and source badges (Market vs. AI).
- 📰 **Market News & Full Article Modal Reader**: Free global news stream with full article reader modal, active ticker filter badge, and "View all news" reset button.
- 💡 **Configurable Strategy Rules**: Customize technical signal calculation thresholds (`buyThresholdPct` / `sellThresholdPct`) and AI system prompts directly in Settings.

---

## ⚠️ Important Note Regarding Installation (Windows SmartScreen)

As an independent developer, Shadow-Zodiac is distributed without a paid commercial code-signing certificate. When you run the installer for the first time, Windows might display a blue window stating: **"Windows protected your PC"** (SmartScreen).

This is a standard warning for independent software. To install Shadow-Zodiac:

1. Click on **"More info"** in the blue SmartScreen window.
2. Click on the **"Run anyway"** button that appears.

*Your data privacy is our priority; all your analysis, local database (SQLite), and configurations remain entirely on your computer.*

---

## 🛠️ Getting Started & Installation Guide

1. 🔑 **Purchase & License Key**: Purchase your active license key at [https://shadow-zodiac.lemonsqueezy.com/checkout/buy/01bd75ff-2bb2-40dd-a9ea-e349b37cffa7](https://shadow-zodiac.lemonsqueezy.com/checkout/buy/01bd75ff-2bb2-40dd-a9ea-e349b37cffa7) (Optional for basic features, required for AI chat & dynamic asset management).  
   💡 **Special Offer**: Get **50% off for 3 months** with code **`C1MDQ3NQ`** *(Offer valid through end of 2026)*.
2. 🔑 **eToro Credentials**: Obtain your eToro API Key and User Key from your eToro developer portal.
3. 📈 **Alpha Vantage API Key**: To enable financial market history and technical indicator analysis, claim your free API key at [https://www.alphavantage.co/support/#api-key](https://www.alphavantage.co/support/#api-key) and configure it in the **Settings** panel under *Market Data / Python Strategy*.
4. 💻 **Run the Installer**:
   Execute **`Shadow-Zodiac Setup 2.7.0.exe`** (located in `dist/` or provided in release downloads).
5. 🔐 **Login & Setup**:
   - Open **Shadow-Zodiac** from your Desktop or Start Menu (the login screen **always** appears on startup).
   - Enter your **Lemon Squeezy License Key** in clear text (Optional).
   - Enter your **eToro API Credentials** and check *Remember credentials on this device*.
6. 🚀 **Usage**: Access the dashboard to view live insights, browse market news, manage analysis settings, or open the side drawer AI Assistant to analyze and optimize your portfolio.

---

## 💡 Configurable AI Strategy Prompt Template

You can customize your AI Assistant's investment rules and analysis methodology in **Settings** under *AI Analysis Prompt*. Below is the default **Global Growth Strategy** prompt template:

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

- **v3.3.0 (2026-07-31)**:
  - **Skeleton Screen Placeholders**: Integrated CSS linear gradient shimmer animations (`skeleton-shimmer`) matching the dark theme layout for dashboard stat cards, portfolio tables, and widget containers (`js/views/dashboard.js` & `styles/main.css`).
  - **Dynamic Top Progress Bar**: Added a sleek, fixed top progress indicator (`#top-progress-bar`) displaying real-time loading feedback ("Fetching eToro portfolio...", "Calculating 30D metrics & AI signals...").
  - **Graceful Error Fallback**: Added an inline error card with a 1-click **Retry Loading Dashboard** button in case of network timeouts or fetching errors.
- **v3.2.1 (2026-07-31)**:
  - **Portfolio History Analytics Sub-View Tabs**: Integrated 3 dedicated view tabs in `Portfolio History Analytics` (`js/views/portfolio-history.js`) for displaying:
    1) `📊 Portfolio Equity & Composition` (Stacked Area Chart & Snapshots Table)
    2) `📜 Closed Positions History` (Paginated, sortable table of all 853 imported closed trades with PnL, leverage, and fees)
    3) `💳 Account Activity Log` (Paginated, filterable table of all 2,409 imported transactions, deposits, withdrawals, and balances)
  - **Reflections Deduplication Key Fix**: Preserved exact timestamp strings in `readReflections()` (`server/storage.js`) instead of truncating dates to day/minute levels, eliminating reflection count variations.
- **v3.2.0 (2026-07-31)**:
  - **eToro Account Statement Importer (.xlsx)**: Integrated a multi-sheet Excel file importer in Settings (`js/views/settings.js`) supporting drag-and-drop and file selection for eToro statements.
  - **SheetJS (`xlsx`) Multi-Language Parsing Engine**: Auto-detects French (`Positions fermées`, `Activité du compte`) and English (`Closed Positions`, `Account Activity`) sheet names and column headers.
  - **Deduplicated Closed Positions & Account Activity Database**: Created `etoro_closed_positions` and `etoro_account_activity` SQLite/MySQL tables with strict unique constraint deduplication (`position_id`, `activity_date`).
  - **Automatic History Re-Calculation**: Auto-triggers portfolio history backfill and metrics update upon completion of statement imports.
- **v3.1.0 (2026-07-31)**:
  - **Pre-Aggregated Market & Financial Metrics**: Replaced raw time-series row dumping in `Script python/ai_agent.py` with SQL pre-aggregation (`30D min/max/avg/return`) resulting in up to 80% reduction in prompt token consumption.
  - **Top-K Targeted RAG Search**: Filtered historical reflections and news queries to Top-K = 3 to 5 entries max, eliminating context clutter.
  - **Structured Gemini Response Schema**: Passed `responseMimeType: "application/json"` and strict `responseSchema` for scoring tasks, eliminating JSON parsing errors and conversational token overhead.
  - **Strict Output Token Limits**: Configured `maxOutputTokens: 1024` and temperature `0.2` across Python and JS Gemini API adapters.
- **v3.0.3 (2026-07-31)**:
  - **Fixed Settings Route ReferenceError**: Fixed `saveBtn is not defined` error in `js/views/settings.js` by explicitly declaring `const saveBtn = container.querySelector('#s-save')`.
  - **100% Automatic MySQL Initialization & Sync**: Automated MySQL database creation (`CREATE DATABASE IF NOT EXISTS shadow_zodiac`), table creation, and full history sync on server startup without requiring manual user credentials entry.
  - **Simplified Settings UI**: Replaced manual MySQL input fields in Settings with a clean automated status panel and 1-click **Re-Sync MySQL History Now** button.
- **v3.0.2 (2026-07-31)**:
  - **Bidirectional MySQL History Sync**: Created complete MySQL schema migration and synchronization engine (`POST /api/mysql/sync` in `server/storage.js`) supporting `reflections`, `portfolio_history`, `ai_discussions`, and `trade_signals`.
  - **Automatic History Recovery**: Automatically restores and syncs all local reflections (including July 27, 28, 29, 30, and 31 records) from `reflections.json` and SQLite into MySQL upon connection or manual sync trigger.
  - **One-Click Sync UI Button**: Added **Sync All History to MySQL** button in Settings View (`js/views/settings.js`) with live feedback on synchronized record counts.
- **v3.0.1 (2026-07-30)**:
  - **Portable ZIP Build Target**: Configured `electron-builder` (`package.json`) to output both a standard NSIS executable setup installer (`Shadow-Zodiac Setup 3.0.1.exe`) and a standalone portable zip archive (`Shadow-Zodiac-3.0.1-win.zip` / `Shadow-Zodiac Setup 3.0.1.zip`) in `/dist`.
  - **Standalone Execution**: Portable zip package allows users to extract and run the desktop application directly without system installation or administrator privileges.
- **v3.0.0 (2026-07-30)**:
  - **Rich Markdown Response Rendering**: Integrated `marked` engine (`marked.parse`) for complete Github Flavored Markdown (GFM) rendering of AI chat messages, formatted headers, bold/italic highlights, bullet/numbered lists, blockquotes, and code blocks.
  - **Click-and-Drag Resizable AI Chat Drawer**: Added a vertical drag handle (`#ai-resize-handle`) on the left border of the AI Assistant drawer.
  - **Interactive Mouse Drag Logic**: Smooth 60fps panel width adjustment with mouse drag event handlers (`mousedown`, `mousemove`, `mouseup`).
  - **Layout Bounds & Constraints**: Enforced strict bounds (`minWidth: 320px`, `maxWidth: 80vw`) with `col-resize` cursors and text selection disabling during drag operations.
  - **Persistent Layout Preference**: Automatically saves user's custom drawer width preference to `localStorage.getItem('shadow_ai_panel_width')`.
- **v2.9.0 (2026-07-30)**:
  - **Automatic MySQL AI Chat Persistence**: Implemented complete user and AI chat interaction storage in MySQL database table `ai_discussions`.
  - **Non-Blocking Asynchronous Hooks**: User prompts and AI responses are saved asynchronously (`POST /api/chat/messages`) without delaying UI chat rendering.
  - **Resilient Dual Storage Architecture**: Tries MySQL connection pool (`mysql2/promise`) first; if unconfigured or disconnected, gracefully falls back to local SQLite `ai_discussions` table and logs warnings with `[Storage]` prefix.
  - **MySQL Configuration Settings Panel**: Added dedicated **MySQL AI Chat Persistence** configuration card in Settings View (`js/views/settings.js`) with an interactive **Test Connection** button (`POST /api/mysql/test`).
- **v2.8.0 (2026-07-30)**:
  - **Portfolio History View (`#portfolio-history`)**: Introduced a dedicated analytics page for historical eToro portfolio tracking (`js/views/portfolio-history.js`).
  - **Interactive Stacked Area Chart**: Rendered using Chart.js with top boundary line for total equity and stacked semi-transparent color fills for individual asset allocations.
  - **Dynamic Timeframe Selector**: Supports instant switching and aggregation between `Daily` (Jour), `Monthly` (Mois), and `Yearly` (Année) views.
  - **Historical Data Table with Pagination**: Positioned below the chart with sortable columns (Date, Total Equity, Available Cash, Asset Breakdown pills, and Period Change %) and interactive pagination controls (5, 10, 20, 50 rows per page).
  - **SQLite Asset Breakdown Column**: Enhanced `portfolio_history` schema with `asset_breakdown TEXT` and automatic snapshot creation on portfolio refreshes.
- **v2.7.1 (2026-07-22)**:
  - **European Ticker Exchange Suffix Fallback**: Implemented automatic retry mechanism for European stocks without explicit suffixes (e.g. `RNO` -> `RNO.PA`, `.DE`, `.L`, `.MI`, `.AS`), automatically storing history under both base and resolved exchange symbols.
  - **LLM Pipeline Guard & Price Validation**: Added data validation before issuing LLM API calls, preventing wasteful API token consumption when price history is absent.
  - **SQLite Warning Elimination**: Resolved `ensureReflectionsTable is not defined` ReferenceError by calling `ensureDatabaseTables()` across storage modules.
- **v2.7.0 (2026-07-22)**:
  - **SQL News & Portfolio History Tables**: Created `news_history` and `portfolio_history` SQLite tables with REST API persistence endpoints (`/api/news`, `/api/portfolio/history`).
  - **Configurable Buy/Sell Signal Thresholds**: Added signal calculation explanation and threshold customization inputs (`buyThresholdPct`, `sellThresholdPct`) in Settings.
  - **Clickable GitHub Releases Link**: Integrated direct update link to `https://github.com/dlaverda/shadow-zodiac/releases` on footer version badge, README, and update notifications.
  - **Full RAG Database AI Context Pipeline**: Enhanced `ai_agent.py` to query and synthesize `market_history`, `trade_signals`, `reflections`, `news_history`, and `top_trends` from SQLite into AI prompts.
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

Check for the latest updates and binaries at: `https://gitlab.com/d.laverda-group/d.laverda-project.git` or `https://github.com/dlaverda/shadow-zodiac/releases`

---

## 💬 Need Help?

If you have any questions, encounter a bug, or need assistance with your license key, please contact support via the email provided in your purchase confirmation.

**Happy Trading!**
