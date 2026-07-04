# Real-Estate-Data-Pipeline
Advanced Python data pipeline using Pandas and BeautifulSoup to scrape, clean, and securely archive automated real estate listings with anti-bot protection.
Markdown


# Multi-Threaded Real Estate Data Pipeline

An advanced, enterprise-grade Python data pipeline that monitors, scrapes, and archives property listings. 

## Features
- **Fail-Safe Ingestion:** Implements exponential backoff retry mechanism (up to 3 attempts) for network requests.
- **Anti-Bot Protection:** Rotates multiple modern User-Agents randomly to mimic browser human behavior.
- **Data Rotation & Backups:** Automated folder directory cleanup using `os` and `shutil`, backing up old files with high-precision timestamps.
- **High-Performance Processing:** Built with `Pandas` and `Numpy` for optimized vector-based dataset manipulation and deterministic UUID generation.

## Tech Stack
- Python 3.x
- Pandas / Numpy
- BeautifulSoup4 / Requests
