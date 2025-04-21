# Myproject
LinkedIn jobs Scraping Project

# LinkedIn Job Scraping

This project automates the process of scraping job listings from LinkedIn using Selenium and BeautifulSoup. It extracts job titles, company names, locations, and relevant skills to help analyze hiring trends and technical skill demands.

---

## 📌 Features

- Automated login and job search on LinkedIn
- Dynamic scrolling to load more job posts
- Extraction of:
  - Job title
  - Company name
  - Location
  - Job description
  - Skills (via keyword extraction using KeyBERT)
- Exporting the data to an Excel/CSV file
- Word cloud and frequency analysis of in-demand skills


## 🚀 Technologies Used

- **Python**
- **Selenium**
- **BeautifulSoup**
- **KeyBERT** (for keyword extraction from job descriptions)
- **Pandas**
- **Fake User Agent**
- **ChromeDriver Autoinstaller**
- **MongoDB** (optional)
- **Jupyter Notebook**


## 📦 Installation

Install all required libraries using pip:

```bash
pip install requests beautifulsoup4 pandas selenium \
chromedriver_autoinstaller torch fake-useragent \
python-dotenv keybert openpyxl pymongo

