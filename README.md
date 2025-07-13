# Financial-Engineering-Assignment-1  
“Assignment 1 for Financial Engineering course, focused on BTC analysis”

## Overview

This repository contains my submission for **Financial Engineering Assignment 1**, which analyzes historical Bitcoin (BTC) data to build predictive models using lagged price and volume features. The assignment explores classification techniques, XGBoost, to forecast the direction of BTC price movement. Key performance metrics and visualizations such as confusion matrix and ROC curve are included.

---

## Files Included


- **Financial_Engineering_Assignment_1_Hirayama_BTC.ipynb** – Main Jupyter notebook with analysis code, modeling, and commentary.
- **Financial_Engineering_Assignment_1_Hirayama_BTC.pdf** – Exported PDF report version for assignment submission.
- **btc_historical_data.parquet** – Cleaned raw historical BTC pricing data.
- **btc-with-computed-features.xlsx** – Excel file containing BTC features used in modeling.

---

## Instructions to Run

1. **Clone the repository:**

```bash
git clone https://github.com/genchan0218/Financial-Engineering-Assignment-1.git
cd Financial-Engineering-Assignment-1
```

2. **Install required Python packages:**

Ensure you have the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost yfinance polars
```

3. **Launch Jupyter Notebook:**

```bash
jupyter notebook BTC_XGBoost_Upgrade_Genki_Hirayama.ipynb
```

4. **Run the notebook:**

Execute all cells sequentially to reproduce the analysis and model outputs. You may modify parameters such as lag window or model hyperparameters to test alternate configurations.

---

## Use of AI Assistants

I made use of AI tools such as ChatGPT to assist with the following:
1. Debugging and optimizing Python code related to modeling and feature engineering  
2. Proofreading markdown content, code documentation, and summary sections  
3. Refining descriptions for charts, confusion matrices, and ROC metrics  
4. Explaining advanced statistical concepts and guiding model selection

