<div align="center">

# 📊 Pandas Data Analysis & Data Cleaning Labs

### Practical Python notebooks for data exploration, transformation, and preprocessing

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

**[Explore Notebooks](#-notebooks) · [Getting Started](#-getting-started) · [Skills Demonstrated](#-skills-demonstrated)**

</div>

---

## 🔎 Overview

This repository brings together hands-on **Python and Pandas** exercises focused on essential data analysis workflows: exploring datasets, computing descriptive statistics, selecting and modifying records, and handling missing values.

The notebooks document practical learning in **data manipulation**, **exploratory data analysis (EDA)**, and **data preprocessing**. Each notebook can be explored independently.

## 📚 Notebooks

| Notebook | Focus | Topics |
|---|---|---|
| [**Summary Functions & Aggregations**](./Pandas_summary_functions_and_aggregations%20.ipynb) | Descriptive analysis | Dataset summaries, statistical measures, counts, and aggregation |
| [**Indexing, Selection & Editing**](./books.ipynb) | Data manipulation | DataFrame indexing, row and column selection, filtering, and updating values |
| [**Handling Missing Data**](./Pandas_handling_missing_data.ipynb) | Data cleaning | Detecting null values, examining missingness, removing incomplete entries, and filling missing values |

> **Note:** The links above use the filenames currently present in this repository, including the space before `.ipynb` in the summary notebook filename.

### 01 · Summary Functions & Aggregations

Practice generating quick insights from tabular data using common Pandas summary operations, such as `describe()`, `mean()`, and `count()`, and exploring aggregation techniques.

**Notebook:** [`Pandas_summary_functions_and_aggregations .ipynb`](./Pandas_summary_functions_and_aggregations%20.ipynb)

### 02 · Indexing, Selection & Editing

Explore how to access, filter, and update data in a Pandas DataFrame. Topics include positional selection with `iloc`, conditional filtering, and editing selected values.

**Notebook:** [`books.ipynb`](./books.ipynb)

### 03 · Handling Missing Data

Work through common data-quality tasks: locating null values, counting missing entries, comparing approaches to dropping incomplete records, and filling missing values where appropriate.

**Notebook:** [`Pandas_handling_missing_data.ipynb`](./Pandas_handling_missing_data.ipynb)

## 🛠️ Tech Stack

| Tool | Role |
|---|---|
| **Python 3** | Programming language |
| **Pandas** | DataFrames, data cleaning, and analysis |
| **NumPy** | Numerical operations |
| **Jupyter Notebook** | Interactive code, outputs, and explanations |

## 📁 Repository Structure

```text
pandas-data-analysis/
├── Pandas_handling_missing_data.ipynb
├── Pandas_summary_functions_and_aggregations .ipynb
├── books.ipynb
└── README.md
```

## 🚀 Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/Mansorri/pandas-data-analysis.git
cd pandas-data-analysis
```

**2. (Recommended) Create a virtual environment**

```bash
python -m venv .venv
```

Activate it on **Windows (PowerShell)**:

```powershell
.venv\Scripts\Activate.ps1
```

Or on **macOS / Linux**:

```bash
source .venv/bin/activate
```

**3. Install the main dependencies**

```bash
python -m pip install pandas numpy notebook
```

**4. Start Jupyter Notebook**

```bash
jupyter notebook
```

Open any `.ipynb` file to explore its code and outputs. Some notebooks may require additional packages or data files depending on their individual cells.

## 💡 Skills Demonstrated

- Exploring and understanding tabular datasets
- Calculating descriptive statistics and aggregations
- Selecting, filtering, and editing DataFrame values
- Identifying and handling missing data
- Organizing reproducible analysis in Jupyter notebooks

## 🎯 Learning Goals

The purpose of this repository is to strengthen the foundations needed for more advanced work in **data analytics**, **data science**, and **machine learning**, with an emphasis on readable, hands-on Python practice.

## 👩‍💻 Maintainer

**[Mansorri](https://github.com/Mansorri)** · [View repository](https://github.com/Mansorri/pandas-data-analysis)

---

<div align="center">

*Built as a practical learning portfolio for Python-based data analysis.*

⭐ If this repository is useful, consider giving it a star.

</div>
