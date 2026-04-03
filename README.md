# 📊 Sales Data Analysis Project

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.1-red)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8-green)

## 📋 Overview
This project analyzes retail store sales data to extract insights about sales performance and profitability.

## 🎯 Key Results

### KPIs
| Metric | Value |
|--------|-------|
| Total Sales | $2,297,201 |
| Total Profit | $286,397 |
| Profit Margin | 12.47% |

### Insights
| # | Insight |
|---|---------|
| 1 | Technology category has highest sales |
| 2 | West region has highest sales |
| 3 | 50%+ discount causes losses |
| 4 | November & December are peak months |

## 📈 Visualizations
![Dashboard](images/dashboard.png)

## 💡 Recommendations
| # | Recommendation | Priority |
|---|----------------|----------|
| 1 | Set max discount to 30% | High |
| 2 | Focus marketing on West region | Medium |
| 3 | Increase inventory before November | Medium |

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
sales-data-analysis/
├── README.md
├── sales_analysis_final.ipynb
├── Superstore.csv
├── requirements.txt
└── images/
    └── dashboard.png