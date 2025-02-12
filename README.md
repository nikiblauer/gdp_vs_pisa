# Exploratory Data Analysis

![header](header.png)

## Overview
This project performs an exploratory data analysis (EDA) on a dataset related to GDP and PISA scores. It includes data cleaning, visualization, and modeling using regression and clustering techniques.

## Features
- **Data Preprocessing:** Cleaning and merging datasets.
- **Insights Extraction:** Analysis on GDP, PISA scores, and their relationships.
- **Visualization:** Matplotlib, Seaborn plots.
- **Machine Learning:** Regression and clustering models.

## Installation
### Using Conda (Recommended)
Ensure you have Conda installed, then run:
```bash
conda env create -f environment.yml
conda activate vds
```

### Using pip (Alternative)
If you prefer `pip`, install dependencies manually:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn matplotlib-venn
```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook exploratory_data_analysis.ipynb
   ```
2. Run each cell sequentially to perform data analysis.

## Dependencies
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Matplotlib-venn (for visualization)

## Results
This analysis provides:
- **Insights into GDP and educational performance:** Examining how GDP levels correlate with PISA scores and identifying patterns across different countries.
- **Regression models for trend analysis:** Implementing linear regression to study the relationship between GDP and educational performance over time.
- **Clustering models for pattern identification:** Using KMeans and DBSCAN clustering to identify groups of countries with similar educational and economic characteristics.
- **Comparative analysis:** Finding the top and bottom-performing countries in terms of PISA scores and their corresponding GDP rankings.
- **Time-series analysis:** Observing trends in GDP and education over the years to predict future performance and economic growth potential.
- **Visualizations:** The generated plots and figures are saved in the `vis/` folder for further reference and analysis.

