# Crime Heatmap Analysis (Python)

A crime data analysis project using Python and Jupyter Notebook to visualize **high-crime hours** and **geographical crime density** with interactive heatmaps.

- Dataset: San Francisco Crime Data (884K+ rows)
- Time and location-based heatmap visualization
- Structured preprocessing pipeline
- Data exploration with Pandas & Jupyter Notebook

[![Status](https://img.shields.io/badge/status-active-success)](https://github.com/AriqF1/heatmap_criminal)
[![License](https://img.shields.io/badge/license-MIT-blue)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.10+-blue)](https://www.python.org/)

## Features

- Preprocessing of crime data from Kaggle
- Duplicate detection and cleaning for large datasets
- Crime frequency analysis by hour and district
- Heatmap of crime locations using coordinates (X, Y)
- Professional and modular folder structure

## Requirements

- Python 3.10+
- Pandas, NumPy, Seaborn, Matplotlib, Jupyter, Folium

Install all dependencies with:

```bash
pip install -r requirements.txt
```

## Getting Started

Clone The Repository

```bash
git clone https://github.com/AriqF1/heatmap_criminal.git
cd heatmap_criminal
```

## Folder Structure

```bash
heatmap-kriminal/
├── data/
│   ├── 01_raw/            # Raw data from Kaggle
│   ├── 02_interim/        # Cleaned data
│   └── 03_processed/      # Analysis-ready data
├── notebooks/             # Jupyter Notebooks for EDA & visualization
├── scripts/               # Python scripts for data pipeline
├── visualization/         # Generated heatmaps and charts
├── reports/               # Final analysis, charts, and documentation
├── README.md
└── requirements.txt
```
