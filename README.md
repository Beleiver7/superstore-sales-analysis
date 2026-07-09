# 🛒 Superstore Sales Analysis — End-to-End Data Analytics Project

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green?logo=pandas)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange?logo=mysql)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-red)
![Seaborn](https://img.shields.io/badge/Seaborn-0.x-purple)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow?logo=jupyter)

---

## 📌 Project Overview

This is a complete end-to-end **Data Analytics project** on a US-based retail store's sales data (2015–2018).  
The goal was to analyze sales performance, identify profitable segments, and uncover the impact of discounts on profitability — all from scratch as a beginner transitioning into Data Analytics.

---

## 🎯 Business Questions Answered

- 📍 Which **region** generates the highest sales and profit?
- 📦 Which **product category** is most profitable?
- 🏷️ Does giving **high discounts** always lead to more revenue?
- 📅 Which **months** have the highest and lowest sales?
- 🚚 How many days does **shipping** take on average?
- 💸 Which sub-categories are actually **losing money**?

---

## 📊 Dataset

| Property | Details |
|---|---|
| Source | [Kaggle — Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) |
| Rows | 9,994 orders |
| Columns | 21 (+ 1 engineered feature) |
| Period | January 2015 — December 2018 |
| Region | USA (East, West, Central, South) |

---

## 🔍 Key Insights Discovered

### 📍 Region Analysis
| Region | Total Sales | Total Profit | Avg Discount |
|---|---|---|---|
| 🥇 West | $725,457 | $108,418 | 10.9% |
| 🥈 East | $678,781 | $91,522 | 14.5% |
| 🥉 Central | $501,239 | $39,706 | **24%** ⚠️ |
| South | $391,721 | $46,749 | 14.7% |

> 💡 **Central region gives the highest discounts (24%) resulting in the lowest profit despite being 3rd in sales!**

---

### 📦 Category Analysis
| Category | Total Sales | Profit Margin |
|---|---|---|
| 🥇 Technology | $836,154 | 17.40% |
| 🥈 Office Supplies | $719,047 | 17.04% |
| ⚠️ Furniture | $741,999 | **2.49%** |

> 💡 **Furniture has the 2nd highest sales but almost ZERO profit margin — high discounts + shipping costs are killing profitability!**

---

### 🏷️ Discount vs Profit
> 💡 **Discount above 20% almost guarantees a loss. Orders with 0% discount earned up to $8,399 profit!**

---

### 📅 Sales Trend
> 💡 **Sales spike every November-December (holiday season) and drop lowest in February — suggesting seasonal inventory and staffing strategies.**

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.12 | Core programming language |
| Pandas | Data manipulation & analysis |
| Matplotlib | Data visualization |
| Seaborn | Advanced visualizations |
| MySQL 8.0 | Database storage & SQL queries |
| Jupyter Notebook | Interactive development environment |
| mysql-connector-python | Python-MySQL integration |

---

## 📁 Project Structure

```
superstore-sales-analysis/
│
├── 📓 Superstore_EDA.ipynb          ← Main analysis notebook
├── 📊 Sample - Superstore.csv       ← Dataset
├── 📋 Python_DataAnalytics_Superstore.txt  ← Commands cheat sheet
└── 📄 README.md                     ← Project documentation
```

---

## 🚀 How to Run This Project

### Prerequisites
```bash
pip install pandas matplotlib seaborn mysql-connector-python jupyter
```

### Steps
1. Clone this repository:
```bash
git clone https://github.com/Beleiver7/superstore-sales-analysis.git
```

2. Navigate to the folder:
```bash
cd superstore-sales-analysis
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `Superstore_EDA.ipynb` and run all cells!

---

## 📈 Project Phases

- [x] **Phase 1** — Data Loading & Exploration
- [x] **Phase 2** — Data Cleaning (missing values, duplicates, date formatting)
- [x] **Phase 3** — Feature Engineering (Shipping Days column)
- [x] **Phase 4** — Exploratory Data Analysis (Region, Category, Sub-Category)
- [x] **Phase 5** — Data Visualization (5 charts)
- [x] **Phase 6** — MySQL Database Integration
- [x] **Phase 7** — SQL Query Validation

---

## 👨‍💻 About Me

**Prateek Sharma**  
NOC Engineer @ Reliance Jio | Transitioning to Data Analytics  
📧 prateeksharma8764@gmail.com  
🐙 GitHub: [Beleiver7](https://github.com/Beleiver7)

---

## ⭐ If you found this project helpful, please give it a star!
