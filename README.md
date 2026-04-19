# Exploratory Data Analysis (EDA) on Road Accident Dataset

This repository contains a comprehensive Exploratory Data Analysis (EDA) project performed on an Indian road accident dataset. The objective of this project is to understand patterns, analyze trends, and extract meaningful insights using Python-based data analysis techniques.

---

## Project Overview

This project focuses on analyzing a dataset containing 3000 records and 22 features related to road accidents across different states in India. The analysis includes data cleaning, preprocessing, visualization, and statistical exploration.

According to the dataset, attributes include state, city, accident severity, vehicle type, weather conditions, driver details, and more .

---

## What is Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) is the process of:

* Understanding the dataset structure
* Cleaning and preprocessing data
* Identifying patterns and relationships
* Detecting missing values and anomalies
* Preparing data for machine learning models

EDA is a critical first step in any data science workflow.

---

## Dataset Information

* Total Records: 3000
* Total Features: 22
* Data Types:

  * Numerical: 6 columns
  * Categorical: 16 columns

Key columns include:

* State Name
* City Name
* Year, Month, Day
* Accident Severity
* Number of Vehicles Involved
* Weather Conditions
* Road Type and Condition
* Driver Age and Gender
* Alcohol Involvement

From the dataset summary:

* Average driver age: 44 years
* Average speed limit: ~75 km/h
* Average casualties: ~5 per accident 

---

## Data Preprocessing

The following preprocessing steps were applied:

* Removed duplicate records
* Handled missing values:

  * Categorical columns filled with mode
  * Numerical columns filled with median
* Standardized column names
* Converted date-related columns if present

Missing values identified:

* Traffic Control Presence: 716 missing
* Driver License Status: 975 missing 

---

## Exploratory Analysis

### 1. Top Accident-Prone States

A pie chart was created to identify the top 5 states with the highest number of accidents.

Top states include:

* Goa
* Sikkim
* Delhi
* Uttarakhand
* Jammu and Kashmir 

---

### 2. Categorical Data Analysis

Bar plots were generated for categorical variables such as:

* State Name
* City Name
* Month
* Day of Week
* Vehicle Type
* Weather Conditions

The charts on pages 5–11 show the frequency distribution of these variables .

---

### 3. Numerical Data Analysis

Histograms were used to analyze distributions of:

* Year
* Number of Vehicles Involved
* Number of Casualties
* Number of Fatalities
* Speed Limit
* Driver Age

These visualizations help understand data spread and central tendencies (page 13–14) .

---

### 4. Outlier Detection

Box plots were used to detect outliers in numerical features such as:

* Speed Limit
* Driver Age
* Casualties
* Fatalities

Outlier analysis is shown on pages 15–17 .

---

### 5. Monthly Accident Trends

A bar graph was used to analyze accident frequency across months, showing seasonal patterns in accident occurrence (page 18) .

---

### 6. Weather Condition Analysis

Count plots and bar charts were used to analyze accidents based on weather conditions.

Top contributing weather conditions:

* Rainy
* Stormy
* Foggy
* Clear
* Windy 

---

### 7. Correlation Analysis

A heatmap was used to visualize relationships between numerical features such as:

* Number of vehicles
* Casualties
* Fatalities
* Speed limit
* Driver age

The heatmap (page 20) shows weak to moderate correlations between variables .

---

### 8. Advanced Visualizations

The project also includes:

* Scatter plot: Driver Age vs Speed Limit vs Severity
* Interactive bar charts using Plotly
* Geographic visualization of accidents across India
* Year-wise accident trend line chart

These are shown in pages 22–27 .

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

---

## Repository Structure

EDA-/
│── datasets/          # Dataset files
│── notebooks/         # Jupyter notebooks
│── outputs/           # Visualizations and charts
│── README.md          # Documentation

---

## Key Insights

* Certain states consistently show higher accident rates
* Weather conditions significantly impact accident occurrence
* Speed limit and driver age show some correlation with accident severity
* Accidents are fairly distributed across months with slight variations

---

## Future Improvements

* Apply machine learning models for accident prediction
* Perform feature engineering for better insights
* Integrate real-time data sources
* Build dashboards using Power BI or Tableau

---

## How to Run the Project

1. Clone the repository
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn plotly
3. Open Jupyter Notebook
4. Run the analysis notebook

---

## License

This project is open-source and available under the MIT License.

---

## Author

GitHub: (https://github.com/pandreabhishek216)

