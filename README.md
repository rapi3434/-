# Silver Send Pro

This repository contains a structured starter for a Telegram-based Soroush multi-account control bot with:
- user panel
- owner panel
- account management
- bot automation workflows
- sender / forwarder / scanner foundations

## Stack
- Python 3.11+
- python-telegram-bot
- aiohttp
- SQLAlchemy / sqlite
- optional FastAPI for dashboard if needed

## Quick start

1. Create a virtual environment
2. Install dependencies
3. Set environment variables
4. Run the bot

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python main.py
```

## Project layout

- `main.py` – entry point
- `bot/` – bot logic
- `core/` – reusable utilities
- `config.py` – environment config

## Notes

This project is intentionally structured as a production-ready foundation and is designed to be extended for the full multi-account campaign engine described in your requirements.
