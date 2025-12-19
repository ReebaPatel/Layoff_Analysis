# 📊 Global Startup Layoffs Analysis (2020–2024)

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on global startup layoffs from 2020 to 2024 using real-world data scraped from **Layoffs.fyi**.  
The goal is to uncover **temporal, industry-wise, geographic, and funding-stage patterns** in layoffs and understand how macroeconomic conditions have impacted companies of different sizes and maturity levels.

This project focuses on **insight generation and data understanding**, not prediction.

---

## ❓ Key Questions Explored
- How have layoffs evolved over time?
- Which countries experienced the highest number of layoffs?
- Which industries were most affected?
- At which funding stages are layoffs most prevalent?
- Do highly funded or publicly traded companies still experience large layoffs?

---

## 📂 Dataset
- **Source:** Layoffs.fyi (via Kaggle)
- **Time Range:** 2020–2024
- **Records:** 3,600+ layoff events
- **Type:** Real-world, publicly reported layoff data

Each row represents a reported layoff event by a company.

---

## 🧹 Data Cleaning & Preparation
The following steps were performed as part of EDA:
- Converted date fields to datetime format
- Removed irrelevant metadata columns (`Source`, `Date_Added`, etc.)
- Retained missing values in numeric fields to avoid false assumptions
- Filled missing categorical values with `"Unknown"`
- Created a `Year` feature for time-based analysis
- Used filtered views of data for quantitative vs frequency-based analysis

Minimal and purposeful cleaning was applied to preserve data authenticity.

---

## 📈 Exploratory Analysis Performed
- **Layoffs over time** to identify macro trends
- **Industry-wise layoffs** to understand sectoral impact
- **Country-wise layoffs** to identify geographic concentration
- **Funding stage vs layoffs** to compare early-stage vs mature companies
- **Funding raised vs layoffs** to assess whether capital protects against workforce reductions

---

## 🔍 Key Insights
- Layoffs peaked during the COVID and post-COVID period, reflecting economic disruption and hiring corrections.
- The United States accounts for the highest number of layoffs, driven by its concentration of tech and venture-backed firms.
- Retail and consumer-facing industries experienced significant workforce reductions.
- Post-IPO companies contributed the largest share of layoffs, indicating that even mature, publicly traded firms are vulnerable to market pressure.
- High fundraising does not guarantee workforce stability.

---

## 🧠 Conclusion
This analysis highlights that layoffs are influenced more by **macroeconomic conditions and market expectations** than company maturity alone.  
Both startups and large public companies are affected, emphasizing the importance of sustainable growth and operational efficiency.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📎 Notes
This project focuses on **exploration and insight generation**.  
Machine learning was intentionally not applied, as the dataset is event-based and not designed for predictive modeling.

---

## 🙌 Acknowledgements
- Data sourced from **Layoffs.fyi**
- Dataset curated and maintained by Roger Lee
