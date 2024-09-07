# Web Scraping Projects

This repository contains Python scripts for web scraping job listings from **Wuzzuf** and **LinkedIn** using **BeautifulSoup**.

## Features

- **Wuzzuf Scraper:**
  - Fetches job listings based on predefined search criteria.
  - Extracts job title, company, location, and posted date.
  - Supports pagination to scrape multiple pages of results.

- **LinkedIn Scraper:**
  - Scrapes job postings directly from public LinkedIn pages without requiring login.
  - Retrieves job title, company, location, and job description.
  - Handles basic HTML structure and job listings loaded on static pages.

## Requirements

- Python 3.7+
- BeautifulSoup4
- Requests
- Pandas (for data manipulation)
  
## Make sure you have the following libraries installed before running the scripts:

- **requests:** For making HTTP requests to web pages.
- **beautifulsoup4 (bs4):** For parsing HTML and extracting data.

To install the necessary libraries, run the following commands:

```bash
pip install requests
pip install beautifulsoup4


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/web-scraping.git
   cd web-scraping
