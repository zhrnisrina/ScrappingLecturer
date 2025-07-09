# 🕸️ Web Scraper for Academic Profiles

This project is a Python-based web scraping tool built on Google Colab that extracts lecturer profile information from an academic institution's website. It automates the process of collecting structured data for research or administrative purposes.

## 📌 Features

- Extracts:
  - Lecturer name
  - NIDN/NIDK
  - Department
  - Education background (S1, S2, S3)
- Automatically parses HTML elements using `BeautifulSoup`
- Stores the extracted data in CSV format for easy analysis

## 🚀 How It Works

1. **Import libraries**: Uses `requests`, `BeautifulSoup`, `pandas`, and `re`.
2. **Target page**: Fetches the main search result page of academic staff profiles.
3. **Extract links**: Loops through the lecturer profile URLs.
4. **Scrape each profile**: Collects structured data from the HTML of each page.
5. **Store data**: Saves everything into a DataFrame and exports to CSV.

## 🛠️ Requirements

- Python 3.x
- Google Colab or Jupyter Notebook
- Packages: `requests`, `bs4`, `pandas`, `re`

## 📂 Output

The final output is a `profil_dosen.csv` file containing:
- Name
- NIDN/NIDK
- Department
- S1, S2, S3 education data

## 💡 Use Case

Useful for education research, institutional audits, or creating lecturer directories.
