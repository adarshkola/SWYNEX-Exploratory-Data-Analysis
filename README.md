# SWYNEX-Exploratory-Data-Analysis

**Task 2 – Exploratory Data Analysis**
Internship task for SWYNEX Technologies

## What I did
I used the cleaned dataset from Task 1 (`india_aqi_cleaned.csv`) and did a basic
exploratory data analysis using Python (pandas and matplotlib).

Steps I followed:
1. Loaded the CSV file and checked the shape, columns, and missing values.
2. Found basic statistics (mean, min, max, etc.) using `describe()`.
3. Calculated the average AQI for each city.
4. Checked how many days fall in each AQI category (Good, Moderate, Severe, etc.).
5. Checked correlation of pollutants with AQI.
6. Checked for anomalies (unusually high/low AQI days) using mean ± 2×standard deviation.
7. Made 5 charts to visualize the data.
8. Wrote 6 insights based on what I found.

## How to run
```bash
pip install pandas matplotlib
python eda_simple.py
```

## Charts
- `chart1_avg_aqi_by_city.png` – Average AQI per city (bar chart)
- `chart2_aqi_category_pie.png` – AQI category distribution (pie chart)
- `chart3_pm25_vs_aqi.png` – PM2.5 vs AQI (scatter plot)
- `chart4_aqi_histogram.png` – Distribution of AQI values (histogram)
- `chart5_aqi_trend.png` – AQI trend over time (line chart)

## Insights
1. Hyderabad has the highest average AQI, meaning it has the worst air quality among the cities in this data.
2. Jaipur has the lowest average AQI, meaning it has the cleanest air among the cities in this data.
3. Most of the days fall under the "Severe" AQI category, showing that poor air quality is very common.
4. PM2.5 has the strongest correlation with AQI, meaning it is the main pollutant affecting AQI.
5. AQI values go up and down a lot over time, meaning pollution changes daily rather than staying steady.
6. No extreme anomalies were found (using mean ± 2×std), meaning even the "Severe" AQI days are part of the normal pattern in this data, not sudden one-off spikes.

## Files
- `eda_simple.py` – main Python file
- `india_aqi_cleaned.csv` – dataset used
- Chart PNG files – output charts

---
*Submitted for the SWYNEX Technologies internship program.*
