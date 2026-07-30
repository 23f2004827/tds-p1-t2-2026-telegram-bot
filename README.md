# TDS P1 Telegram Bot — Data Analyst LLM Agent

An autonomous LLM Data Analyst agent integrated as a Telegram bot.

## Features
- Handles single-turn and multi-turn data analysis questions.
- Answers MOSPI dataset queries, numerical forecasts, statistics, and calculations.
- Guarantees strict JSON output format matching expected answer schemas.
- Generates public `log_url` for offline evaluation.

## Setup & Run
```bash
pip install -r requirements.txt
TELEGRAM_BOT_TOKEN="your_bot_token" python3 bot.py
```
