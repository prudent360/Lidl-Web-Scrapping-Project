Trustpilot Lidl Review Scraper 🍅📊
A Python-based web scraping project to extract customer reviews from Lidl's Trustpilot page. This tool collects author names, review titles, dates, ratings, and text from multiple pages and stores the data in a structured format.

1. Table of Contents
2. Project Overview
3. Technologies Used
4. Setup & Requirements
5. How to Use
6. Data Structure
7. Output Examples
8. Legal & Ethical Notes
9. Contributing
10. License

11. Project Overview
    This project scrapes customer reviews from Lidl's Trustpilot page (https://uk.trustpilot.com/review/www.lidl.co.uk ) to analyze user feedback. The script:

Bypasses basic bot detection using mechanize
Extracts author , title , date , rating , and review text
Stores data in a pandas DataFrame and exports to CSV/Excel
Supports multi-page scraping for comprehensive data collection

2. Technologies Used
   Python : Core programming language
   Mechanize : For browser emulation and page navigation
   BeautifulSoup : HTML parsing
   Pandas : Data structuring and export
   Jupyter Notebook : Development environment

3. Setup & Requirements
   Installation

- Clone this repository:

git clone https://github.com/prudent360/lidl-trustpilot-scraper.git
cd lidl-trustpilot-scraper

- Install dependencies
  pip install -r requirements.txt

requirements.text

beautifulsoup4==4.12.3
mechanize==0.4.9
pandas==2.0.3
