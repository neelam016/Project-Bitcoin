# Trader Behavior Insights

## 📌 Project Overview

This project analyzes the relationship between **Bitcoin market
sentiment** (Fear & Greed Index) and **trader behavior** using
historical trade-level execution data.\
The goal is to identify how sentiment impacts: - Profitability (PnL) -
Win rates - Leverage usage - Trading volume

The analysis helps uncover patterns that may improve trading strategies
and risk management.

------------------------------------------------------------------------

## 📂 Dataset

1.  **Trader Data**
    -   Source: Hyperliquid\
    -   Contains trade-level executions (PnL, leverage, size, etc.)
2.  **Market Sentiment Data**
    -   Source: Bitcoin Fear & Greed Index\
    -   Provides daily sentiment scores categorized as *Extreme Fear,
        Fear, Neutral, Greed, Extreme Greed*.

------------------------------------------------------------------------

## 🛠️ Methodology

-   Datasets were merged on the **date** column.
-   Sentiment values were aligned with daily trading activity.
-   Metrics such as PnL, win rate, and leverage were aggregated per
    sentiment category.
-   Statistical summaries and visualizations were created.

------------------------------------------------------------------------

## 📊 Key Findings

-   **Leverage:** Higher in "Greed" than "Fear".
-   **Win Rate:** Dropped during "Extreme Greed" (overconfidence
    effect).
-   **Trading Volume:** Spiked in "Extreme Fear" (panic
    selling/capitulation).
-   **Profitability:** Profitable traders reduced exposure in greedy
    markets.

------------------------------------------------------------------------

## 📑 Files in this Repository

-   `Assignment.ipynb` → Jupyter Notebook with analysis\
-   `ds_report.pdf` → Final report with insights\
-   `README.md` → Project documentation

------------------------------------------------------------------------

## 🚀 How to Run

1.  Clone this repository

    ``` bash
    git clone https://github.com/yourusername/trader-behavior-insights.git
    cd trader-behavior-insights
    ```

2.  Install dependencies

    ``` bash
    pip install -r requirements.txt
    ```

3.  Run the notebook

    ``` bash
    jupyter notebook Assignment.ipynb
    ```

------------------------------------------------------------------------

## 📈 Future Work

-   Backtest signals using Fear & Greed as a trading factor.
-   Incorporate **BTC price movements** for deeper context.
-   Add **order book depth data** for liquidity analysis.

------------------------------------------------------------------------

## 👩‍💻 Author

-   **Your Name**\
    B.Tech 3rd Year \| Data Science Enthusiast
