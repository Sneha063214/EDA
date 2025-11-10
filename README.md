
# Zomato Data Analysis

## Overview

This project performs **Exploratory Data Analysis (EDA)** on the Zomato dataset to uncover insights about restaurants, ratings, and customer behavior across different countries. The analysis includes data cleaning, merging datasets, and generating meaningful visualizations.

---

## Files

* **`new-data.ipynb`** – Data loading, cleaning, and preprocessing.
* **`eda-exploratory.ipynb`** – Exploratory analysis and visualizations.

---

## Objectives

* Handle and visualize missing values.
* Explore numerical and categorical variables.
* Analyze relationships between features.
* Visualize patterns in ratings, cities, and countries.

---

## Tools and Libraries

* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Datasets

1. **zomato.csv** – Contains restaurant details such as name, location, cuisines, ratings, and delivery options.
2. **Country-Code.xlsx** – Maps country codes to country names.

Both datasets are read from the Kaggle input directory.

---

## Key Steps

### 1. Data Preparation

* Loaded datasets using Pandas.
* Merged restaurant data with country codes.
* Checked dataset info, shape, and missing values.

### 2. Data Cleaning

* Handled null entries.
* Visualized missing data using a Seaborn heatmap.

### 3. Exploratory Analysis

* Top countries and cities using Zomato.
* Distribution of aggregate ratings.
* Relationship between rating color and country.
* Online delivery availability by country.

---

## Insights

* Zomato is most active in **India**, followed by **USA** and **UK**.
* High-rated restaurants are fewer but have strong customer engagement.
* Online delivery is mainly used in **India** and **UAE**.
* Several countries have many restaurants with no ratings.

---

## How to Run

1. Download the notebooks and datasets.
2. Open in **Jupyter Notebook** or **Google Colab**.
3. Run all cells sequentially.

---

## Author

**Sneha Sharma**
Data Science and AI Enthusiast


