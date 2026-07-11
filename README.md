# 📈 Value Trap Analysis in Vietnam Stock Market
### Experimental Design & Data Analytics for Investment Decision Making

> An end-to-end financial analytics project that investigates whether low valuation stocks (Value Stocks) truly outperform the market or become Value Traps by combining financial data collection, exploratory analysis, statistical hypothesis testing, and quantitative investment experiments.

---

# 📌 Project Overview

Many investors believe that buying stocks with a low P/E ratio is a good investment strategy.

However, not every "cheap" stock is actually undervalued.

Some companies remain cheap because their business fundamentals continue to deteriorate.

These stocks are commonly known as **Value Traps**.

This project investigates:

- Can low P/E stocks consistently outperform the market?
- Which financial indicators help distinguish genuine value opportunities from value traps?
- Does combining valuation metrics with business quality improve investment performance?

Rather than building a forecasting model, this project focuses on **data-driven investment research** using statistical analysis and experimental design.

---

# 🎯 Business Problem

Investment decisions based solely on valuation ratios often lead to poor portfolio performance.

This project aims to answer several practical questions:

### Investment Strategy

- Is buying low P/E stocks a profitable strategy?

### Fundamental Analysis

- Which financial indicators best identify high-quality companies?

### Portfolio Construction

- Does combining valuation and quality filters improve returns?

### Statistical Validation

- Are the observed differences statistically significant?

---

# 🏗 Project Workflow

```
VNStock API
      │
      ▼
Financial Data Collection
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Experimental Design
      │
      ▼
Statistical Hypothesis Testing
      │
      ▼
Investment Insights
```

---

# 📂 Dataset

## Source

- VNStock
- VCI Market Data

## Market

Vietnam Stock Market

## Universe

VN100 Companies

## Study Period

- 2020
- 2021
- 2022
- 2023

Collected information includes

- Market valuation
- Financial statements
- Profitability
- Revenue growth
- Debt ratio
- Historical stock prices

---

# 🛠 Technology Stack

## Programming

- Python

## Data Processing

- Pandas
- NumPy

## Data Collection

- VNStock API

## Statistics

- SciPy
- StatsModels

## Visualization

- Matplotlib
- Seaborn

---

# ⚙ Data Pipeline

## 1. Financial Data Collection

Automatically collect financial information for VN100 companies.

Collected data includes

- P/E Ratio
- ROE
- Revenue Growth
- Debt-to-Equity
- Historical Prices

Data is cached locally to improve reproducibility and reduce repeated API calls.

---

## 2. Data Cleaning

Processing steps include

- Handle missing values
- Remove incomplete companies
- Align financial periods
- Merge yearly datasets
- Standardize financial metrics

---

## 3. Feature Engineering

Create investment factors including

### Value Factors

- P/E

### Quality Factors

- ROE
- Revenue Growth
- Debt-to-Equity

### Composite Quality Score

Multiple quality metrics are combined into a single ranking score to evaluate company fundamentals.

---

# 📊 Exploratory Data Analysis

The project explores

## Financial Metric Distribution

- P/E
- ROE
- Growth
- Leverage

---

## Correlation Analysis

Relationships between

- Valuation
- Profitability
- Growth
- Returns

---

## Company Comparison

Analyze how financial characteristics differ across firms and years.

---

# 🧪 Experimental Design

Instead of predicting prices, this project evaluates investment strategies through controlled experiments.

## Strategy 1

Low P/E portfolio

---

## Strategy 2

Low P/E + High ROE

---

## Strategy 3

Low P/E + High Revenue Growth

---

## Strategy 4

Low P/E + Low Debt-to-Equity

---

## Strategy 5

Composite Quality Score

Companies are ranked using multiple quality indicators before portfolio selection.

---

# 📈 Statistical Analysis

The project performs hypothesis testing to validate whether strategy performance differs significantly.

Examples include

- Mean comparison
- Ranking analysis
- Double sorting
- Statistical significance testing

This ensures investment conclusions are supported by statistical evidence rather than visual observation alone.

---

# 💡 Key Business Insights

The analysis investigates questions such as

- Does low valuation alone produce superior returns?
- Which financial indicators reduce the probability of investing in value traps?
- Which combination of factors generates the strongest investment portfolio?

The results provide evidence-based guidance for investors rather than relying on intuition.

---

# 📊 Visualization

Visualizations include

- Distribution plots
- Correlation heatmaps
- Boxplots
- Portfolio comparison
- Financial metric distributions
- Return comparison across strategies

---

# 📁 Repository Structure

```
value-trap-analysis/

│
├── data/
│
├── data_cache/
│
├── pipeline.ipynb
│
└── README.md
```

---

# 📌 Skills Demonstrated

✔ Financial Data Collection

✔ API Integration

✔ Data Cleaning

✔ Exploratory Data Analysis (EDA)

✔ Feature Engineering

✔ Experimental Design

✔ Statistical Hypothesis Testing

✔ Quantitative Finance Analytics

✔ Data Visualization

✔ Investment Research

✔ Data Storytelling

✔ Python

---

# 🔮 Future Improvements

- Build an automated ETL pipeline
- Add Fama-French factor analysis
- Backtest with transaction costs
- Compare against VNIndex benchmark
- Create an interactive Power BI dashboard
- Deploy a Streamlit application for portfolio screening

---

# ⭐ If you find this project useful, please consider giving it a star!