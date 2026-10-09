# Air Quality Data in India — Python Data Analysis

## Project overview
This project explores city-level air-quality observations in India using Python. It focuses on data inspection, missing values, summary statistics, AQI distributions, city comparisons, time trends, pollutant relationships, and visualizations.

**Required reference dataset:** [Air Quality Data in India — Kaggle](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)

## Files
- `README.md` — project overview and instructions.
- `air_quality_analysis.ipynb` — detailed Jupyter Notebook with analysis and plots.
- `sample_air_quality_data.csv` — expanded illustrative sample dataset for testing notebook cells.
- `output/` — folder where the notebook can save generated charts and summary tables.

## Important dataset note
The included `sample_air_quality_data.csv` is **synthetic illustrative data** created to test the notebook. It is not copied from Kaggle and must not be used to make claims about real Indian air quality.

For the actual project analysis:
1. Open the Kaggle reference link above.
2. Download and extract the dataset.
3. Place the official `city_day.csv` in the same folder as this notebook.
4. Run the notebook from top to bottom. It automatically prefers `city_day.csv` when present.

The commonly documented `city_day.csv` structure has 16 columns: `City`, `Date`, pollutant measurements, `AQI`, and `AQI_Bucket`. The exact number of rows and missing values should be checked from the downloaded file rather than assumed.

## Objectives
- Understand the dataset's size, columns, data types, and missing values.
- Inspect duplicate records and invalid date/numeric values.
- Calculate descriptive statistics for numeric fields.
- Compare average AQI across cities.
- Explore annual, monthly, and weekday patterns.
- Examine AQI category distribution.
- Explore relationships between pollutant measurements and AQI.
- Identify potential outliers for further investigation.
- Compare 2019 and 2020 only when both years exist in the data.
- Export cleaned data and summary tables for reporting.

## Technology stack
- Python 3
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn

## Setup and run
Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Start Jupyter:

```bash
jupyter notebook air_quality_analysis.ipynb
```

Run each cell in order. The notebook writes optional outputs to the `output/` folder. Create that folder if it does not exist; the notebook also creates it automatically.

## Interpretation
The notebook calculates statistics from whichever CSV it loads. Use results from the official Kaggle `city_day.csv` for your final report. Treat correlation as association, not proof of causation. Missing-value imputation and outlier handling should be explained transparently rather than silently changing the original data.

## Team
**TEAM ANSH**
- Akshaysinh Chauhan — IU2441230574
- Mevada Ansh — IU2441230560

## Data source
Rohan Rao, *Air Quality Data in India*, Kaggle: https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india
