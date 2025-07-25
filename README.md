# Data_Analytics_toolkit


## Overview
A Python-based automated pipeline to streamline data collection, cleaning, exploratory analysis, visualization, and results export—structured as modular scripts for flexibility and maintainability.


![word-tree-figure](https://github.com/user-attachments/assets/0490e561-c4bb-479f-aea0-aa6b53121c0e)


## Project Structure

```bash
Data_Analytics_toolkit/
├── data_analytics_toolkit.py          # Main
│
├── scripts/
│   ├── __init__.py        # (optional)
│   ├── get_data.py        # Fetch raw data (downloads, APIs, etc.)
│   ├── clean_data.py      # Clean and preprocess data
│   ├── eda_analysis.py    # Perform exploratory data analysis
│   ├── visualizations.py  # Generate charts and graphs
│
├── data/
│   └── example.csv        # Sample input dataset
│
├── requirements.txt       # Required Python packages
└── README.md              # Project overview & usage instructions

```

## 🚀 Key Features

-    📥 Data Collection: Import from CSV, etc

-    🧹 Data Cleaning: Handle missing values, duplicates, type casting, and formatting

-    📊 Exploratory Data Analysis (EDA): Summarize stats, distributions, and correlations

-   📈 Visualization Engine: Generate charts with Seaborn, Matplotlib, or Plotly

-    💾 Result Export: Save cleaned datasets, cleaning report, and EDA report.



## 📦 Installation

To run this app locally:

```bash
git clone https://github.com/DrAdrianDC/Data_Analytics_toolkit.git
cd Data_Analytics_toolkit
```

Install the required dependencies:
```bash
pip install -r requirements.txt
```

Then launch the app with:
```bash
streamlit run data_analytics_toolkit.py
```

## 💡 Use Cases

-  Quickly explore a dataset for trends and outliers
- Share EDA reports with colleagues without writing code
- Perform basic preprocessing on raw data
- Teaching/learning data science concepts interactively



