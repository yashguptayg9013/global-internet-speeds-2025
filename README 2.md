# 🌐 Global Internet Speeds 2025 — Business Analysis

![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13-4c72b0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

> **A comprehensive Exploratory Data Analysis (EDA) of internet connectivity across 157 countries, uncovering global digital divides, regional infrastructure patterns, and strategic business insights.**

---

## 📌 Project Overview

As a Business Analyst, understanding **digital infrastructure** is critical for market entry assessments, product strategy decisions, and digital transformation roadmaps. This project analyses the **Speedtest Global Index 2025** dataset to answer:

- Which countries and regions lead (and lag) in internet connectivity?
- Is there a significant gap between broadband and mobile performance?
- What strategic implications do connectivity disparities have for businesses?
- How reliable is the available data across different regions?

---

## 📊 Key Findings

| Insight | Detail |
|---|---|
| 🏆 Fastest Broadband | **Singapore — 410 Mbps** |
| 📱 Fastest Mobile | **UAE — 652 Mbps** |
| 🐢 Slowest Broadband | **Syria — 3.5 Mbps** (116× gap vs Singapore) |
| 🌍 Strongest Region (Broadband) | **East Asia — avg 255.7 Mbps** |
| 🌍 Weakest Region (Broadband) | **Africa — avg 39.9 Mbps** |
| 📡 Mobile Leader Region | **Middle East — avg 194.9 Mbps** (5G-driven) |
| 🔗 Broadband↔Mobile Correlation | **r = 0.46** (moderate positive) |
| ⚠️ Data Gap | **53 countries (33.8%) lack mobile data** |

---

## 📁 Repository Structure

```
global-internet-speeds-2025/
│
├── 📓 Global_Internet_Speeds_2025_EDA.ipynb    # Full Jupyter Notebook (EDA)
├── 📄 Global_Internet_Speeds_2025_Report.docx  # Professional BA Report
├── 📂 data/
│   └── global_internet_speeds_2025.csv         # Raw dataset (157 countries)
├── 📂 charts/                                  # All 10 generated visualisations
│   ├── 01_top15_broadband.png
│   ├── 02_bottom15_broadband.png
│   ├── 03_top15_mobile.png
│   ├── 04_regional_broadband_boxplot.png
│   ├── 05_regional_avg_bb_vs_mob.png
│   ├── 06_scatter_bb_vs_mob.png
│   ├── 07_mobile_vs_broadband_gap.png
│   ├── 08_data_coverage.png
│   ├── 09_distributions.png
│   └── 10_correlation.png
└── README.md
```

---

## 🔍 Analysis Sections

The Jupyter Notebook walks through **10 structured sections**:

1. **Environment Setup** — Libraries, colour palette, reproducibility config
2. **Data Loading & First Look** — Structure, dtypes, region mapping for 157 countries
3. **Data Quality Assessment** — Missing values, coverage analysis, reliability scoring
4. **Descriptive Statistics** — Mean, median, std dev, quartiles, skewness, kurtosis
5. **Top & Bottom Rankings** — Fastest/slowest countries for broadband and mobile
6. **Distribution Analysis** — Histograms, outlier detection (IQR method)
7. **Regional Analysis** — Boxplots and grouped bars across 11 world regions
8. **Broadband vs Mobile Comparison** — Scatter plots, parity analysis, gap rankings
9. **Correlation Analysis** — Pearson correlation, regression line, heatmap
10. **Business Insights & Recommendations** — 5 strategic findings with action items

---

## 📈 Visualisations

The project includes **10 publication-quality charts**:

| # | Chart | Type |
|---|---|---|
| 1 | Top 15 Broadband Countries | Horizontal Bar |
| 2 | Bottom 15 Broadband Countries | Horizontal Bar |
| 3 | Top 15 Mobile Countries | Horizontal Bar |
| 4 | Regional Broadband Distribution | Boxplot |
| 5 | Regional Avg — Broadband vs Mobile | Grouped Bar |
| 6 | Broadband vs Mobile per Country | Scatter Plot |
| 7 | Mobile vs Broadband Speed Gap | Diverging Bar |
| 8 | Data Coverage | Pie Charts |
| 9 | Speed Distributions | Histograms |
| 10 | Correlation Matrix + Regression | Heatmap + Scatter |

---

## 💡 Strategic Recommendations

1. **Market Entry Prioritisation** — Target Europe, East Asia, and North America for digital-heavy products (speeds reliably >150 Mbps)
2. **Mobile-First for Gulf Markets** — UAE, Qatar, and Kuwait are 5G-dominant; optimise products for mobile delivery
3. **Low-Bandwidth Design for Africa & South Asia** — Design offline-capable, data-efficient applications for these markets
4. **Dual-Channel Strategy for South America** — Strong broadband in cities, weak mobile connectivity rurally
5. **Always Evaluate Both Metrics** — r = 0.46 means broadband quality does not predict mobile quality; assess both independently

---

## 🛠️ How to Run

### Prerequisites
```bash
pip install pandas matplotlib seaborn plotly jupyter
```

### Run the notebook
```bash
git clone https://github.com/YOUR_USERNAME/global-internet-speeds-2025.git
cd global-internet-speeds-2025
jupyter notebook Global_Internet_Speeds_2025_EDA.ipynb
```

---

## 📦 Tech Stack

| Tool | Purpose |
|---|---|
| **Python 3.10** | Core programming language |
| **Pandas** | Data loading, cleaning, transformation |
| **NumPy** | Numerical operations, statistical calculations |
| **Matplotlib** | Base visualisation engine |
| **Seaborn** | Statistical charts (boxplots, heatmaps) |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📄 Data Source

- **Dataset:** Speedtest Global Index 2025 by Ookla
- **Coverage:** 157 countries, broadband + mobile download speeds
- **Metrics:** Download speed in Megabits per second (Mbps)

---

## 👤 Author

**Yash Gupta** — Business Analyst

- 📧 yashguptayg9013.ie@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/YOUR_PROFILE)
- 🐙 [GitHub](https://github.com/YOUR_USERNAME)

---

## 📌 LinkedIn Post Template

> Just published a Business Analysis project on **Global Internet Speeds 2025** 🌐
>
> Analysed 157 countries across broadband and mobile metrics to uncover:
> - A **116× speed gap** between Singapore and Syria
> - How the Gulf states are **leapfrogging broadband** with 5G mobile
> - Why South America has **world-class broadband** but weak mobile
> - **5 strategic recommendations** for digital market entry
>
> Tools: Python • Pandas • Matplotlib • Seaborn • Jupyter
>
> 🔗 GitHub: [link] | Full report: [link]
>
> #BusinessAnalysis #DataAnalysis #Python #EDA #PortfolioProject #DataScience

---

*This project is part of my Business Analyst portfolio, demonstrating skills in data cleaning, exploratory analysis, visualisation, and translating data into business strategy.*
