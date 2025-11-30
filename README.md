# Retail Revenue Analysis

[![🚀 Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/betklab/sales-analysis/blob/main/Analysis.ipynb)


This project analyzes regional daily revenue trends using anonymized retail transaction data.  
The analysis covers sales, returns, and net revenue across multiple locations over a six-day period.

## 📁 Project Structure

- **Analysis.ipynb** — Main notebook containing the full exploratory data analysis (EDA), visualizations, and insights.
- **plots/** — Directory where generated figures (e.g., revenue trend charts) are saved.
- **data/** — Folder for the source datasets (not included here unless provided separately).

## 📊 Dataset Description

The dataset contains **18,729 records** of retail transactions, including sales, returns, and revenue.  
It spans **2020-01-01 to 2020-01-06** and includes:

- `location` — Identifier for the store or region  
- `purchase_date` — Date of purchase  
- `purchase_id` — Transaction-level purchase ID  
- `product_code` — Product identifier  
- `quantity_sold` — Units sold  
- `quantity_returned` — Units returned  
- `revenue_after_returns` — Net revenue after returns  
- (`day_of_week` is added during processing)

### Ethical Considerations

**The dataset is fully anonymized and contains no private, sensitive, or confidential information.  
All identifiers have been removed or transformed to ensure that individuals or locations cannot be re-identified.**

## 🔍 Key Analysis Steps

The notebook includes:

- Data cleaning and preprocessing  
- Revenue aggregation by date, region, and day of week  
- Line-chart visualizations of regional revenue trends  
- Return-rate calculations  
- Identification of high-performing vs. underperforming locations  
- Recommendations based on observed patterns  

## 📈 Example Visualization

One of the plots generated:

- **Regional Daily Revenue Trend (Line Chart)**  
  - Shows each region’s net revenue over the six-day period  
  - Includes monetary formatting and day-of-week labels  
  - Saved as: `plots/regional_daily_revenue_trend.png`

## 🛠️ Requirements

To run the notebook, install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```