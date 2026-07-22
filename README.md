# 🪐 Shadow-Zodiac — Premium Dashboard & AI Sentiment Sentinel

[![Version](https://img.shields.io/badge/version-2.2.0-blue.svg)](https://gitlab.com/d.laverda-group/d.laverda-project)
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
- **Pinnable & Retractable AI Assistant Panel**: Interactive chat side panel with a pushpin button to lock alongside your dashboard, featuring an instant **"Analyser et optimiser mon portefeuille"** action.
- **AI Trading Signals History Pivot Matrix**: Full-width matrix table displaying assets in rows and historical dates in columns with color-coded buy/sell price cells and source badges (Market vs. AI).
- **Digital Eco-Design & Token Savings**: System instructions enforce telegraphic, direct summaries to minimize token consumption and speed up execution.
- **Integrated License Security**: Instant Lemon Squeezy license key verification at launch with local offline caching.

---

## ⚠️ Important Note regarding Installation (Windows SmartScreen)

As an independent developer, Shadow-Zodiac is distributed without a paid commercial code-signing certificate. When you run the installer for the first time, Windows might display a blue window stating: **"Windows protected your PC"** (SmartScreen).

This is a standard warning for independent software. To install Shadow-Zodiac:

1. Click on **"More info"** in the blue SmartScreen window.
2. Click on the **"Run anyway"** button that appears.

*Your data privacy is our priority; all your analysis, local database (SQLite), and configurations remain entirely on your computer.*

---

## 🛠️ Getting Started & Installation

1. **Purchase & License Key**: Get your active **Lemon Squeezy License Key**.
2. **eToro Credentials**: Obtain your eToro API Key and User Key from your eToro developer portal.
3. **Alpha Vantage API Key**: To enable financial market history and technical indicator analysis, claim your free API key at [https://www.alphavantage.co/support/#api-key](https://www.alphavantage.co/support/#api-key) and configure it in the **Settings** panel under *Market Data / Python Strategy*.
4. **Run the Installer**:
   Execute **`Shadow-Zodiac Setup 2.2.0.exe`** (located in `C:\Users\XXX\Documents\shadow-zodiac\dist\` or provided in distribution release).
5. **Login & Setup**:
   - Open **Shadow-Zodiac** from your Desktop or Start Menu.
   - Enter your **Lemon Squeezy License Key** (displayed in clear text).
   - Enter your **eToro API Credentials** and check *Remember credentials on this device*.
6. **Usage**: Access the dashboard to view live insights, manage analysis settings, or ask the pinned AI Assistant to analyze and optimize your portfolio.

---

## 📜 Update History

- **v2.2.0 (2026-07-22)**:
  - Added Pinnable & Retractable AI Chat Panel with pushpin button.
  - Added instant **"Analyser et optimiser mon portefeuille"** action button.
  - Redesigned AI Trading Signals History into a full-width Pivot Matrix (Assets × Dates).
  - Native SQLite data persistence with full automated table initialization.
  - Plain-text Lemon Squeezy license input on login window with *Remember Credentials* option.
- **v2.1.0 (2026-03-29)**:
  - Multi-Horizon Confidence Scoring (1M / 1Y / 5Y).
  - Fallback to Google Gemini for unlisted assets.
  - Self-populating dropdown column filters across all dashboard tables.
- **v2.0.0 (2026-01-15)**:
  - Real-time eToro tracking, SQLite persistence server on port `3456`.
  - Multi-backend LLM integration (Gemini, LM Studio, AnythingLLM).
- **v1.0.0 (2025-07-14)**:
  - Initial commercial release. Full Lemon Squeezy integration, native Windows NSIS packaging, and offline grace period.

Check for the latest updates and binaries at: `https://gitlab.com/d.laverda-group/d.laverda-project.git`

---

## 💬 Need Help?

If you have any questions, encounter a bug, or need assistance with your license key, please contact support via the email provided in your purchase confirmation.

**Happy Trading!**
