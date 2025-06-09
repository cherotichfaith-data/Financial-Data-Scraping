# 📈 Financial Data Scraper & Analyzer

This project is a Jupyter Notebook-based solution that uses web scraping and data analysis techniques to gather, process, and analyze financial data—specifically stock market prices and economic indicators—from [stockanalysis.com](https://stockanalysis.com/). The goal is to automate the extraction of relevant financial insights and visualize them in a meaningful way.

---

## 🧾 Introduction

The world is evolving rapidly and increasingly relies on **real-time data** for informed decision-making. This assignment focuses on scraping financial data from **stockanalysis.com** with the aim of extracting valuable information including **stock prices** and **economic indicators**. Selenium-based automation tools are used to scrape the data efficiently, which is then analyzed to derive meaningful insights.

---

## 🧰 Libraries Used

- **Selenium**: Automates browsers and handles JavaScript-rendered content.
- **Webdriver Manager**: Automatically installs and manages the appropriate version of ChromeDriver.
- **Pandas**: Provides robust data structures for handling tabular data (e.g., CSV files).
- **NumPy**: Supports numerical computations and efficient data manipulation.
- **Matplotlib**: Used for plotting data visualizations.
- **Seaborn**: Enhances Matplotlib graphs with attractive and informative visuals.

---

## 📂 Output Directory

Before the scraping begins, the code checks for and creates an `financial_data/` directory to store CSV outputs. This ensures all scraped and processed data is organized and accessible.

---

## ⚙️ Setting Up

### Web Driver and Selenium Configuration

- Chrome browser is configured using Selenium WebDriver.
- WebDriver Manager handles installation.
- The automation simulates user interaction to dynamically load content from websites.

---

## 🌐 Target Website

The script targets sections of **stockanalysis.com** to scrape financial details like:

- Income Statements  
- Balance Sheets  
- Cash Flows  
- Financial Ratios

A debugging screenshot (`page_debugging.png`) is saved to verify the page load during scraping.

---

## 📥 Loading Data

CSV files (e.g., `income_statement.csv`, `cash_flow.csv`) are loaded into **Pandas DataFrames** for further inspection and analysis.

---

## ✅ Data Validation

- Checks for missing values.
- Summarizes data (mean, std, min, max, etc.).
- Helps detect inconsistencies or outliers in scraped data.

---

## 📊 Analysis Modules

### 📈 Analyzing Revenue

- Analyzes revenue over the last five years.
- Factors include initial investment, operating revenue, and other revenue streams.

### 💵 Cash Growth Calculation

- Builds a DataFrame for fiscal year and short-term investments.
- Computes yearly percentage growth.
- Understands a company’s liquidity trajectory over time.

### 📉 Net Income & Depreciation Trends

- Tracks **Net Income**, **Depreciation**, and **Asset Write-downs**.
- Offers insight into company profit behavior and capital asset usage over time.

---

## 🔄 Trend Extraction and Visualization

### 📉 Extracting Financial Values

- Flattens data to ease processing.
- Focuses on `Net Income` and similar financial metrics for trend analysis.

### 📊 Financial Trend Visualization

- Visualizes:
  - Net Income over time
  - Growth of non-cash expenses
  - Company restructuring costs

---

## 📈 Net Income Trends

- Analyzes how `Net Income` evolved annually.
- Reveals performance metrics and earnings strength.

---

## 🔗 Correlation Matrix

- Visual representation of correlation between financial features using Seaborn heatmaps.

---

## 🔮 Forecasting: Linear Regression

- Trains a **Linear Regression** model using data from 2020–2024.
- Forecasts `Net Income` for 2025 and 2026.
- Visualization shows predicted vs. actual trends.

---

## 🚨 Outlier Detection

- Uses **Interquartile Range (IQR)** to detect outliers in `Net Income`.
- Identifies financial anomalies over the analyzed period.

---

## 🔍 Final Analysis: Revenue vs Net Income

- Compares five-year trends of **Revenue** and **Net Income**.
- Offers conclusions about the company’s financial health and profitability.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).




