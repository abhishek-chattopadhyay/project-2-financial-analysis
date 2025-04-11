# Effect of Economic Indicators on Financial Markets: A Data-Driven Analysis

Understanding the dynamics of financial markets is both intellectually stimulating and analytically challenging. This project investigates the relationship between key economic indicators and financial market performance, with a particular focus on the S&P 500 index. Conducted as part of the Ironhack Data Science Bootcamp, this end-to-end data analysis project combines data collection, cleaning, analysis, and presentation.

---

## 📌 Project Objective

- Analyze how economic indicators such as GDP, unemployment rate, and inflation impact the S&P 500.
- Collect and consolidate relevant data into a clean dataset suitable for analysis.
- Perform univariate and bivariate analysis on numerical and categorical data.
- Communicate findings effectively to stakeholders through visualizations and presentations.

---

## 📊 Data Sources

- **Economic Indicators:** [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/)
- **Stock Market Data:** [Yahoo Finance](https://finance.yahoo.com/)

---

## 🔍 Methodology

### 1. **Data Collection**
- Utilized the FRED API to fetch economic indicators.
- Extracted historical S&P 500 data using the `yfinance` Python module.

### 2. **Data Wrangling**
- Merged multiple time series into a unified DataFrame.
- Engineered relevant numerical and categorical features.
- Handled missing values appropriately.
- Created a clean dataset for analysis.

### 3. **Exploratory Data Analysis (EDA)**
- Conducted univariate and bivariate analysis to explore data distributions and relationships.
- Computed correlation matrices and visualized key insights.

---

## 📈 Results & Insights

### Key Findings:
1. **Market Crashes & Historical Events:**  
   Univariate analysis captured significant market downturns such as the 2008 Financial Crisis and the COVID-19 crash in early 2020—both instances when the S&P 500 dropped over 10% in a single month.

2. **Correlations with Economic Indicators:**  
   Correlation matrices reveal significant relationships between economic indicators and the S&P 500, highlighting the macroeconomic influence on stock performance.

3. **Additional Insights:**  
   For example, housing construction activity typically declines when the unemployment rate rises—a pattern supported by bivariate analysis.

---

## 📁 Project Structure

- [`/code`](./code): Contains the detailed Jupyter notebook with all code and analysis steps.
- [`/plot`](./plot): Includes all relevant visualizations and plots used in the analysis.
- [`/data`](./data): Ready-to-use cleaned dataset in CSV format.
- [`/presentation`](./presentation): Final stakeholder presentation summarizing findings and recommendations.

---

## 📬 Contact

If you have questions or feedback about this project, feel free to connect via [LinkedIn](https://www.linkedin.com/in/abhishekchemistry).

---

**Disclaimer:** This project is for educational purposes and does not constitute financial advice.
