# Bitcoin Market Sentiment vs Trader Performance Analysis

## Objective

The goal of this project was to analyze the relationship between Bitcoin market sentiment and trader performance using:

- Bitcoin Fear & Greed Index Dataset
- Hyperliquid Historical Trader Dataset

The datasets were merged using the date column and analyzed using Python.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Performed

- Data Cleaning
- Date Conversion
- Dataset Merging
- Average Profit Analysis
- Win Rate Analysis
- Trade Count Analysis
- Long vs Short Analysis
- Top Trader Analysis
- Correlation Analysis

---

## Key Results

### Average Closed PnL

| Sentiment     | Average Closed PnL |
| ------------- | ------------------ |
| Extreme Greed | 67.89              |
| Fear          | 54.29              |
| Greed         | 42.74              |
| Extreme Fear  | 34.54              |
| Neutral       | 34.31              |

### Win Rate (%)

| Sentiment     | Win Rate |
| ------------- | -------- |
| Extreme Greed | 46.49%   |
| Fear          | 42.08%   |
| Neutral       | 39.70%   |
| Greed         | 38.48%   |
| Extreme Fear  | 37.06%   |

### Trade Count

| Sentiment     | Trades |
| ------------- | ------ |
| Fear          | 61,837 |
| Greed         | 50,303 |
| Extreme Greed | 39,992 |
| Neutral       | 37,686 |
| Extreme Fear  | 21,400 |

---

## Findings

- Extreme Greed produced the highest average profit.
- Extreme Greed produced the highest win rate.
- Fear periods had the highest trading activity.
- Extreme Fear showed the weakest trader performance.
- Market sentiment appears to influence trader performance and trading activity.

---

## Project Structure

```text
bitcoin-sentiment-analysis/

├── data/
├── notebooks/
├── visuals/
├── report/
├── README.md
└── requirements.txt
```

## Conclusion

The analysis shows that trader performance changes across different market sentiment conditions. Extreme Greed periods showed stronger profitability and win rates, while Extreme Fear periods showed weaker performance.
