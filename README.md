# 📈 Cryptocurrency Market Insights

This project analyzes historical cryptocurrency market data to explore trends, compare key metrics across popular coins, and visualize relationships between price, volume, and market capitalization. The goal is to better understand market dynamics and provide insights into cryptocurrency behavior over time.

---

## 📂 Data

The datasets used include:

- `coin_gecko_2022-03-16.csv`
- `coin_gecko_2022-03-17.csv`

They contain features such as:

- **Price Data**: `price`, `24h_high`, `24h_low`  
- **Volume & Market Metrics**: `total_volumes`, `market_caps`  
- **Coin Identifiers**: `coin_id`, `symbol`, `name`  

---

## 🔍 Analysis Workflow

The analysis follows a structured workflow:

- Loading and merging data from multiple dates  
- Cleaning column names and converting data types  
- Aggregating and comparing prices across days  
- Visualizing price distributions and market caps  
- Sorting and filtering top cryptocurrencies by metrics  
- Creating comprehensive plots for:
  - **Price comparisons**
  - **Market capitalization distribution**
  - **Volume vs Market Cap correlations**

---

## 📊 Key Insights

- Top market cap coins include **Bitcoin**, **Ethereum**, and **Tether**, reflecting dominance in the space  
- Significant differences in market caps and volumes show market fragmentation  
- Correlation observed between market cap and price, especially for large-cap coins  
- High trading volume does not always correlate with high price or market cap (e.g., stablecoins)  
- Visual exploration helps identify outliers and emerging trends across coins

---

## 📁 Scripts & Outputs

- `Cryptocurrency Price & Market Data.ipynb`: Full workflow from data loading to final visualizations  
- Visual outputs include:
  - Bar plots of top coins by market cap
  - Histograms of price distributions
  - Scatter plots of volume vs market cap
  - Comparative tables of daily changes

---

## 🛠️ Libraries Used

- **Data Processing**: `pandas`, `numpy`  
- **Visualization**: `matplotlib`, `seaborn`  

---

## ✅ Usage

To run the project:

1. Clone this repository  
2. Place the CSV files in the root directory  
3. Open and run the Jupyter notebook `Cryptocurrency Price & Market Data.ipynb`  
4. Explore the insights from the visualizations and tables

---

## 🚀 Future Improvements

- Automate daily scraping to create a continuous time series  
- Include more features like supply, circulating coins, or social signals  
- Build a dashboard for interactive exploration  
- Explore forecasting with time series models for price prediction

---

## 👤 Author

**Rohit Shivhare**  
[LinkedIn](https://www.linkedin.com/in/rohit-shivhare-a857a4233/)  
*MSc Data Science – Brunel University, London*
