# 🧪 OpenLIS

Open-source Laboratory Information System for clinical specimen workflow management.

## Problem

Clinical labs suffer from:
- Multiple data entries across spreadsheets
- No workflow state management
- Paper-based processes that bottleneck during peak hours

## Solution

A web-based LIS with Maker-Checker workflow, ensuring no result is released without supervisor validation.

## Project Structure
```
src/
├── pages/        # UI screens (Login, Reception, Results, etc.)
├── components/   # Reusable UI elements
├── services/     # Business logic (authentication, validation)
└── database/     # Data models and queries
```

## Tech Stack

- Python 3.12
- Streamlit
- SQLite (local database)

## Status

🚧 Under Development