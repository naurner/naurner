<h1 align="center">Hi, I'm Aleksei 👋</h1>
<h3 align="center">Python developer: Telegram bots, scrapers, automation and LLM data pipelines</h3>

<p align="center">
  <a href="https://t.me/UkanisAleksei"><img src="https://img.shields.io/badge/Telegram-@UkanisAleksei-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://www.linkedin.com/in/ukanis-aleksei-4b0706259/"><img src="https://img.shields.io/badge/LinkedIn-Aleksei%20Ukanis-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.upwork.com/freelancers/~01b79ffa28442df3f8"><img src="https://img.shields.io/badge/Upwork-Ukanis%20A.-14A800?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"></a>
</p>

I build tools that replace manual work: the spreadsheet someone fills in by hand, the site someone refreshes all day, the report someone counts every week. I've been writing Python since early 2025: a paid bot for a client, internal tools my team uses every day, and my own products. The bigger projects come with tests, Docker and a one-command setup.

Studying Computer Science at IT Park University. Looking for a remote junior Python / backend role.

📍 Bishkek, Kyrgyzstan (UTC+6) · 🗣 Russian, English

---

## ⭐ Featured projects

### 🔭 [NFT Mint Radar](https://github.com/naurner/nft-mint-radar)
Real-time on-chain monitor that catches new NFT collections and live mints. It reads EVM logs directly over JSON-RPC, filters noise with unique-wallet burst detection, enriches projects from OpenSea, scores them 0–100 and sends tiered Telegram alerts as live-updating cards. Optional auto-posting to X with captions from a local LLM.

`Python` `asyncio` `httpx` `EVM JSON-RPC` `aiogram` `OpenSea API` `Ollama` `Turso` `Docker` · **686 tests**

### 📊 [PC Market Scanner](https://github.com/naurner/pc-market-scanner)
Scrapes a national classifieds site and Telegram groups. An LLM turns messy listings into structured data (model, condition, price), and every answer is checked against the post text. The result is a live price database: medians, deal detection, Kaplan–Meier "how fast will it sell" estimates and semantic search on embeddings.

`Python` `httpx` `BeautifulSoup` `Ollama` `Claude API` `Groq` `numpy` `aiogram` · **389 tests**

### 📋 [Studio CRM Bot](https://github.com/naurner/studio-crm-bot)
Telegram CRM used by our graduation album team. A 10-stage order pipeline moves between sales, photographers, retouchers, designers and print, with a "take this shoot" claim system, Google Sheets as the database, Microsoft To Do sync, deadlines and role-based menus.

`Python` `aiogram` `Google Sheets API` `Microsoft Graph` `MSAL` `SQLite` · **364 tests**

### 📸 [Yearbook Autofill](https://github.com/naurner/yearbook-autofill)
Print-production automation for the same team. Python drives Photoshop through generated ExtendScript to fill album templates from Excel (photos as clipping masks, text with original styles), builds a personal PDF per student and renders watermarked previews without Photoshop. Students pick their photos in a Telegram bot.

`Python` `Photoshop JSX` `Pillow` `fontTools` `openpyxl` `aiogram` · **142 tests**

### 🚗 [Car Deal Monitor](https://github.com/naurner/car-deal-monitor)
Deal finder for buying cars to resell. Scans two marketplaces by model generation and price, an LLM reads descriptions to skip salvage cars and fake prices, and the bot can message sellers and parse their replies. Posts and bumps ads with Playwright, with a remote browser login streamed to a phone (noVNC + Cloudflare Tunnel).

`Python` `Playwright` `SQLAlchemy` `APScheduler` `httpx` `Ollama` `aiogram` `Docker`

---

## 📁 More projects

| Project | What it is | Stack |
|---|---|---|
| [StatsBot](https://github.com/naurner/StatsBot) | Client project: parses chat operators' shift reports, keeps earnings and payouts in Excel | python-telegram-bot · pandas · openpyxl |
| [Water Delivery Bot](https://github.com/naurner/Water_bot_CRM) | Ordering bot for a water delivery service: time slots, rescheduling, reminders | python-telegram-bot · JobQueue · openpyxl |
| [Telegram Channel Parser](https://github.com/naurner/Work-stack-parser) | Exports public Telegram channels to Excel with keyword filters, no API keys | aiohttp · BeautifulSoup |
| [SportHub](https://github.com/naurner/sporthub) | UI prototype of a mobile app for organising amateur sports games | React Native · Expo · TypeScript |

---

## 🧰 Tech stack

**Core:** ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![asyncio](https://img.shields.io/badge/asyncio-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-555555) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)

**Bots & integrations:** ![aiogram](https://img.shields.io/badge/aiogram-26A5E4?logo=telegram&logoColor=white) ![python-telegram-bot](https://img.shields.io/badge/python--telegram--bot-26A5E4?logo=telegram&logoColor=white) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?logo=googlesheets&logoColor=white) ![Microsoft Graph](https://img.shields.io/badge/Microsoft%20Graph-0078D4?logo=microsoft&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)

**Scraping & automation:** ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white) ![httpx](https://img.shields.io/badge/httpx%20%2F%20aiohttp-555555) ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-555555) ![Photoshop](https://img.shields.io/badge/Photoshop%20JSX-31A8FF?logo=adobephotoshop&logoColor=white)

**AI:** ![Claude](https://img.shields.io/badge/Claude%20API-D97757?logo=anthropic&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)

**Data & infra:** ![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00) ![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

**Learning now:** Django, Django REST Framework, PostgreSQL

---

<p align="center">
  <b>Hiring or have a task you repeat every week? Write to me on <a href="https://t.me/UkanisAleksei">Telegram</a> or <a href="mailto:alekseiukanis@gmail.com">email</a>.</b>
</p>
