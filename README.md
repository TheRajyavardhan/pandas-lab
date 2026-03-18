# 📊 Pandas Lab

## 🚀 Overview

This repository documents my journey of learning **Pandas**, one of the most powerful Python libraries for **data analysis and data manipulation**.

Pandas is widely used in:

* Data Science
* Machine Learning
* Data Analysis
* Business Intelligence

---

## 📌 What is Pandas?

Pandas is a Python library that provides:

* **Series** → 1D data structure
* **DataFrame** → 2D table (like Excel)

It helps in:

* Cleaning data
* Analyzing data
* Transforming datasets
* Handling missing values

---

## 🧠 Topics Covered

### ✅ Basics

* Introduction to Pandas
* Series and DataFrame
* Creating datasets

### ✅ Data Handling

* Reading CSV files
* Viewing data (`head()`, `tail()`)
* Data selection (`loc`, `iloc`)

### ✅ Data Cleaning

* Handling missing values (`dropna()`, `fillna()`)
* Removing duplicates
* Changing data types

### ✅ Data Analysis

* Filtering data
* Sorting
* Value counts
* Unique values

### ✅ GroupBy Operations

* Aggregations (`sum`, `mean`, `count`)
* Multi-level grouping

### ✅ Advanced Operations

* Merging datasets (joins)
* Concatenation
* Pivot tables
* Crosstab

### ✅ Performance Techniques

* Vectorized operations
* Using `apply()`
* Working with large datasets

### ✅ Visualization

* Bar charts
* Line plots
* Histograms

---

## 🛠️ Installation

Install Pandas using pip:

```bash
pip install pandas
```

Also install matplotlib for visualization:

```bash
pip install matplotlib
```

---

## 📂 Example Code

```python
import pandas as pd

data = {
    "Name": ["Rohit", "Virat", "Dhoni"],
    "Runs": [12000, 13000, 10000]
}

df = pd.DataFrame(data)

print(df)

print(df["Runs"])
```

---

## 📈 Sample Operations

### Filter Data

```python
df[df["Runs"] > 11000]
```

### GroupBy

```python
df.groupby("Name")["Runs"].sum()
```

### Add Column

```python
df["Runs_with_bonus"] = df["Runs"] + 100
```

---

## 🎯 Goal

The goal of this repository is to:

* Build strong fundamentals in Pandas
* Prepare for real-world data analysis
* Move towards data science and machine learning

---

## 🔥 Future Plans

* Add real-world datasets
* Perform Exploratory Data Analysis (EDA)
* Integrate with visualization tools
* Build data science projects

---

## ⭐ Note

This repository is part of my continuous learning journey in **Data Science and Python development**.
