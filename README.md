# TMDB Movie Data Analysis with Spark and PySpark

Pipeline that fetches movie data from the TMDB API, cleans it with PySpark,
computes KPIs, visualises the results with Matplotlib and generates a final report.

## Setup
1. Install Java 17 and Python 3.10+.
2. `pip install -r requirements.txt`
3. Copy `.env.example` to `.env` and set `TMDB_API_KEY=your_key`.
4. Open `tmdb_analysis.ipynb` and run all cells.

## Outputs
- `reports/final_report.md`: key insights, methodology, KPI tables and conclusions
- `reports/figures/`: the five charts
- `data/`: raw API cache and clean dataset (not committed)
