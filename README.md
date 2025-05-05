
# 📊 Market Basket Analysis with Apriori Algorithm

This project implements a **Market Basket Analysis (MBA)** system using the **Apriori algorithm** to identify frequent itemsets and discover purchasing patterns within a retail transaction dataset. It helps in understanding which products are often bought together, aiding decisions in product placement, inventory management, and marketing strategies.

## 💡 Objectives

* Load and preprocess transaction data from a CSV file.
* Implement the Apriori algorithm from scratch in Python.
* Identify frequent itemsets for various minimum support thresholds.
* Visualize the relationship between support values and the number of frequent itemsets discovered.

## 🛠️ Tools & Technologies

| Language/Tool | Purpose                                        |
| ------------- | ---------------------------------------------- |
| Python        | Core programming language for implementation   |
| Pandas        | Data loading and preprocessing                 |
| Matplotlib    | Visualization of itemset frequency vs. support |
| Google Colab  | Cloud-based notebook for running experiments   |

## 📁 Dataset

* The dataset is a CSV file containing retail transactions.
* Each row represents a list of products purchased in a single transaction.

## 🔍 Key Features

* **Data Preprocessing**: Parses string-formatted product lists into Python lists.
* **Apriori Algorithm**:

  * Frequent 1-itemset generation (`L1`)
  * Candidate generation and pruning for higher-order itemsets (`Ck`, `Lk`)
  * Support counting and filtering based on a minimum support threshold
* **Parameter Tuning**: Automatically tests various minimum support values to evaluate algorithm sensitivity.
* **Visualization**: Plots the number of frequent itemsets discovered for each value of minimum support.

## 📈 Output

* Frequent itemsets for each support level (L1, L2, L3…)
* Insights into optimal support values
* A line chart showing how the number of itemsets changes with support thresholds

