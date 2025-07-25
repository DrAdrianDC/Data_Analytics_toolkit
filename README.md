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

📥 **Data Collection**  
Import datasets from CSV, Excel, JSON formats via an intuitive drag-and-drop interface.

🧹 **Data Cleaning**  
Handle missing values, drop duplicates, convert data types, and reformat columns — all without code.

📊 **Exploratory Data Analysis (EDA)**  
Choose between:
- **Basic EDA**: Summary statistics, data types, null value counts
- **Full EDA Report**: Auto-generated report using `pandas_profiling` / `ydata_profiling`

📈 **Visualization Engine**  
Generate charts using Seaborn, Matplotlib, and Plotly, including:
- Histograms
- Boxplots
- Pie charts
- Correlation heatmaps

💾 **Result Export**  
Download the cleaned dataset, cleaning report and EDA report files. 


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



