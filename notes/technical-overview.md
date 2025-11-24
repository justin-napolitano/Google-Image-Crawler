---
slug: github-google-image-crawler-note-technical-overview
id: github-google-image-crawler-note-technical-overview
title: Google-Image-Crawler
repo: justin-napolitano/Google-Image-Crawler
githubUrl: https://github.com/justin-napolitano/Google-Image-Crawler
generatedAt: '2025-11-24T18:37:42.787Z'
source: github-auto
summary: >-
  Google-Image-Crawler is a Python tool to automate image downloads from Google
  Image Search using keywords. It utilizes Selenium for dynamic browsing and
  BeautifulSoup for parsing the HTML.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

Google-Image-Crawler is a Python tool to automate image downloads from Google Image Search using keywords. It utilizes Selenium for dynamic browsing and BeautifulSoup for parsing the HTML.

## Key Components:
- **Python 3**: Core language.
- **Selenium WebDriver**: Automates Chrome to scrape images.
- **BeautifulSoup4**: Parses HTML for image URLs.
- **urllib3**: Manages HTTP requests.

## Quick Start:
1. Clone the repo:
    ```bash
    git clone https://github.com/justin-napolitano/Google-Image-Crawler.git
    cd Google-Image-Crawler
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    If `requirements.txt` is missing, manually install:
    ```bash
    pip install selenium beautifulsoup4 urllib3
    ```
3. Configure `config.json` for your keywords and download settings.
4. Run the crawler:
    ```bash
    python seleniumCrawler.py
    ```

**Gotcha**: Ensure the ChromeDriver version matches your Chrome browser version.
