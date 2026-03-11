---

# 📊 Cryptocurrency Market Analysis

## 📌 Project Overview

This project focuses on **collecting, cleaning, and analyzing cryptocurrency market data** from CoinMarketCap. The dataset was obtained through **web scraping techniques** and analyzed using Python data science libraries.

The goal of the project is to understand ** cryptocurrency market trends, price movements, market capitalization, and trading volumes ** through **data preprocessing and visualization techniques**.

The project follows a complete **Data Science workflow** including:

* Web Scraping
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Observational Insights

---

# 📂 Dataset Information

The dataset contains **1000 rows and 9 columns** representing cryptocurrency market statistics.

### Dataset Columns

| Column       | Description                                  |
| ------------ | -------------------------------------------- |
| Rank         | Ranking of the cryptocurrency by market cap  |
| Name         | Name of the cryptocurrency                   |
| Symbol       | Trading symbol of the cryptocurrency         |
| Price (USD)  | Current price in US dollars                  |
| 1h %         | Price change percentage in the last 1 hour   |
| 24h %        | Price change percentage in the last 24 hours |
| 7d %         | Price change percentage in the last 7 days   |
| Market Cap   | Total market capitalization                  |
| Volume (24h) | Total trading volume in the last 24 hours    |

---

# 🌐 Data Collection (Web Scraping)

The cryptocurrency data was scraped from:

🔗 [https://coinmarketcap.com](https://coinmarketcap.com)

### Tools Used

* **Python**
* **Selenium**
* **BeautifulSoup**
* **Requests**

### Extracted Data Fields

The scraper extracted:

* Rank
* Cryptocurrency Name
* Symbol
* Price
* 1h Percentage Change
* 24h Percentage Change
* 7d Percentage Change
* Market Capitalization
* 24h Trading Volume

The scraper navigates multiple pages to collect **1000+ cryptocurrency records**.

---

# 🧹 Data Cleaning & Preparation

Before performing analysis, the dataset was cleaned using **Pandas**.

### Cleaning Steps

1. **Checked Dataset Shape**

   * Total rows: **1000**
   * Total columns: **9**

2. **Column Standardization**

   * Converted column names to lowercase.
   * Removed unnecessary characters.

3. **Handled Missing Values**

   * Verified if any missing values exist.
   * Cleaned inconsistent data formats.

4. **Removed Duplicate Records**

   * Checked for duplicate entries and removed them if present.

5. **Data Type Conversion**

   * Converted price, market cap, and volume columns into numeric values.

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed to understand **market patterns and cryptocurrency behavior**.

## 1️⃣ Univariate Analysis

Univariate analysis studies **one variable at a time**.

### Example Columns Used

* Price
* Market Cap
* Volume (24h)
* 24h %

### Insights

* Most cryptocurrencies have **low prices**, while a few have extremely high prices (e.g., Bitcoin).
* Market capitalization distribution is **highly skewed**, dominated by a few major coins.
* Trading volume varies significantly between coins.

---

## 2️⃣ Bivariate Analysis

Bivariate analysis examines the **relationship between two variables**.

### Example Relationships

| Variable 1 | Variable 2 |
| ---------- | ---------- |
| Price      | Market Cap |
| Price      | Volume     |
| Market Cap | Volume     |

### Insights

* Cryptocurrencies with **higher market caps generally have higher trading volumes**.
* Higher price coins are **not always the ones with highest volume**.
* Market leaders dominate trading activity.

---

## 3️⃣ Multivariate Analysis

Multivariate analysis studies **multiple variables together**.

### Example Variables

* Price
* Market Cap
* Volume
* 24h %
* 7d %

### Insights

* Coins with high market cap tend to have **lower volatility**.
* Smaller cryptocurrencies show **larger percentage price changes**.

---

# 📈 Visualization Techniques

Different visualization techniques were used to understand the data:

### Univariate Plots

* Histogram
* Box Plot
* Density Plot

### Bivariate Plots

* Scatter Plot
* Line Plot
* Correlation Heatmap

### Multivariate Plots

* Pair Plot
* Bubble Chart
* Heatmaps

---

# 🛠️ Technologies Used

| Tool             | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Programming Language      |
| Pandas           | Data Cleaning & Analysis  |
| NumPy            | Numerical Operations      |
| Matplotlib       | Data Visualization        |
| Seaborn          | Statistical Visualization |
| Selenium         | Web Scraping              |
| BeautifulSoup    | HTML Parsing              |
| Jupyter Notebook | Development Environment   |

---

# 📊 Key Insights

* The cryptocurrency market is **highly concentrated**, with a few coins dominating market capitalization.
* **Bitcoin and Ethereum** maintain the largest market influence.
* High market cap coins generally show **lower volatility compared to smaller coins**.
* Trading volume is strongly linked to **market popularity and investor interest**.

---

# 📁 Project Structure

```
Cryptocurrency-Market-Analysis
│
├── coinmarketcap_full_data.csv
├── Web Scraping.ipynb
├── Coin_market.ipynb
├── Coin Market Analysis.pptx
└── README.md
```

---

# 🎯 Project Outcome

This project demonstrates:

* **Real-world web scraping skills**
* **Data cleaning techniques**
* **Exploratory Data Analysis**
* **Visualization of financial datasets**

It provides a **practical understanding of cryptocurrency market behavior using data science tools**.

---

