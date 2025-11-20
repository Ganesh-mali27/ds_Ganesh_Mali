# 📊 Bitcoin Market Sentiment vs Trader Behaviour – Analysis Project  
### Directory: ds_<candidate_name>

This repository contains the full analysis required for the assignment evaluating the relationship between **Bitcoin market sentiment** (Fear–Greed Index) and **Hyperliquid trader behaviour**.

All work follows the required submission structure and was completed entirely in **Google Colab**.

# 📁 Directory Structure

```
ds_Ganesh_Mali/
│
├── notebook_1.ipynb        # Your main Google Colab notebook
│
├── csv_files/              # Store all CSV outputs here
│   ├── fear_greed_index.csv
│   └── historical.csv
│   └── merged.csv
│
├── outputs/                # Store all visual outputs
│   ├── trades_per_sentiment_1.png
│   └── avg_pnl_sentiment_2.png
│   └── win_rate_sentiment_3.png
│   └── avg_USD_volume_sentiment_4.png
│   └── trade_count_sentiment&Side_5.png
│   └── trade_date_value_6.png
│   └── trade_date_dailyUSD_7.png
│   └── dailyUSD_dailyPnL_8.png
│   └── dailyTrades_dailyPnL_9.png
│
├── ds_report.pdf           # Final summarized PDF report
│
└── README.md               # Instructions + notes for reviewer
```

# 🎯 Objective

To evaluate how **trader actions** (profitability, volume, buy/sell patterns, risk-taking) correlate with **market sentiment** (Fear, Greed, Extreme Fear, Extreme Greed) using:

- **Fear–Greed Index data**
- **Hyperliquid trading history**

The analysis uncovers:
- How sentiment influences trader risk
- Profitability patterns across sentiment phases
- Market behaviour during volatile conditions
- Signals that can help traders make smarter decisions

---

# ▶️ Google Colab Notebook

Main Notebook:  
🔗 **[notebook_1](https://colab.research.google.com/drive/1UBphPXSlMyZyPFm8fd6FnDscqehMSbyL?usp=sharing)**


# 🛠️ Setup Instructions

## ✔ Option 1 — Run Using Google Colab (Recommended)

1. Open `notebook_1.ipynb` in Google Colab.
2. Upload the following raw datasets into Colab:
   - `historical_data.csv`
   - `fear_greed_index.csv`
3. Ensure the notebook paths match the uploaded filenames.
4. Run all cells in sequence.

## ✔ Option 2 — Run Locally

### Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn


