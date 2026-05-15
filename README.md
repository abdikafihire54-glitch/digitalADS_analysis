[README.md](https://github.com/user-attachments/files/27786370/README.md)
# ADS Performance Dashboard

This project analyzes advertising performance data from `global_ads_performance_dataset.csv` using Python.

## What it does
- loads the ads performance dataset
- cleans the data by trimming text, parsing dates, converting numeric columns, and removing duplicates
- computes standard campaign metrics like CTR, CPA, and ROAS
- displays chart-only visualizations using `matplotlib`

## Files
- `digital.ipynb` - Jupyter notebook for data cleaning and charts
- `global_ads_performance_dataset.csv` - source dataset
- `Ads.py` - placeholder file

## Run the notebook
1. Open `digital.ipynb` in Jupyter or VS Code Notebook
2. Run the cells sequentially
3. Ensure `matplotlib` is installed: `pip install matplotlib`

## Notes
- The notebook now uses `matplotlib` for plotting to avoid Plotly dependency issues.
- The visualizations include daily spend vs revenue, CTR by platform, conversions by country, industry ROAS vs CPC, and spend by campaign type.
