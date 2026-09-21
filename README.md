# SWYNEX-Exploratory-Data-Analysis

Exploratory Data Analysis project completed as part of my Data Analyst Internship at SWYNEX Technologies.

# Task 2 – Exploratory Data Analysis

## Project Overview

This project was completed as part of my Data Analyst Internship at SWYNEX Technologies. The objective of this task was to perform Exploratory Data Analysis (EDA) on the cleaned Air Quality Index (AQI) dataset from Task 1.

The analysis was performed to understand the dataset, identify patterns and trends, examine relationships between pollutants and AQI, and generate useful insights using Python.

## Dataset

The dataset used for this task is the cleaned India AQI dataset prepared during Task 1.

The cleaned dataset contains:

- **100 rows**
- **10 columns**
- Air quality information from different cities in India
- Pollutant measurements
- AQI values
- AQI categories

The main columns include:

- City
- Date
- PM2.5
- PM10
- NO2
- SO2
- CO
- O3
- AQI
- AQI_Bucket

## Tools Used

- Python
- Pandas
- Matplotlib
- VS Code

## Files

```text
SWYNEX-Exploratory-Data-Analysis
│
├── india_aqi_cleaned.csv
├── chart1_avg_aqi_by_city.png
├── chart2_aqi_category_pie.png
├── chart3_pm25_vs_aqi.png
├── chart4_aqi_histogram.png
├── chart5_aqi_trend.png
├── exploratory_data_analysis.py
└── README.md
Exploratory Data Analysis Steps
1. Load the Dataset

Loaded the cleaned AQI dataset using Pandas.

2. Check Dataset Information

Checked:

Number of rows and columns
Column names
Missing values
Duplicate records
Data types
3. Calculate Basic Statistics

Calculated basic statistical measures such as:

Count
Mean
Standard deviation
Minimum
Maximum
Quartiles

using the describe() function.

4. Average AQI by City

Calculated the average AQI for each city to compare AQI levels across different cities.

5. AQI Category Distribution

Analyzed the number of records in each AQI category using AQI_Bucket.

6. Correlation Analysis

Calculated the correlation between AQI and the different pollutant columns to understand the relationships between air pollutants and AQI.

7. Anomaly Check

Performed a simple anomaly check using the mean and standard deviation.

The normal AQI range was calculated using:

Mean ± 2 × Standard Deviation

AQI values outside this range were checked as potential anomalies.

Visualizations
1. Average AQI by City

A bar chart was created to compare the average AQI across different cities.

2. AQI Category Distribution

A pie chart was created to show the distribution of AQI categories.

3. PM2.5 vs AQI

A scatter plot was created to examine the relationship between PM2.5 and AQI.

4. AQI Distribution

A histogram was created to understand the distribution of AQI values.

5. AQI Trend Over Time

A line chart was created to observe how AQI values changed over time.

Key Insights

Based on the analysis:

Hyderabad has the highest average AQI in this dataset, with an average AQI of approximately 375.33.
Jaipur has the lowest average AQI in this dataset, with an average AQI of approximately 206.44.
The Severe AQI category contains the highest number of records, with 45 out of 100 records.
PM2.5 has the strongest positive correlation with AQI among the pollutant columns in this dataset.
The correlation between PM2.5 and AQI is approximately 0.89, showing a strong positive relationship in this dataset.
AQI values vary across different cities and dates, showing changes in air quality over time.
No AQI values were identified as anomalies using the mean ± 2 standard deviations method.
Final Results

The EDA produced:

City-wise average AQI analysis
AQI category distribution
Pollutant correlation analysis
AQI anomaly check
AQI distribution analysis
AQI trend over time
5 data visualizations
Conclusion

The Exploratory Data Analysis helped in understanding the structure and characteristics of the cleaned AQI dataset.

The analysis identified differences in AQI across cities, the distribution of AQI categories, relationships between pollutants and AQI, and changes in AQI over time.

Learning Outcome

Through this task, I practiced Exploratory Data Analysis using Python, Pandas and Matplotlib.

I learned how to calculate basic statistics, analyze categorical data, calculate correlations, identify potential anomalies, and create visualizations to understand patterns and trends in a dataset.
