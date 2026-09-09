# Exploratory Data Analysis — Univariate & Multivariate Analysis

A hands-on EDA project demonstrating a wide range of data visualization techniques for understanding single variables (univariate) and relationships between variables (bivariate/multivariate), using the Titanic, Tips, Flights, and Iris datasets.

---

## 📌 Project Overview

This notebook is a practical walkthrough of exploratory data analysis techniques in Python, covering:

- **Univariate Analysis** — examining one variable at a time (categorical and numerical)
- **Multivariate Analysis** — examining relationships between two or more variables

The goal is to build intuition for *which plot to use for which data type*, a foundational skill for any data analysis or machine learning project.

---

## 🗂️ Datasets Used

| Dataset | Source | Used For |
|---|---|---|
| Titanic | `titanic.csv` (local file) | Categorical & numerical univariate analysis, bivariate analysis |
| Tips | `seaborn.load_dataset('tips')` | Scatter plot (numerical vs numerical) |
| Flights | `seaborn.load_dataset('flights')` | Pivot table & cluster map |
| Iris | `seaborn.load_dataset('iris')` | Pair plot |

> Note: `titanic.csv` is loaded from a local path in the notebook (`C:\Users\DELL\Documents\titanic.csv`). Update this path to wherever you keep the dataset, or download it from a public source such as [Kaggle's Titanic dataset](https://www.kaggle.com/c/titanic/data).

---

## 📊 Techniques Covered

### 1. Univariate Analysis
- **Categorical data:** Count plot (`sns.countplot`), Pie chart (`value_counts().plot(kind='pie')`)
- **Numerical data:** Histogram (`plt.hist`), Distribution plot (`sns.displot`), Box plot (`sns.boxplot`)
- Basic statistics: min, max, mean

### 2. Multivariate Analysis
- **Numerical vs Numerical:** Scatter plot (with hue, style, and size encoding)
- **Categorical vs Categorical:** Bar plot
- **Numerical vs Categorical:** Box plot, Distribution plot (comparing survival groups)
- **Multiple variables:** Pair plot (Iris dataset)
- **Aggregated data:** Pivot table + Cluster map (Flights dataset)

---

## 🛠️ Tech Stack

- Python
- pandas, numpy
- matplotlib
- seaborn

---

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Update the Titanic dataset path in the notebook to match your local file location.
3. Open `EDA_using_univariate_analysis.ipynb` in Jupyter Notebook / JupyterLab and run all cells top to bottom.

---

## 📁 Project Structure

```
├── EDA_using_univariate_analysis.ipynb   # Main analysis notebook
├── requirements.txt                       # Python dependencies
└── README.md
```

---

## ✍️ Author

Built as a practice project to strengthen exploratory data analysis and data visualization skills — a foundational step before moving into feature engineering and machine learning modeling.
