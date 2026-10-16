# India Agriculture & Monsoon Intelligence 🌧️🌾

A Python-based exploratory data analysis project studying historical Indian monsoon rainfall patterns and selected-season Rice and Wheat production trends.

## Overview

This project uses historical rainfall and crop-production datasets to explore:

- Monthly and seasonal rainfall patterns across Indian meteorological subdivisions.
- Year-to-year monsoon rainfall variability.
- Selected-season Rice and Wheat production, cultivated area, and calculated yield.
- How historical climate and agricultural datasets can be analyzed responsibly.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
india-agriculture-monsoon-intelligence/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_rainfall_analysis.ipynb
│   ├── 02_crop_production_analysis.ipynb
│   └── 03_combined_findings.ipynb
├── reports/
│   └── findings.md
├── images/
├── README.md
├── requirements.txt
└── .gitignore
```

## Data Sources

- Dataset01: India rainfall data: https://data.gov.in/catalog/rainfall-india
- Dataset02: District-wise, season-wise crop production statistics: https://www.data.gov.in/catalog/district-wise-season-wise-crop-production-statistics-0
- Alternative agriculture data portal: https://data.desagri.gov.in/website/crops-apy-report-web
- Or use Kaggle data: https://www.kaggle.com/datasets/pyatakov/india-agriculture-crop-production?resource=download&select=India+Agriculture+Crop+Production.csv

Check the original dataset documentation for coverage, units, definitions, and reuse conditions.

## Analysis

### Rainfall

The rainfall analysis explores monthly and seasonal rainfall, historical monsoon variability, and high- and low-rainfall years across meteorological subdivisions.

### Crop Production

The crop analysis focuses on Rice–Kharif and Wheat–Rabi records. It examines recorded area, production, and calculated yield over time.

The 2020–21 observations are excluded from the main trend plots because the available records for that year are substantially fewer than in preceding years.

## Preliminary Findings

For the selected-season dataset, comparing 1997–98 with 2019–20:

- Rice–Kharif recorded production increased by 127.89%.
- Wheat–Rabi recorded production increased by 104.65%.
- Calculated yield increased by 22.50% for Rice and 49.65% for Wheat.

These are endpoint comparisons, not annual growth rates. They should not be interpreted as verified national totals until geographic coverage and aggregation have been validated.

## Important Limitations

- Rainfall data uses meteorological subdivisions, while crop data uses districts.
- Agricultural years and calendar years must be aligned carefully before combined statistical analysis.
- Seasonal records may not represent complete annual crop production.
- Visual trends and correlations alone do not establish causation.
- Missing production values are not assumed to mean zero production.

## Run the Project

1. Clone or download this repository.
2. Install the dependencies listed in `requirements.txt`.
3. Open the notebooks folder in Jupyter.
4. Run the notebooks in order, starting with rainfall analysis.

## Future Improvements

- Validate geographic coverage and crop aggregation.
- Compare rainfall and agricultural outcomes over correctly aligned periods.
- Add robust statistical analysis and uncertainty checks.
- Build an interactive dashboard for exploring rainfall and crop trends.

## Author

Created as a learning project in Python, data analysis, and Indian agriculture.
