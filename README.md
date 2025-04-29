# lottery-data-pipeline
# Multi-Lottery Data Pipeline and Dashboard

## Overview
This project automates the collection, storage, analysis, and visualization of lottery draw data from:
- Florida Lotto (USA)
- Cash4Life (USA)
- Mega-Sena (Brazil)

It scrapes official lottery results, saves them into a local SQLite database, analyzes hot and cold numbers, checks user tickets, and visualizes insights using Tableau.

---

## Features
- Automated web scraping of official lottery results
- Structured storage in SQLite database
- Hot/Cold number analysis across 100+ past draws
- Ticket checker for multiple games
- Motivation system for strategic play
- Tableau dashboard integration for visual analysis
- Fully automated system — no manual updating required

---

## Technologies Used
- Python (requests, BeautifulSoup, sqlite3, pandas)
- SQLite (database storage)
- Tableau Public (data visualization)
- GitHub (version control)

---

## Folder Structure
```plaintext
lottery-data-pipeline/
├── src/
│   ├── scraper.py
│   ├── checker.py
│   ├── analyzer.py
├── data/
│   ├── lottery_data.db
├── dashboards/
│   ├── tableau_lottery_dashboard.twbx
├── README.md
