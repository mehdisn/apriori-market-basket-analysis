# Apriori Market Basket Analysis

This project implements the **Apriori algorithm** to perform market basket analysis. It identifies frequent itemsets and generates association rules based on a given dataset. The output includes rules that indicate item co-occurrences, useful for understanding customer purchasing behavior.

## Table of Contents
- [Features](#features)
- [Dataset](#dataset)
- [Results](#results)

## Features
- **Frequent Itemset Mining**: Identifies frequently purchased items using the Apriori algorithm.
- **Association Rules Generation**: Extracts rules with minimum support and confidence thresholds.
- **Customizable Parameters**: Users can modify the support and confidence values.
- **CSV Export**: Saves the generated rules into a CSV file for further analysis.

## Dataset
The project uses a sample dataset (`msnbc990928.txt`), where:
- Each row represents a transaction.
- Each element in a row corresponds to an item ID.
- The algorithm converts these transactions into a binary matrix for analysis.

## Results
The output will display:
. Frequent itemsets discovered from the dataset.
. Association rules in the form of:
    `{item1, item2} => {item3}`
. A CSV file containing rules and their corresponding confidence scores.
