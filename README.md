# Google Play Store Analysis

An exploratory data analysis and regression project on Google Play Store app data, with an accompanying Power BI dashboard.

## What it does

- Cleans and explores the Play Store dataset (ratings, installs, categories, pricing, etc.)
- Handles missing values using `KNNImputer`
- Analyzes relationships between app attributes and outcomes using `statsmodels` and correlation analysis
- Trains a Linear Regression model to study/predict app performance metrics
- Visualizes trends and distributions with `seaborn`/`matplotlib`
- Includes a Power BI dashboard (`Play Store Analysis.pbix`) for interactive exploration of the same data

## Contents

- `Google_Play_Store.ipynb` — data cleaning, analysis, and modeling
- `Play Store Analysis.pbix` — Power BI dashboard

## Running it

Open `Google_Play_Store.ipynb` in Jupyter. Requires `pandas`, `numpy`, `seaborn`, `matplotlib`, `statsmodels`, and `scikit-learn`. Open the `.pbix` file in Power BI Desktop to view the dashboard.

## Tech

Python, pandas, scikit-learn, statsmodels, Power BI
