# 📈 Stock Price Prediction using Unsupervised Learning

This project explores **unsupervised machine learning techniques** to analyze and predict stock price movements.  
Instead of relying on labeled outcomes (like "buy/sell"), the model uses **clustering and feature engineering** to discover patterns and behaviors within stock market data.  

---

## 🔍 Project Overview
- ✅ Download historical stock price data (Yahoo Finance / other APIs).  
- ✅ Generate technical indicators (returns, volatility, RSI, MACD, etc.).  
- ✅ Apply **Unsupervised Learning (Clustering)** to group similar stocks.  
- ✅ Analyze market behavior patterns and visualize results.  
- ✅ Compare performance with baseline market indices (like S&P 500 / SPY).  

This approach is useful for:
- Identifying hidden structure in stock movements.  
- Grouping stocks with similar risk/return profiles.  
- Building **data-driven trading strategies** without explicit labels.  

---

## 🛠️ Tech Stack
- **Python 3.10+**  
- **Jupyter Notebook** (for experiments)  
- **Libraries**:
  - `pandas`, `numpy` → Data manipulation  
  - `matplotlib`, `seaborn` → Visualization  
  - `scikit-learn` → Clustering (KMeans, PCA, etc.)  
  - `statsmodels` → Statistical analysis  
  - `PyPortfolioOpt` → Portfolio optimization  

---

## 📂 Project Structure
unsupervised/
│── Unsupervised_learning.ipynb # Main notebook
│── README.md # Project documentation
│── requirements.txt # Dependencies (to be added)
└── data/ # (Optional) Store raw/processed datasets


---

## 🚀 How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/srikaranrao/Stock-price-prediction-using-Unsupervised-learning.git
   cd Stock-price-prediction-using-Unsupervised-learning

Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook Unsupervised_learning.ipynb

📊 Key Results

Stocks grouped into distinct clusters with similar return-volatility profiles.

Visualization of clusters and stock behavior.

Insights for potential portfolio construction and strategy design.

(Add plots from your notebook here as images for better presentation — e.g., cluster plots, return graphs.)

🌍 Real-World Applications

📌 Grouping stocks into sectors/factors beyond traditional industry classifications.

📌 Identifying momentum vs. mean-reversion stock behaviors.

📌 Feeding clusters into portfolio optimization for diversification.

🔮 Future Improvements

Add dimensionality reduction (PCA, t-SNE, UMAP) for better visualization.

Explore other clustering methods (DBSCAN, Hierarchical).

Integrate live data feeds for real-time clustering.

Backtest clustering-based strategies on historical data.