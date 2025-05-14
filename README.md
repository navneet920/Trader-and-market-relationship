# Trader Performance vs Market Sentiment Analysis

## Overview
This project explores the relationship between trader performance and market sentiment (Fear/Greed). Using datasets of trader transactions and Bitcoin market sentiment, we aim to uncover hidden patterns and derive actionable insights to guide smarter trading strategies.

---

## Objectives
- Explore the correlation between trader profitability, leverage usage, and market sentiment.
- Identify patterns in trader behavior during Fear and Greed periods.
- Cluster traders into behavior-based segments.
- Deliver recommendations for sentiment-aware trading strategies.

---

## Datasets
1. **Bitcoin Market Sentiment Dataset**
   - Columns: `Date`, `Classification` (Fear/Greed)

2. **Historical Trader Data**
   - Columns: `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Size USD`, `Side`, `Timestamp IST`, `Start Position`, `Direction`, `Closed PnL`, `Leverage`, etc.

---

## Analysis Steps

1. **Data Cleaning & Preparation**
   - Merging trader data with sentiment data.
   - Feature engineering (Profitability Flag, Aggression Score, etc.).

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap.
   - PnL distribution by sentiment.
   - Leverage usage comparison during Fear vs Greed.

3. **Advanced Analysis**
   - Clustering traders using KMeans and PCA.
   - Identifying trader profiles and anomalies.

4. **Insights & Recommendations**
   - Adaptive leverage strategies.
   - Sentiment-aware position sizing.
   - Cluster-based trading optimizations.

---

## Technologies Used
- Python 3.11+
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Files Included
- `historical_data.csv`
- `fear_greed_index.xlsx`
- `analysis_script.ipynb`
- `results/` (Visualizations, Reports)
- `README.md`

---

## How to Use
1. Clone this repository.
2. Place your datasets in the root directory.
3. Run the `analysis_script.ipynb` in Jupyter Notebook or VS Code.
4. Review the results in the `results/` folder.

---

## License
This project is licensed under the MIT License.

---

## Author
**Navneet Kumar**

---

