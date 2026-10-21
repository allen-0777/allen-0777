# Hi, I'm Allen Chan 👋

**Data Engineer** — I build data pipelines that ingest, clean, and serve financial market data, from scheduled ETL jobs to Postgres to the API and dashboard on top.

資料工程師，專注於金融市場資料的擷取、清理、入庫與服務化。**Open to remote roles.**

- 🔭 Currently: running a production daily ETL for Taiwan stock market capital flows ([StockCapitalFlow](https://github.com/allen-0777/StockCapitalFlow))
- 💼 Experience: `<工作經歷：公司 / 職稱 / 年資>`
- 🌏 Based in Taiwan (UTC+8) · Mandarin / English `<語言程度>`

## 🛠 Tech stack

**Languages & data:** Python · SQL · pandas · NumPy  
**Storage:** PostgreSQL (Supabase) · SQLite · SQLAlchemy  
**Pipelines & ops:** Apache Airflow · dbt · pandera (data quality) · Docker Compose · GitHub Actions (scheduled ETL, CI) · pytest · Render · Vercel · Google App Engine  
**APIs & apps:** FastAPI · Flask · Streamlit · aiohttp / httpx (async ingestion) · React + Vite  
**Data sources I've integrated:** TWSE OpenAPI · TAIFEX · FinMind · yfinance · SEC EDGAR · Google Sheets API

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)

## 📌 Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**StockCapitalFlow**](https://github.com/allen-0777/StockCapitalFlow) · [live](https://stock-capital-flow.vercel.app) | Production daily ETL of TWSE / TAIFEX / FinMind institutional-flow data into Postgres, with retry/rate-limited ingestion, batched upserts, freshness checks, and a FastAPI + React dashboard | Python, FastAPI, Postgres 17, GitHub Actions, pytest |
| [**tw-market-data-pipeline**](https://github.com/allen-0777/tw-market-data-pipeline) | Airflow-orchestrated daily batch pipeline for TWSE / TAIFEX data: raw lake landing, pandera quality gates, idempotent Postgres COPY loads, dbt staging → marts with 71 tests, one-command Docker Compose | Airflow, dbt, Postgres 17, pandera, Docker, GitHub Actions |
| [**stock**](https://github.com/allen-0777/stock) | Streamlit dashboard for Taiwan after-market data: institutional buy/sell rankings, futures OI, FX, and a moving-average backtester; async fetching + Google Sheets export | Python, pandas, Streamlit, httpx |
| [**self_healing_agent**](https://github.com/allen-0777/self_healing_agent) | Agent framework that reflects on tool failures, retries with an adjusted strategy, and persists what worked; sandboxed execution and JSON run logs | Python, Claude API, pytest |
| [**nofomo**](https://github.com/allen-0777/nofomo) | Trade journal that records trades via natural language and analyzes FOMO vs. planned trades across multi-market, multi-currency portfolios | Python, Flask, SQLAlchemy, SQLite |
| [**ai-technical-analyzer**](https://github.com/allen-0777/ai-technical-analyzer) | OHLCV ingestion + support/resistance detection with an LLM commentary layer, served over FastAPI to a React chart UI | Python, FastAPI, pandas, SciPy, React |
| [**Cladexter**](https://github.com/allen-0777/Cladexter) | Autonomous financial research assistant that plans steps, pulls SEC EDGAR filings and web news, and writes a structured report | JavaScript, Claude API, SEC EDGAR |

## 📫 Contact

- Email: `<聯絡信箱>`
- LinkedIn: [allen-chan-959591226](https://www.linkedin.com/in/allen-chan-959591226)
- Résumé: `<履歷連結>`
