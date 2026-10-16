# India Agriculture & Monsoon Intelligence

## 1. Project Overview

This project explores historical rainfall patterns across Indian meteorological subdivisions and examines selected-season production trends for Rice and Wheat.

The objective is to practice data cleaning, exploratory data analysis, visualization, and evidence-based interpretation using Python, Pandas, NumPy, and Matplotlib.

## 2. Rainfall Analysis

- The rainfall dataset covers 1901–2017 and contains 36 meteorological subdivisions.
- The analysis examines monthly rainfall, monsoon rainfall, annual variability, and wettest and driest monsoon years.
- Subdivision averages are unweighted averages of available subdivision observations. They should not be interpreted as official area-weighted all-India rainfall totals.
- Historical meteorological subdivisions do not necessarily match modern state or district boundaries.

## 3. Rice and Wheat Analysis

- The crop dataset contains State, District, Crop, Year, Season, Area, Production, and Yield fields.
- Rice and Wheat records both report production in tonnes in the selected dataset.
- Rice–Kharif and Wheat–Rabi are used as the primary season-specific comparisons.
- Calculated yield is total recorded production divided by total recorded area for each crop-year group.
- The 2020–21 records are excluded from trend charts because the dataset contains only 13 records for each selected crop-season combination in that year.

## 4. Interpretation and Limitations

- Selected-season summaries are not automatically complete national production estimates.
- Summing across all seasons can be misleading if seasonal records overlap with Whole Year records.
- Rainfall observations are at meteorological-subdivision level, while crop observations are at district level. Direct merging without a defensible geographic mapping is inappropriate.
- Visual similarity between rainfall and crop trends does not establish causation.
- Missing production values are not treated as zero.

## 5. Next Steps

- Validate geographic and temporal coverage.
- Investigate extreme rainfall years and crop trends.
- Explore district-level crop data with an appropriate geographic mapping if one becomes available.
- Add reproducible charts, data-source citations, and project setup instructions to the README.

## 6. Preliminary Crop Trend Results

Comparing the first and last available selected-season observations from 1997–98 to 2019–20:

- **Rice (Kharif):** Recorded production increased by 127.89%, recorded area increased by 86.03%, and calculated yield increased by 22.50%.
- **Wheat (Rabi):** Recorded production increased by 104.65%, recorded area increased by 36.75%, and calculated yield increased by 49.65%.

These percentages compare two endpoints; they are not annual growth rates. They describe the selected-season dataset and should not be interpreted as verified national totals until geographic coverage and aggregation are validated.

The rainfall and crop datasets use different time formats. Their year alignment must be verified before calculating correlations or drawing conclusions about rainfall and agricultural production.
