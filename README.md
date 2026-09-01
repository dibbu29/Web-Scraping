# 📊 Wikipedia Data Scraping & Extraction

A Python-based web scraping project that automates the extraction, cleaning, and structuring of tabular data from Wikipedia into clean CSV format for analysis.

---

## 📌 Project Overview
Web data often exists in unstructured HTML tables that require cleaning before analysis. This project uses Python to fetch live Wikipedia pages, parse HTML structures, strip unnecessary metadata (such as reference tags like `[1]`), and load the processed data into structured Pandas DataFrames.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python 3
* **Libraries:** `beautifulsoup4`, `requests`, `pandas`
* **Environment:** Jupyter Notebook (`.ipynb`)

---

## ⚙️ Key Features
* **Automated HTTP Requests:** Fetches raw web content reliably using the `requests` library.
* **HTML Parsing:** Extracts target tables, headers, and rows using **BeautifulSoup**.
* **Data Cleansing:** Removes line breaks (`\n`), footnote references, and trailing whitespace.
* **Structured Export:** Processes raw data into **Pandas DataFrames** and exports ready-to-use `.csv` files.

