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
