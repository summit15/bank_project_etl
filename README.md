# 🏦 Largest Banks by Market Capitalization – ETL Project

## 📊 Project Overview

This project is an automated **ETL (Extract, Transform, Load)** pipeline built in Python that compiles the list of the **top 10 largest banks in the world** ranked by **market capitalization in USD**, and converts it into multiple currencies using current exchange rates.

The script is designed to run quarterly to reflect updates in financial data and is fully modular with logging, transformation, CSV/database storage, and SQL querying functionality.

---

## 🚀 Key Features

- ✅ **Web scraping**: Extracts bank market cap data from Wikipedia (archived IMF source).
- 🔁 **Currency conversion**: Converts USD values into GBP, EUR, and INR using exchange rate CSV.
- 📄 **Output formats**: Saves the processed data to CSV and SQLite database.
- 🧾 **Logging**: Tracks every step of the ETL process in a log file.
- 📥 **SQL Querying**: Supports custom queries for analytics/reporting.

---

## 🧠 Technologies Used

| Tool/Library     | Purpose                          |
|------------------|----------------------------------|
| Python 3         | Programming language             |
| `pandas`         | Data manipulation                |
| `numpy`          | Numeric transformation           |
| `requests`       | Web requests                     |
| `BeautifulSoup4` | HTML parsing                     |
| `sqlite3`        | Local database storage           |
| `datetime`       | Logging timestamps               |


# Running the program will create a necessary log files and databse files too
