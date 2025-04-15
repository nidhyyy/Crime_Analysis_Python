# 🔍 Crime Rate Analysis in California

This project performs an exploratory data analysis (EDA) on violent crime statistics across various cities and counties in California. Using Python and Excel, we explore, clean, and visualize data to uncover patterns and trends in criminal activity across time and geography.

##  Project Objective

The goal of this project is to gain meaningful insights from a dataset of violent crimes by:
- Cleaning and preparing the data
- Detecting and handling missing values and outliers
- Analyzing crime trends over the years
- Comparing crime rates across regions
- Identifying relationships between crime rate, population, and crime count


## 📂 Dataset Description

The dataset contains the following key attributes:
- City and County Names(county_fips,county_name)
- Report Year(report_year)
- Race/Ethnicity Data (race_eth_name,race_eth_code)
- Violent Crime Rate (per 1,000 population)
- Crime Count (Numerator)
- Population Estimate (Denominator)
- 95% Confidence Intervals (ll_95ci,u|_95ci)
- Standard Error and Relative Standard Error(se, rse)
- Region Name and Geographical Information (region_name,region_code, geo_name,geo_type_value,geotype)



##  Tools and Libraries Used

- Python 3.x
- Pandas – data manipulation and cleaning
- NumPy – numerical calculations
- Matplotlib & Seaborn– data visualization
- Jupyter Notebook– interactive code execution and exploration

---

## Key Features & Analysis Steps

-  **Data Cleaning**: Handled missing values, dropped duplicates, and corrected data types.
- **Outlier Detection**: Used IQR (Interquartile Range) method to detect and remove outliers.
-  **Trends Over Time**: Visualized crime patterns year-wise using line plots.
-  **Crime Type Analysis**: Aggregated total crime counts by category.
-  **Population vs Crime**: Explored the relationship between population and crime count/rate.
-  **Rate vs Count**: Investigated how crime count affects the crime rate using scatter plots and regression.

---

## 📷 Sample Visualizations

- Bar chart of total crimes by type
- Line chart showing yearly crime trends
- Scatter plot for crime rate vs count
- Boxplots before outlier removal


