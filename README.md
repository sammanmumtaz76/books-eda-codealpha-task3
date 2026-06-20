# 📚 Books Dataset — EDA & Visualization
**CodeAlpha Data Analytics Internship**

## 📌 Overview
This repository contains the complete analysis of 1,000 books scraped from 
books.toscrape.com — covering statistical EDA (Task 2) and an interactive 
Tableau dashboard (Task 3).

---

## 🎯 Task 2 — Exploratory Data Analysis
**File:** `notebooks/Books_EDA.ipynb`

Statistical analysis using Python, pandas, and scipy — including:
- Data quality checks (nulls, duplicates, scraping artifacts)
- Univariate analysis (price, category, rating distributions)
- Outlier detection (IQR method)
- Bivariate & multivariate analysis (price vs rating, category trends)
- Hypothesis testing (ANOVA)

### Key Findings
- Price distribution is nearly symmetrical (skewness = −0.04)
- Price and rating are statistically independent (ANOVA: p = 0.833)
- 21.9% of category labels were scraping artifacts — cleaned before analysis
- Historical Fiction offers the best value (low price + solid rating)

---

## 🎨 Task 3 — Data Visualization Dashboard
**File:** `dashboard/Books-EDA-Dashboard.twbx`

An interactive Tableau dashboard built to visually communicate the findings 
from Task 2 to a non-technical audience.

### Dashboard Preview
![Dashboard Screenshot](dashboard/dashboard_screenshot.png)

### What's Included
| Visual | Purpose |
|--------|---------|
| Price Distribution (Histogram) | Shows how prices are spread across £10–£60 |
| Price Segments (Donut Chart) | Low / Medium / Premium price tier breakdown |
| Rating Distribution (Bar Chart) | How books are rated across 1–5 stars |
| Price vs Rating | Tests whether expensive books get better ratings |
| Top Categories by Price | Highlights highest-priced genres |
| Category Heatmap | Combined view of price and rating across genres |
| KPI Cards | Total Books, Average Price, Average Rating, Total Categories |

### How to View
This dashboard requires **Tableau Desktop or Tableau Reader** (free) to open 
the `.twbx` file. A static preview is included above for quick viewing 
without installing any software.

---

## 🛠️ Tools Used
Python · pandas · numpy · scipy · Tableau

## 👤 Author
Samman — BSCS, University of Sargodha# books-eda-codealpha-tak3
