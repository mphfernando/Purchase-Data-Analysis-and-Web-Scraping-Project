# Purchase-Data-Analysis-and-Web-Scraping-Project

## Overview
This project performs data analysis on a purchase dataset, scrapes product details from Walmart, and integrates the scraped data with existing datasets. Additionally, it offers interactive features for filtering, searching, and summarizing data using a command-line interface.

---

## Features

### 📊 Purchase Data Analysis:
- Detects missing values and ensures data consistency.
- Analyzes trends, popular product categories, and average customer spending.
- Visualizes data using line charts, bar charts, and pie charts.

### 🌐 Web Scraping:
- Scrapes product data (title, price, rating) from Walmart for multiple categories.
- Combines scraped data with existing datasets for enriched analysis.

### 🔍 Interactive Analysis Tools:
- Searches customer purchase history.
- Filters purchases based on date range and amount.
- Calculates total revenue by product category.
- Generates and exports a summary report highlighting top-performing products.

### 📁 Exporting Results:
- Saves processed datasets and summary reports as CSV files.

---

## 🛠 Installation

1. Clone the repository or download the project files.
2. Install dependencies:
   ```bash
   pip install pandas matplotlib beautifulsoup4 requests
   ```
3. If using Google Colab, upload the `.py` file and mount Google Drive for file operations.

---

## 🚀 Usage

### Prepare Datasets:
- Ensure the purchase data file (`purchase_data.csv`) is available.
- Place it in the specified directory or update the script’s file path.

### Run the Script:
- Execute the script in Python:
  ```bash
  python project.py
  ```
- Follow the menu prompts for interactive analysis.

### Web Scraping:
- The script scrapes product data for categories such as electronics, toys, books, and more.
- Ensure the target URLs are accessible and update `HEADERS` with a valid `User-Agent`.

### Outputs:
- Processed and matched datasets are saved as CSV files in the specified location.
- Summary reports are also exported as CSV files for further analysis.

---

## 📂 Files

- **`project.py`**: Main script containing all functionality.
- **`purchase_data.csv`**: Input purchase dataset (ensure this file exists in your drive).
- **Output Files:**
  - `combined_walmart_data.csv`: Combined dataset of scraped and existing data.
  - `matched_dataset_combined.csv`: Dataset with matched purchase and scraped data.
  - `summaryreport.csv`: Generated summary report highlighting top-performing products.

---


