# California Housing - EDA & Data Preprocessing

Exploratory data analysis and preprocessing on the California Housing dataset.

## Dataset
Source: Kaggle (California Housing Prices). Included as `housing.csv`.

## Preview
![Feature-to-Feature Correlation](Screenshot%202026-10-05%20175226.png)

## What I did
- Data understanding: head, tail, info, describe, dtypes, duplicates
- Missing values: filled `total_bedrooms` with median
- Outliers: IQR-based detection, boxplots, Yeo-Johnson power transformation
- Feature engineering: rooms_per_household, bedrooms_per_room, population_per_household
- Feature selection: variance, correlation with target, scatter plots, correlation heatmap

## Tech
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## How to run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook EDA.ipynb
```
