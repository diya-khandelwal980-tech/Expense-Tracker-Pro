# Expense Tracker Pro

A browser-based expense tracker built with Python, Flask, SQLite, HTML, CSS, and Chart.js.

## Requirements
- Python 3.10 or newer
- Internet connection for Google Fonts and Chart.js CDN (the core app works without fonts, but charts require Chart.js)

## Run in VS Code

1. Open this folder in VS Code.
2. Open Terminal > New Terminal.
3. (Recommended) Create a virtual environment:
   - Windows: `py -m venv .venv`
   - PowerShell: `.venv\Scripts\Activate.ps1`
4. Install dependencies: `python -m pip install -r requirements.txt`
5. Run: `python app.py`
6. Open `http://127.0.0.1:5000` in Chrome or Edge.

The `expenses.db` SQLite database is created automatically in the current working directory.

## Features
- Add, edit and delete expenses
- Monthly spending summary and budget progress
- Category doughnut chart and monthly bar chart
- Search by title/notes; filter by category and date range
- Export all transactions to CSV
- Persistent SQLite storage

## Notes
This is a local educational project, not a production financial service. For real deployment, set a private `app.secret_key`, disable debug mode, add authentication if needed, and use appropriate security protections.
