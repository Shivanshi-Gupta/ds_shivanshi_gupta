# ds_shivanshi_gupta
Market Sentiment vs Trader Behavior Analysis on Hyperliquid
# Hyperliquid Market Sentiment & Trader Behavior Analysis

## Objective
The objective of this project is to analyze how market sentiment (Fear vs Greed)
impacts trader behavior and performance on the Hyperliquid trading platform.
By combining Bitcoin sentiment data with historical trader data, we aim to
uncover patterns that can inform smarter and risk-aware trading strategies.

## Project Structure
ds_shivanshi_gupta/
├── notebook_1.ipynb
├── csv_files/
├── outputs/
└── README.md


## Methodology
- Loaded and cleaned both datasets.
- Standardized timestamps and aligned data at daily frequency.
- Engineered trader behavior metrics such as:
  - Daily PnL
  - Win rate
  - Trade frequency
  - Leverage usage
  - Long/short ratio
- Conducted comparative analysis between Fear and Greed regimes.
- Segmented traders based on leverage, frequency, and consistency.
- Generated actionable strategy recommendations.

## Key Insights
- Trader profitability and win rates are significantly higher during Greed regimes.
- High leverage traders experience larger drawdowns during Fear periods.
- Frequent traders outperform primarily during Greed phases, indicating momentum-driven strategies.

## Strategy Recommendations
- During Fear regimes, traders should reduce leverage exposure by 40–60% to minimize drawdowns.
- High-frequency trading strategies should be emphasized during Greed regimes when market momentum is stronger.

## How to Run
1. Upload the notebook to Google Colab.
2. Upload CSV files from `csv_files/`.
3. Run all cells sequentially.

## Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (optional)
