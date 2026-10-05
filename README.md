<h1 align="center">Hi, I'm Aleksei 👋</h1>
<h3 align="center">Python Automation Developer: Telegram bots, web scraping, AI data pipelines</h3>

<p align="center">
  <a href="https://www.upwork.com/freelancers/~01b79ffa28442df3f8"><img src="https://img.shields.io/badge/Hire%20me%20on-Upwork-14A800?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"></a>
  <a href="https://t.me/naurner"><img src="https://img.shields.io/badge/Telegram-@naurner-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
</p>

I build software that **replaces manual work**: the spreadsheet someone updates by hand, the website someone refreshes all day, the report someone assembles every week.

All the projects below run in production for real businesses, and each one comes with **tests, Docker and a one-command setup**. They're working tools, not tutorial code.

📍 Bishkek, Kyrgyzstan (UTC+6) · 🗣 English, Russian

---

## 🛠 What I can build for you

| | Service | Typical result |
|---|---|---|
| 🤖 | **Telegram bots & mini-CRMs** | Orders, roles, reminders, payments and reports in chat, so your team stops working out of spreadsheets |
| 🕷 | **Web scraping & monitoring** | Marketplace, classifieds and Telegram channel monitors with alerts when a price or listing matches |
| 🧠 | **AI data extraction** | Free-form text → clean structured data with LLMs (OpenAI, Claude, Groq, local Ollama) plus validation |
| ⛓ | **Blockchain monitoring** | On-chain event trackers, mint and whale alerts, trading signal bots |
| 🔗 | **API integrations & workflow automation** | Google Sheets, Microsoft 365, OpenSea, n8n, any REST API, connected end to end |
| 🖨 | **Document & print automation** | Photoshop/InDesign templates filled from Excel/CSV, so hundreds of personalized PDFs come out automatically |

---

## ⭐ Featured projects

### 🔭 [NFT Mint Radar](https://github.com/naurner/nft-mint-radar)
Real-time on-chain monitor that catches new NFT collections and live mints **before they hit Twitter**. It decodes EVM logs directly, filters noise with unique-wallet burst detection, enriches projects from OpenSea, scores them 0–100 and sends tiered Telegram alerts as **live-updating cards**. It can also auto-post to X with captions written by a local LLM.

`Python` `asyncio` `EVM JSON-RPC` `aiogram` `OpenSea API` `Ollama` `Turso` `Docker` · **686 tests**

### 📊 [PC Market Scanner](https://github.com/naurner/pc-market-scanner)
Scrapes a national classifieds site and Telegram groups. An **LLM turns messy listings into structured data** (model, condition, price) and every AI answer is checked against the post text. The result is a live price database: medians, deal detection ("cheapest active listing"), **Kaplan–Meier "how fast will it sell" estimates** and semantic search on embeddings.

`Python` `httpx` `BeautifulSoup` `Ollama` `Claude API` `Groq` `numpy` `aiogram` · **389 tests**

### 📋 [Studio CRM Bot](https://github.com/naurner/studio-crm-bot)
Telegram-first CRM for a photo studio. A 10-stage order pipeline moves between sales, photographers, retouchers, designers and print. It has a "✋ take this shoot" claim system, **Google Sheets as the database**, synced **Microsoft To Do** tasks, SLA deadlines and role-based menus.

`Python` `aiogram` `Google Sheets API` `Microsoft Graph` `MSAL` `SQLite` · **364 tests**

### 🚗 [Car Deal Monitor](https://github.com/naurner/car-deal-monitor)
Deal finder for car resellers. It scans two marketplaces by model generation and price, an LLM reads descriptions to skip salvage cars and fake prices, and the bot can even **message sellers and parse their replies**. It posts and bumps ads with Playwright, with a **remote browser login streamed to your phone** (noVNC + Cloudflare tunnel).

`Python` `Playwright` `SQLAlchemy` `APScheduler` `Ollama` `aiogram` `Docker`

### 📸 [Yearbook Autofill](https://github.com/naurner/yearbook-autofill)
Print-production automation for a graduation album studio. **Python drives Photoshop through generated ExtendScript** to fill templates from Excel (photos as clipping masks, text with original styles). It builds a personal PDF yearbook per student and renders watermarked previews without Photoshop. Students pick their photos in a Telegram bot.

`Python` `Photoshop JSX` `Pillow` `fontTools` `openpyxl` `aiogram` · **142 tests**

---

## 📁 More projects

| Project | What it is | Stack |
|---|---|---|
| [SportHub](https://github.com/naurner/sporthub) | Mobile app for local sports events with prepayment and automatic cost splitting | React Native · Expo · TypeScript |
| [Water Delivery CRM](https://github.com/naurner/Water_bot_CRM) | Telegram CRM that replaced Excel for a water delivery business | aiogram · PostgreSQL · APScheduler |
| [Earnings Tracker Bot](https://github.com/naurner/StatsBot) | Parses free-form income/expense messages and builds Excel reports | aiogram · SQLite · openpyxl |
| [Telegram Channel Parser](https://github.com/naurner/Work-stack-parser) | Async scraper for public Telegram channels, no bot token needed | aiohttp · BeautifulSoup |
| [Image Classifier](https://github.com/naurner/AntiCaptcha-Majestic-demo) | CNN that classifies small images into 4 classes | TensorFlow · Keras |

---

## 🧰 Tech stack

**Core:** ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![asyncio](https://img.shields.io/badge/asyncio-3776AB?logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)

**Bots & integrations:** ![aiogram](https://img.shields.io/badge/aiogram-26A5E4?logo=telegram&logoColor=white) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?logo=googlesheets&logoColor=white) ![Microsoft Graph](https://img.shields.io/badge/Microsoft%20Graph-0078D4?logo=microsoft&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)

**Scraping & automation:** ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white) ![httpx](https://img.shields.io/badge/httpx%20%2F%20aiohttp-555555) ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-555555) ![Photoshop](https://img.shields.io/badge/Photoshop%20JSX-31A8FF?logo=adobephotoshop&logoColor=white) ![InDesign](https://img.shields.io/badge/InDesign-FF3366?logo=adobeindesign&logoColor=white)

**AI:** ![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white) ![Claude](https://img.shields.io/badge/Claude%20API-D97757?logo=anthropic&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)

**Data & infra:** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00) ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)

---

## 🤝 How I work

1. **You describe the manual process.** I reply with a plain-language plan, a clear scope and an honest estimate.
2. **You get working code in a Git repo** with a README, setup steps and tests, not a black box.
3. **I test the ugly cases**: empty fields, broken sources, rate limits, the site changing its layout.
4. **Easy to run:** Docker, one-click scripts and in-bot "update" buttons, so you never need to SSH into anything.

<p align="center">
  <b>Have a task you repeat every week? Send me the steps and I'll tell you what can be automated.</b><br><br>
  <a href="https://www.upwork.com/freelancers/~01b79ffa28442df3f8"><img src="https://img.shields.io/badge/Start%20a%20project%20on-Upwork-14A800?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"></a>
</p>
