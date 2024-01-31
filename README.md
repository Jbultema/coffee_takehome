# Coffee Item Classification and Pairing Analysis

## Overview
This project focuses on analyzing a dataset of food and beverage orders to identify coffee-related items and understand common pairings with coffee. The goals are:
1. Determine the sales of coffee-items
2. Developing an upselling feature that recommends items to pair with coffee orders.

## Features
- Identification of coffee items using keyword-based filtering and NLP modeling.
- Integration of text and numerical features for enhanced classification.
- Analysis of item pairings with coffee to inform upselling strategies.

## Approach
The project involves several key steps:
1. **Keyword-Based Filtering**: Developing a heuristic to identify coffee items based on keywords.
2. **Feature Engineering**: Combining text data with numerical features like price and quantity for improved model performance.
3. **NLP Modeling**: Using machine learning models to classify items as coffee or non-coffee based on item names and descriptions.
4. **Pairing Analysis**: Analyzing order data to determine common pairings with coffee.

## Dataset
The dataset includes various fields such as `ORDER_ID`, `ITEM_NAME`, `ITEM_DESCRIPTION`, `ITEM_PRICE`, and `ITEM_QUANTITY`. It represents orders from a food ordering platform, focusing on a single metropolitan area over one month.

## Prerequisites
- Python 3.x
- Pandas
- Scikit-learn
- Numpy

## Author
Jarred Bultema, PhD