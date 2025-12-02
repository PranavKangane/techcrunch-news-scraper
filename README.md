# techcrunch-news-scraper
A Python-based web scraping project that collects article metadata (author, title, category, published date, and URL) from TechCrunch using requests and BeautifulSoup.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Web Scraping](https://img.shields.io/badge/Web%20Scraping-BeautifulSoup-green)
![Data](https://img.shields.io/badge/Dataset-CSV-orange)

## 🚀 Project Highlights
- Handles full pagination (up to N pages)
- Extracts author, title, category, datetime, and article URL
- Uses modular, scalable architecture
- Includes a datetime-based stopping condition (stops once year != 2025)
- Saves clean structured CSV output for analysis

# 📰 TechCrunch News Scraper  
A Python web scraping project that extracts structured article metadata from TechCrunch, including **title, author, category, publication date, and article URL**.  
The scraper is fully modular, supports pagination, includes a date-based stopping condition, and outputs clean CSV files for analysis.

---

## 📌 Project Highlights

- Scrapes the latest articles from TechCrunch
- Extracts:
  - Article title  
  - Author name  
  - Category  
  - Publication datetime  
  - Article URL  
- Handles multi-page pagination
- Stops automatically when articles no longer match a target year (e.g., stop when year ≠ 2025)
- Clean, modularized Python code
- Outputs structured data in CSV format for analytics, NLP, dashboards, or trend research

---

## 📂 Repository Structure

```
techcrunch-news-scraper/
│
├── README.md
├── techcrunch_scraper.py
│
├── data/
    └── techcrunch_articles_2025.csv

```

---

## 🔧 Technologies Used

- Python 3.9+
- Requests
- BeautifulSoup4
- LXML parser
- CSV module

---



## 📊 Output Dataset Format

Each row in the generated CSV contains:

| Column     | Description                                                   |
|------------|---------------------------------------------------------------|
| author     | Name of the article’s author                                 |
| title      | Title of the TechCrunch article                              |
| category   | Article category (AI, FinTech, Startups, etc.)               |
| datetime   | Publication timestamp (ISO format)                           |
| url        | Direct link to the article                                   |

---

## 🎯 Who Can Use This Dataset?

This dataset is useful for:

- **Data analysts** studying publication patterns  
- **Journalists** tracking tech news trends  
- **Marketing analysts** performing content research  
- **VCs & founders** analyzing startup activity  
- **NLP researchers** building topic models & text classifiers  
- **Students** learning web scraping & data engineering  


