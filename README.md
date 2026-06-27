# Data Analysis with Python

A structured collection of notebooks, assignments, and notes covering the core toolkit for data analysis in Python — from array operations and dataframes to web scraping and visualization. This repository documents my learning journey through practical, hands-on notebooks.

## Topics Covered

- NumPy fundamentals (arrays, indexing, vectorized operations)
- Pandas (Series, DataFrames, cleaning, transformation, aggregation)
- Data collection & web scraping (BeautifulSoup, HTML parsing)
- Data visualization with Matplotlib
- Statistical visualization with Seaborn
- Working with real-world datasets (CSV, JSON, scraped HTML)

## Repository Structure

```
data-analysis-with-python/
├── notebooks/        # Topic-wise Jupyter notebooks (NumPy, Pandas, scraping, Matplotlib, Seaborn)
├── assignments/       # Practice questions, solutions, and assignment PDFs
├── notes/             # Lecture notes (PDF) for NumPy, Pandas, Matplotlib, Seaborn
└── data/              # Datasets used across notebooks (CSV, JSON, scraped HTML)
    ├── cleaned_data/   # Processed/cleaned datasets
    └── scraped_data/   # Raw HTML pulled during web scraping exercises
```

## Datasets Used

- `iris.csv`, `titanic_dataset.csv`, `global_air_quality.csv` — public datasets for analysis practice
- `employee_data.csv/.json`, `store_data.json`, `raw_data.csv` — custom datasets for cleaning and transformation exercises
- `scraped_data/` — HTML pages collected via web scraping exercises

## How to Use

Clone the repository and open the notebooks in Jupyter:

```bash
git clone <repo-url>
cd data-analysis-with-python
jupyter notebook notebooks/01_thinking_data.ipynb
```

Run notebooks from the project root so relative paths to the `data/` folder resolve correctly.

## Purpose

This repository serves as a personal reference and practice log for building practical data analysis skills in Python — covering the full workflow from data collection and cleaning to exploratory analysis and visualization.
