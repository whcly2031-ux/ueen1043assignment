# UEEN1043 Assignment - Transaction Analysis and Visualisation
**Group 17 (P2)**

## 👤 Group Members
* **CHIEW WEI HENG** (2304580)
* **TAN POULNY** (2303710)

---

## 📝 Project Overview
This Python-based analytical tool is designed to process, clean, and visualize financial transaction data. The system integrates multiple datasets (transactions, merchant types, and fraud records) to identify patterns in fraudulent behavior and provide statistical insights through high-resolution graphical visualizations.

## 🛠 Key Features
* **Object-Oriented Design:** Utilizes Python classes and **Private Access Modifiers** (Encapsulation) to ensure data integrity.
* **Robust Data Cleaning:** * Filters out transactions with errors.
    * Handles missing values (NaN) across critical columns (`id`, `mcc`, `amount`).
    * Sanitizes currency strings and converts them to numeric formats.
    * Removes duplicate records, ensuring only the most recent transaction is retained.
* **Data Integration:** Merges disparate CSV files using `pandas` to create a unified analytical dataset.
* **Automated Visualization:** Generates five distinct plots to reveal trends in fraud rates, business types, and transaction timing.

---

## 📊 Visualizations Generated
The script automatically generates and saves the following high-quality PNG charts (500 DPI):
1. **Average Transaction Per Date:** A line chart showing daily volume trends.
2. **Fraud Rate by Hour of Day:** A bar chart identifying high-risk time windows for fraud.
3. **Fraud Distribution:** A pie chart showing the ratio of Legitimate vs. Fraudulent vs. Unknown transactions.
4. **Debit vs Credit by Fraud:** A stacked bar chart analyzing the relationship between transaction types and fraud status.
5. **Top 5 Fraud Business Types:** A horizontal bar chart identifying industries most targeted by fraudulent activity.

---

## 🚀 Getting Started

### Prerequisites
Ensure you have Python installed along with the following libraries:
```bash
pip install pandas matplotlib
