# Sales Optimization & Revenue Growth Analysis for a Multi-Store Supermarket Chain

## Project Overview
Supermarket retail businesses operate in a high-volume, low-margin environment where small changes in customer behaviour can significantly impact revenue.

This project analyzes transactional retail data to investigate the **structural causes of declining supermarket sales** over a one-year period.

The analysis integrates:

- Exploratory Data Analysis using **Python**
- Analytical storytelling using **Tableau**
- Executive dashboards using **Power BI**

The goal is to identify key drivers of sales decline and propose **data-driven strategies to improve business performance**.

---

## Problem Statement
Supermarkets often experience fluctuations in sales due to factors such as:

- Seasonal demand variation  
- Changing customer behaviour  
- Product mix imbalance  
- Operational inefficiencies  
- Customer segment dependency  

However, identifying the **true structural driver of declining sales** is often difficult without proper data analysis.

This project investigates whether the decline is caused by **pricing changes, reduced transaction volume, customer behaviour shifts, or operational factors**.

---

## Dataset Overview

| Attribute | Details |
|-----------|--------|
| Total Transactions | 1,000 |
| Total Features | 21 (including 4 derived features) |
| Time Period | Jan – Dec 2019 |
| Branches | A, B, C |
| Cities | Yangon, Mandalay, Naypyitaw |
| Product Lines | 6 |
| Customer Types | Member, Normal |
| Payment Methods | Cash, Credit Card, E-wallet |

### Column Types

**Numerical Columns**
- Quantity
- Unit Price
- Tax %
- Total
- COGS
- Gross Income
- Gross Margin %
- Rating

**Categorical Columns**
- Branch
- City
- Customer Type
- Gender
- Product Line
- Payment
- Day Name
- Invoice ID

**Date & Time Columns**
- Date
- Time
- Hour
- Day
- Month

**Derived Features**
- Hour
- Day
- Month
- Day Name

Dataset Source: Public retail dataset from Kaggle

---

## Methodology

### 1. Base Plot Identification
Monthly **Revenue Trend** was selected as the base performance indicator.

### 2. Exploratory Data Analysis (Python)

- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Hypothesis testing

### 3. Revenue Decomposition

Revenue was decomposed as:

**Revenue = Price × Quantity**

This helped determine whether sales decline was caused by **price changes or volume reduction**.

### 4. Performance Classification

Monthly performance was categorized into:

- High  
- Moderate  
- Low  

This helped identify structural shifts in business performance.

### 5. Dashboard Development

Interactive dashboards were created using **Power BI** to monitor:

- Branch contribution
- Product performance
- Customer behavior
- Operational timing

---

## Key Insights

- Sales decline was primarily driven by **reduction in transaction volume**
- **Average selling price remained stable**, indicating demand contraction rather than pricing issues
- Customer participation reduced during lower performance months
- Sales performance shifted from **high-performance months to lower regimes**
- Branch contribution remained balanced, indicating **system-wide demand decline**

---

## Strategic Recommendations

- Monitor **transaction volume thresholds** to detect early decline
- Strengthen **customer retention strategies**
- Improve operational efficiency during **peak evening hours**
- Maintain **minimum performance benchmark levels**
- Implement **targeted promotions instead of generalized discounting**

---

## Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Tableau
- Power BI
- Excel

---

## Full Project Documentation

Due to the extensive size of the project (3-month analysis including weekly documentation), the complete project files are available here:

**Google Drive Folder:**  
🔗 [Full Project Files](https://drive.google.com/drive/folders/1dHNOc1hk15qjNh4OeyKbs75kX7l8LCpI?usp=drive_link)

The Drive folder includes:

- Full project report
- Weekly research documentation
- Tableau story files
- Power BI dashboards
- Python notebooks
- Project presentation

---


---

## Conclusion

This project demonstrates that declining supermarket sales performance was primarily driven by **structural volume contraction rather than pricing instability**.

The analytical framework developed through Python analysis, Tableau storytelling, and Power BI dashboards provides a **data-driven decision-support system for retail sales performance monitoring**.


