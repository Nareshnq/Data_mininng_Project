# Data Mining Project — Washington House Price Prediction

A data mining project that explores Washington house price data and builds a price prediction model, comparing predicted prices against actual sale prices.

## What this project covers

- **Exploratory analysis** of the Washington housing dataset, including feature relationships such as living area, above-ground area, and bathroom counts.
- **Correlation and multicollinearity checks** — for example, `sqft_living` and `sqft_above` are highly correlated, which matters when selecting features for the model.
- **Price prediction** — the trained model's predictions are saved alongside actual prices for comparison.

## Files in this repo

- `Datamining_Project2.ipynb` — Main project notebook: analysis and price prediction workflow.
- `kaggle.ipynb` — Supporting notebook with correlation and multicollinearity exploration.
- `naresh.projectdm-Copy2.ipynb` — Additional project notebook.
- `experiment_project .ipynb` — Experiment notebook.
- `Untitled.ipynb` — Scratch notebook.
- `Washington_price_dataset.csv` — Washington house price dataset used for training and evaluation.
- `actual_vs_predicted_prices.csv` — Model output: actual prices next to predicted prices, for checking prediction accuracy.

## How to run

1. Open `Datamining_Project2.ipynb` in Jupyter Notebook or JupyterLab.
2. Make sure the CSV files in this repo are in the same working directory.
3. Run the cells top to bottom — the analysis runs first, followed by model training and the actual-vs-predicted comparison.
