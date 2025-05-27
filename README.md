# Crypto Market Cluster Analysis

Jupyter Notebook for advanced clustering and segmentation of the entire Binance USDT-crypto universe by behavioral similarity and dependence on Bitcoin.


# Project Goal

- Segment and visualize all USDT crypto assets from Binance by statistical similarity and beta to BTC.
- Find clusters: groups of coins that move together, BTC-followers, and truly independent or anti-Bitcoin tokens.
- Highlight outliers (anomalies) — assets fundamentally different from the market.
- Automate market exploration for quant research, trading ideas, and portfolio construction.


# Contents

- Loading historical OHLCV data for all Binance USDT-pairs (up to 1000 days)
- Feature engineering: calculating volatility, RSI, beta vs BTC, volume, and more
- Modern clustering:
    - UMAP for dimensionality reduction and visualization
    - HDBSCAN and KMeans for cluster detection and anomaly search
- 2D market maps, outlier detection, identification of the most independent altcoins
- Practical blocks: filtering, cluster analysis, exporting results


# How to Run

1. **Clone or download** the repository and open `crypto_market_cluster_analysis.ipynb` in [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/).

2. **Install dependencies:**
   ```bash
   pip install pandas numpy matplotlib ta umap-learn hdbscan requests
