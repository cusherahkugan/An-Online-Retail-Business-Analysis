---

## Overview

This project analyzes an **online retail dataset** containing **401,604 transactions** and **£8.28M in revenue**.  
The aim is to uncover **key revenue drivers, top products and markets, customer segments, and seasonal trends**, enabling data-driven business strategy and growth.

---

## Features

- Analyze revenue distribution across transactions  
- Identify top-performing products and geographic markets  
- Examine monthly and seasonal revenue trends  
- Segment customers using **K-means clustering (k=3)**  
- Perform correlation analysis to identify revenue drivers  

---

## Tools & Libraries

- **Python**  
- **Pandas & NumPy** – Data manipulation  
- **Matplotlib & Seaborn** – Visualization  
- **Scikit-learn** – Clustering and standardization  
- **Jupyter Notebook** – Analysis environment  

---

## Project Structure

An-Online-Retail-Business-Analysis/
│
├── data/ # Dataset (online_retail.csv)
├── notebooks/ # Jupyter notebook with analysis
├── images/ # Generated plots
├── report/ # PDF report
└── README.md # Project overview


---

## Key Visualizations

| Plot | Description | Key Insight |
|------|-------------|-------------|
| Revenue distribution | Histogram with KDE | Right-skewed, most transactions are low-value, few high-value transactions |
| Top products by revenue | Bar chart | REGENCY CAKESTAND 3 TIER (£132K) highest revenue, home décor and seasonal items dominate |
| Top countries by revenue | Bar chart | UK contributes £6.75M (81.5%), highlighting strong domestic market |
| Monthly revenue trend | Line chart | Peaks in Nov 2011 (£1.13M), indicating seasonal Q4 demand |
| Correlation matrix | Heatmap | Quantity strongly drives revenue (0.92 correlation) |
| Customer segmentation | Scatter plot | Core, low-value, and high-value customers identified for targeted marketing |

---

## Key Insights

- Revenue concentrated in the **UK market** (81.5%)  
- Seasonal products drive strong sales, especially **Q4**  
- High-volume purchases are the primary driver of revenue  
- High-value customers contribute disproportionately and are key for loyalty programs  
- European markets present growth potential  

---

## Conclusion

This analysis demonstrates how **data analytics** supports business strategy in online retail.  
The insights provide actionable guidance for **marketing, inventory management, and market expansion**, enabling data-driven decision-making and revenue optimization.

---