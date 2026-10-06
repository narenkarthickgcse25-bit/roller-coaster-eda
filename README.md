# Roller Coaster EDA

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a roller coaster dataset using Python.

The analysis focuses on understanding roller coaster characteristics such as speed, height, inversions, G-force, opening year, manufacturer, location, and operating status.

## Dataset

* Total records: 1,087
* Cleaned features: 15
* Dataset file: `coaster_db.csv`

## Data Cleaning

The project includes:

* Handling missing values
* Checking and removing exact duplicate rows
* Converting columns to appropriate data types
* Cleaning numerical features
* Converting opening dates
* Creating `Opening_Year`
* Creating `Coaster_Age`

## Exploratory Data Analysis

The following analyses were performed:

* Descriptive statistics
* Categorical data analysis
* Coaster type distribution
* Status distribution
* Top manufacturers
* Location analysis
* Speed distribution
* Height distribution
* Inversion distribution
* G-force distribution
* Opening year trends
* Correlation analysis
* Outlier analysis
* Speed vs height analysis
* Coaster age analysis
* Manufacturer-wise analysis
* Location-wise analysis

## Key Findings

* Steel roller coasters are the most common coaster type.
* Operating roller coasters form the largest group by status.
* Roller coaster speed and height show a weak positive relationship.
* The dataset contains coasters with very high speeds, heights, inversions, and G-forces.
* Opening year and coaster introduction year show a strong positive relationship.
* Coaster age has a perfect negative relationship with opening year because age was calculated from opening year.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Files

| File                                            | Description            |
| ----------------------------------------------- | ---------------------- |
| `Exploratory Data Analysis (EDA) Project.ipynb` | Complete EDA notebook  |
| `coaster_db.csv`                                | Roller coaster dataset |

## Conclusion

This project demonstrates how Python can be used to clean, analyze, visualize, and extract meaningful insights from a real-world roller coaster dataset.
