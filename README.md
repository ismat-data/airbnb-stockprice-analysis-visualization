# Airbnb Stock Price Analysis & Visualization

## 📌 Project Overview

This project presents a **comprehensive exploratory data analysis (EDA) and visualization of Airbnb's stock price performance**. The analysis focuses on understanding price movements, trading behavior and relationships between stock market indicators using **Python for data analysis** and **Power BI for interactive visualization**.

The dataset contains daily stock trading information including **Open, High, Low, Close, Adjusted Close prices and Volume**. The goal of this project is to transform raw financial data into meaningful insights through statistical analysis and visual dashboards.

---

# 🎯 Objectives

The main objectives of this project are:

* Analyze historical Airbnb stock price trends.
* Perform **data cleaning and preprocessing**.
* Conduct **univariate, bivariate and correlation analysis**.
* Understand relationships between stock variables such as price and trading volume.
* Create an **interactive Power BI dashboard** for business insights.
* Present clear visual storytelling using charts and analytical techniques.

---

# 📂 Dataset Information

The dataset contains daily stock market data with the following columns:

| Column    | Description              |
| --------- | ------------------------ |
| Date      | Trading date             |
| Open      | Opening stock price      |
| High      | Highest price of the day |
| Low       | Lowest price of the day  |
| Close     | Closing stock price      |
| Adj Close | Adjusted closing price   |
| Volume    | Number of shares traded  |

---

# 🛠 Tools & Technologies Used

### Programming & Analysis

* Python
* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn
* Power BI

### Development Environment

* Jupyter Notebook
* Microsoft Power BI Desktop

---

# 📊 Project Workflow

## 1️⃣ Data Loading

The dataset is loaded into Python using Pandas for analysis.

## 2️⃣ Data Assessment

Initial inspection of the dataset includes:

* Checking dataset structure
* Identifying data types
* Statistical summary of variables

## 3️⃣ Data Preprocessing

Key preprocessing steps include:

* Converting the **Date column into datetime format**
* Sorting records by date
* Preparing the dataset for time-series analysis

## 4️⃣ Data Cleaning

Cleaning operations include:

* Checking for missing values
* Removing duplicate records
* Ensuring dataset consistency

## 5️⃣ Feature Engineering

Additional features were created to improve analysis such as:

* Time-based insights
* Date gap analysis between trading days

---

# 📈 Exploratory Data Analysis (EDA)

## Univariate Analysis

This analysis focuses on understanding individual variables:

* Distribution of stock prices
* Trading volume patterns
* Time gaps between trading days

Key Insight:
Most trading intervals are **1-day gaps**, which is expected due to daily market operations.

---

## Bivariate Analysis

Relationships between variables were explored to understand stock behavior.

Examples:

* Open vs Close Price
* Volume vs Price Movements
* High vs Low Price Range

---

## Correlation Analysis

Correlation analysis was conducted to measure relationships between stock variables.

Key Finding:
A **very strong positive correlation (~0.99)** exists between **Open and Close prices**, indicating that opening price strongly influences closing price on the same trading day.

---

# 📊 Power BI Dashboard

The Power BI dashboard provides an interactive visualization layer for the analysis.

### Dashboard Highlights

The dashboard includes visualizations such as:

* 📈 Stock Price Trend Over Time
* 📊 Open vs Close Price Comparison
* 📉 High vs Low Price Range
* 📦 Trading Volume Analysis
* 📊 Correlation Insights Between Variables

These visualizations allow users to explore stock market behavior interactively.

---

# 🔎 Key Insights

* Airbnb stock prices show **consistent market-driven fluctuations** over time.
* **Opening and closing prices have an extremely strong positive relationship**.
* Trading volumes vary significantly depending on market activity.
* High and low prices demonstrate daily market volatility.

---

# 📁 Project Structure

```
Airbnb-Stock-Analysis
│
├── Airbnb-Stock-EDA.ipynb        # Python exploratory data analysis
├── airbnb-stock-dashboard.pbix   # Power BI visualization dashboard
├── dataset.csv                   # Stock price dataset
└── README.md                     # Project documentation
```

---

# 🚀 How to Run the Project

### Run the Python Analysis

1. Download the repository.
2. Open the notebook in **Jupyter Notebook / Google Colab**.
3. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

4. Run all notebook cells.

### View the Dashboard

1. Open the `.pbix` file in **Microsoft Power BI Desktop**.
2. Explore the interactive dashboard visuals.

---

# 📌 Use Cases

This project demonstrates skills relevant to:

* Data Analysis
* Financial Data Exploration
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Intelligence Dashboards

It is useful for **data analyst portfolios and financial data analytics projects**.

---

# 👨‍💻 Author

**Ismat Khan**
Data Analyst Enthusiast

📧 Email: [ismatafrozkhan121@gmail.com](mailto:ismatafrozkhan121@gmail.com)

---

# ⭐ If you found this project useful, consider giving it a star!
