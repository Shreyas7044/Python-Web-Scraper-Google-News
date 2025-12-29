# Python-Web-Scraper-Google-News
A Python-based web scraper that extracts article links from Google News using BeautifulSoup and urllib. This project demonstrates how to parse HTML, identify anchor tags, and filter article URLs efficiently. Useful for beginners learning web scraping, parsing, and Python automation concepts.

This project is a Python-based web scraper that pulls article URLs from Google News by extracting anchor tags from the HTML structure. It uses the BeautifulSoup library to parse the page and identify article links.

## 📌 Details
Google News uses tags to create links to websites shown on the platform. Along with additional metadata, this scraper collects all article URLs displayed on Google News.
I have used the BeautifulSoup module to analyze data from Google News.
Parsing means converting HTML into a structured format so that a programming language can work with it easily. Here, Python parses HTML and extracts article URLs.
To install BeautifulSoup, use: pip install beautifulsoup4

## 🧠 How It Works
Python provides an inbuilt module called `urllib` to handle URLs.

The `Scraper` class:
- Takes the site URL as input
- Sends a request to fetch the HTML page
- Uses BeautifulSoup to parse HTML
- Extracts all `<a>` tags
- Prints only Google News article URLs

## 🧾 Code Overview
- `urllib.request.urlopen()` → Sends request and fetches page HTML
- `BeautifulSoup(html, "html.parser")` → Parses HTML
- `find_all("a")` → Finds all links
- Filters URLs containing `"articles"`

## ▶️ Run The Application
python main.py

Make sure Python and BeautifulSoup are installed.

## 📷 Application Screenshot
![Application Screenshot](screenshot.png)

## 🛠 Requirements
- Python 3.x
- beautifulsoup4

Install dependencies:
pip install -r requirements.txt

## 🚀 Output
You will see a list of Google News article URLs printed in the terminal.

## 🙌 Uses
- Learn Web Scraping
- Understand HTML parsing
