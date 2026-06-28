# Healthcare No-Show Analytics

An analytics project for exploring healthcare appointment no-shows through SQL analysis, Python notebooks, parquet exports, QA summaries, and Tableau visualizations.

## Project Contents

```text
Task 1/   Initial Python and SQL exploration
Task 2/   SQL queries and exported result charts
Task 3/   No-show and appointment visualizations
Task 4/   Star schema design
Task 6/   Parquet export, QA files, and processing notebook
Task 7/   Tableau workbook and dashboard screenshots
```

## Main Artifacts

- `Task 1/Python/Task 1.ipynb` - Python-based exploratory analysis.
- `Task 1/SQL/HealthCareBD.sql` - database setup script.
- `Task 2/SQLQuery1.sql` - SQL analysis query.
- `Task 4/Star Schema.png` - dimensional model diagram.
- `Task 6/Scripts/Task 6.ipynb` - parquet processing and QA workflow.
- `Task 6/QA/*.csv` - data quality outputs.
- `Task 7/HealthCareAnalysis.twb` - Tableau workbook.
- `Task 7/*.png` - Tableau dashboard exports.

## Suggested Workflow

1. Review the SQL setup scripts in `Task 1/SQL` and `Task 2`.
2. Open the notebooks in Jupyter to inspect the data preparation and analysis steps.
3. Review the generated QA CSVs in `Task 6/QA`.
4. Open `Task 7/HealthCareAnalysis.twb` in Tableau Desktop to explore the dashboard.

## Requirements

The repository is artifact-focused and does not currently include a pinned Python environment. A typical analysis environment should include:

- Python 3.10+
- Jupyter
- pandas
- pyarrow
- matplotlib or seaborn
- a SQL database compatible with the included scripts
- Tableau Desktop or Tableau Public for the `.twb` workbook

## Notes

The parquet files and dashboard images are included as analysis artifacts so the project can be reviewed without rerunning every transformation step.
