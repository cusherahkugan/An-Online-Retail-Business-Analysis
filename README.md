# Online Retail Business Analytics

## Business Problem
The objective of this project is to analyze online retail data to identify key drivers of revenue and provide strategic insights to senior management (CEO and CMO) for future business planning.

## Dataset
- Source: Kaggle (TATA Online Retail Dataset)
- Format: CSV
- Domain: E-commerce / Online Retail

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Analysis Performed
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Revenue analysis by category and region
- Trend analysis
- Correlation analysis
- Customer segmentation using K-Means clustering

## Key Visualizations

| Plot | Description | Key Insight |
|------|-------------|-------------|
| Revenue distribution | Histogram with KDE | Right-skewed, most transactions are low-value, few high-value transactions |
| Top products by revenue | Bar chart | REGENCY CAKESTAND 3 TIER (£132K) highest revenue, home décor and seasonal items dominate |
| Top countries by revenue | Bar chart | UK contributes £6.75M (81.5%), highlighting strong domestic market |
| Monthly revenue trend | Line chart | Peaks in Nov 2011 (£1.13M), indicating seasonal Q4 demand |
| Correlation matrix | Heatmap | Quantity strongly drives revenue (0.92 correlation) |
| Customer segmentation | Scatter plot | Core, low-value, and high-value customers identified for targeted marketing |


## Key Insights
- Revenue concentrated in the **UK market** (81.5%)  
- Seasonal products drive strong sales, especially **Q4**  
- High-volume purchases are the primary driver of revenue  
- High-value customers contribute disproportionately and are key for loyalty programs  
- European markets present growth potential  

## Business Recommendations
- Focus expansion on high-performing regions
- Invest marketing resources in top product categories
- Target high-value customer segments with personalized campaigns

## Repository Structure
- data/ -> dataset (online_retail.csv)
- notebooks/ -> analysis notebook
- images/ -> visualizations
- report/ ->  report
