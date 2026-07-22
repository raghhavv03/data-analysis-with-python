# Data Analysis with Python

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/pandas-2.0%2B-150458.svg)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/numpy-1.24%2B-013243.svg)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/matplotlib-3.7%2B-11557c.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/seaborn-0.12%2B-3776ab.svg)](https://seaborn.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A structured, hands-on curriculum and practical reference for data analysis with Python. This repository covers the complete data analysis lifecycle — from raw data collection and web scraping to data wrangling, exploratory data analysis (EDA), and statistical visualization.

---

## 📌 Features & Highlights

- **Interactive Jupyter Notebooks**: Step-by-step tutorials covering foundational tools: NumPy, Pandas, Matplotlib, Seaborn, and BeautifulSoup.
- **Real-World Datasets**: Practice with structured tabular data (CSV/JSON), messy raw records, and HTML pages.
- **Hands-On Assignments**: Practical exercises with solutions to test understanding of real data manipulation scenarios.
- **Curated Lecture Notes**: PDF quick-reference guides accompanying major modules.

---

## 📂 Repository Structure

```text
data-analysis-with-python/
├── notebooks/                     # Interactive tutorial notebooks
│   ├── 01_thinking_data.ipynb
│   ├── 02_numpy_tutorial.ipynb
│   ├── 03_pandas_tutorial_part_1.ipynb
│   ├── 04_pandas_tutorial_part_2.ipynb
│   ├── 05_data_collection.ipynb
│   ├── 06_matplotlib_tutorial_part_1.ipynb
│   ├── 07_matplotlib_tutorial_part_2.ipynb
│   └── 08_seaborn_tutorial.ipynb
├── assignments/                   # Exercises, practice questions & solutions
│   ├── 01_pandas_assignment.pdf
│   ├── 02_pandas_assignment_solution.ipynb
│   ├── 03_data_collection_practice_question.ipynb
│   ├── 04_web_scraping_practice_question.ipynb
│   ├── 05_matplotlib_practice_question.ipynb
│   ├── 06_data_visualization_assignment.pdf
│   └── 07_data_visualization_assignment_solution.ipynb
├── notes/                         # Module reference PDFs
│   ├── 01_numpy_notes.pdf
│   ├── 02_pandas_notes.pdf
│   ├── 03_matplotlib_notes.pdf
│   └── 04_seaborn_notes.pdf
└── data/                          # Raw & processed datasets
    ├── cleaned-data/              # Processed CSV outputs
    │   ├── countries_data.csv
    │   └── quotes_data.csv
    ├── scraped-data/              # Raw HTML files saved during scraping
    │   └── data_1.html, quotes_1.html ... quotes_10.html
    ├── employee_data.csv / employee_data.json
    ├── global_air_quality.csv
    ├── iris.csv
    ├── raw_data.csv
    ├── store_data.json
    └── titanic_dataset.csv
```

---

## 📚 Curriculum Breakdown

| Module | Topic | Notebook / Reference | Description |
| :--- | :--- | :--- | :--- |
| **01** | **Thinking Data** | [`01_thinking_data.ipynb`](notebooks/01_thinking_data.ipynb) | Data mindset, structured problem-solving, and basic data processing workflows. |
| **02** | **NumPy Foundations** | [`02_numpy_tutorial.ipynb`](notebooks/02_numpy_tutorial.ipynb) | Multi-dimensional arrays, vectorization, indexing, slicing, and broadcasting. |
| **03-04** | **Pandas Deep Dive** | [`03_pandas_tutorial_part_1.ipynb`](notebooks/03_pandas_tutorial_part_1.ipynb)<br>[`04_pandas_tutorial_part_2.ipynb`](notebooks/04_pandas_tutorial_part_2.ipynb) | Series, DataFrames, filtering, missing data handling, grouping, merging, and reshaping. |
| **05** | **Data Collection & Scraping** | [`05_data_collection.ipynb`](notebooks/05_data_collection.ipynb) | API consumption, HTML parsing with BeautifulSoup, and saving web datasets. |
| **06-07** | **Matplotlib Visualizations** | [`06_matplotlib_tutorial_part_1.ipynb`](notebooks/06_matplotlib_tutorial_part_1.ipynb)<br>[`07_matplotlib_tutorial_part_2.ipynb`](notebooks/07_matplotlib_tutorial_part_2.ipynb) | Figure & Axes architecture, line/bar plots, scatter plots, histograms, and customization. |
| **08** | **Seaborn Statistical Plots** | [`08_seaborn_tutorial.ipynb`](notebooks/08_seaborn_tutorial.ipynb) | Categorical plots, distribution plots, pairplots, heatmaps, and styling themes. |

---

## 🛠️ Quick Start & Usage

### 1. Prerequisites & Environment Setup

Ensure Python 3.8+ is installed on your system. Clone the repository and set up a virtual environment:

```bash
# Clone the repository
git clone https://github.com/your-username/data-analysis-with-python.git
cd data-analysis-with-python

# Create and activate virtual environment
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install jupyter pandas numpy matplotlib seaborn beautifulsoup4 requests lxml
```

### 2. Running the Notebooks

Launch Jupyter Notebook or JupyterLab from the root directory:

```bash
jupyter notebook
```

> **Note**: Always launch Jupyter from the root directory (`data-analysis-with-python`) so relative file paths to datasets in `data/` resolve correctly.

---

## 📊 Datasets Included

- **`iris.csv`**: Classic multi-class classification dataset for feature exploration.
- **`titanic_dataset.csv`**: Demographic and survival data for EDA and data cleaning practice.
- **`global_air_quality.csv`**: Environmental data for time-series and geographical metrics.
- **`employee_data.csv / .json`**: Custom employee records used to practice format conversion and cleaning.
- **`store_data.json`**: Nested JSON data for flattening and relational table conversion.

---

## 🤝 License

Distributed under the MIT License. See `LICENSE` for details.
