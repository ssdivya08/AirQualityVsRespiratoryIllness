# Air Quality vs Respiratory Illness Trend Comparison

## Project Overview

The **Air Quality vs Respiratory Illness Trend Comparison** project analyzes air-quality conditions and respiratory-health indicators to identify useful patterns and trends in the available data.

The project combines two related datasets using `location_id`. The first dataset contains air-quality and respiratory-health information, while the second dataset contains location details such as city, state, region, population and population density.

The analysis is performed using Python and Jupyter Notebook, with results presented through tables, charts and stakeholder-oriented insights.

---

## Objectives

The main objectives of this project are:

- Analyze average AQI across different cities.
- Compare AQI across different regions.
- Identify cities with the highest and lowest AQI.
- Analyze monthly changes in AQI.
- Identify the most common AQI category.
- Analyze respiratory ED visits, hospital admissions and outpatient visits.
- Study the relationship between AQI and respiratory-health indicators.
- Analyze PM2.5 and PM10 levels.
- Compare AQI exceedance and non-exceedance observations.
- Study population density and AQI.
- Analyze AQI and respiratory ED visits over time.
- Present the results using suitable visualizations.
- Generate useful insights from the analysis.

---

## Datasets

The project uses two datasets.

### 1. Air Quality and Respiratory Health Dataset

This dataset contains information such as:

- Date
- Location ID
- AQI value
- AQI category
- PM2.5
- PM10
- NO2
- SO2
- CO
- O3
- Temperature
- Humidity
- Wind speed
- Respiratory ED visits
- Hospital admissions
- Outpatient visits
- Respiratory mortality count
- Prescriptions issued
- AQI exceedance flag

### 2. Location Dataset

This dataset contains:

- Location ID
- City
- State
- Region
- Population
- Population density
- Baseline AQI

The two datasets are connected using the common **`location_id`** column.

---

## Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **Matplotlib**
- **CSV**

### Python Libraries

```python
import pandas as pd
import matplotlib.pyplot as plt
```

---

## Data Processing

The project follows these main steps:

1. Load the datasets.
2. Inspect the data.
3. Check missing values.
4. Check duplicate records.
5. Check data types.
6. Convert the date column into the required format.
7. Merge the two datasets using `location_id`.
8. Extract month information for monthly analysis.
9. Perform the required calculations.
10. Create visualizations.
11. Interpret the results.
12. Prepare stakeholder insights.

---

## Analysis Performed

The project contains 25 analytical questions covering the following areas:

### Air Quality Analysis
- Average AQI by city
- Average AQI by region
- Highest AQI city
- Lowest AQI city
- Monthly AQI
- Most common AQI category
- Average AQI by AQI category

### Respiratory Health Analysis
- Respiratory ED visits by city
- Hospital admissions by city
- Outpatient visits by city
- Monthly respiratory ED visits
- Monthly hospital admissions
- City with the highest average respiratory ED visits

### AQI and Respiratory Health
- AQI vs respiratory ED visits
- AQI vs hospital admissions
- AQI vs outpatient visits
- AQI category vs respiratory ED visits
- AQI category vs hospital admissions

### Pollutant Analysis
- PM2.5 by city
- PM10 by city
- PM2.5 vs respiratory ED visits
- PM10 vs respiratory hospital admissions

### Additional Analysis
- AQI exceedance vs respiratory ED visits
- Population density vs AQI
- AQI and respiratory ED visits over time

---

## Visualizations

The project uses different graphs according to the type of analysis.

### Bar Charts
Used for comparing:
- Cities
- Regions
- AQI categories
- Respiratory-health indicators
- PM2.5 and PM10
- AQI exceedance groups

### Line Charts
Used for analyzing:
- Monthly AQI
- Monthly respiratory ED visits
- Monthly hospital admissions
- AQI and respiratory ED visits over time

### Scatter Plots
Used for analyzing relationships between:
- AQI and respiratory ED visits
- AQI and hospital admissions
- AQI and outpatient visits
- PM2.5 and respiratory ED visits
- PM10 and hospital admissions
- Population density and AQI

---

## Key Insights

The analysis helps identify:

- Differences in AQI between cities and regions.
- Changes in AQI across different months.
- Differences in respiratory-health activity between cities.
- Relationships between AQI and respiratory-health indicators.
- Differences in respiratory ED visits during AQI exceedance and non-exceedance observations.
- Relationships between particulate pollutants and respiratory-health indicators.
- Patterns between population density and AQI.

These findings represent patterns in the available dataset and should not be treated as direct medical conclusions.

---

## Project Structure

```
Air-Quality-Respiratory-Illness-Analysis/
│
├── README.md
│
├── Air_Quality_Respiratory_Analysis.ipynb
│
├── air_quality_respiratory.csv
│
├── location.csv
│
├── Project_Report.docx
│
└── requirements.txt
```

---

## How to Run the Project

### Step 1: Install Python

Install Python on your system.

### Step 2: Install Required Libraries

Run:

```bash
pip install pandas matplotlib jupyter
```

### Step 3: Open Jupyter Notebook

Run:

```bash
jupyter notebook
```

### Step 4: Open the Notebook

Open:

```
Air_Quality_Respiratory_Analysis.ipynb
```

### Step 5: Run the Cells

Run the notebook cells from top to bottom to perform data loading, cleaning, analysis and visualization.

---

## Project Limitations

The analysis depends on the available datasets, locations and time period.

The project mainly uses descriptive analysis, comparisons, correlation and visualization. Therefore, the results show patterns in the available data but do not prove that air pollution directly causes respiratory illness.

Additional data covering more locations, longer time periods and other factors could provide a broader analysis.

---

## Conclusion

The Air Quality vs Respiratory Illness Trend Comparison project provides a structured analysis of air-quality and respiratory-health data.

By combining the two datasets, performing data cleaning and analysis, and presenting the results through visualizations, the project makes it easier to identify important patterns related to AQI, pollutants and respiratory-health indicators.

The analysis can be useful for understanding the available data and supporting further investigation into air-quality and respiratory-health trends.
