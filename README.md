# Modified-Z-Score
**Overview**
This project involves the analysis and statistical processing of movie revenue data from the Movies_revenue.xlsx dataset. The main tasks include calculating new revenue metrics, identifying outliers using Z-scores and modified Z-scores, and handling these outliers for a refined analysis.

**Datasets**
Movies_revenue.xlsx: This dataset contains revenue information for various movies.

**Steps**
**Data Loading and Initial Analysis:**
Load the dataset and display the initial rows.
Generate descriptive statistics for the revenue column.

**Revenue Transformation:**
Convert revenue values to millions for easier interpretation.
Generate descriptive statistics for the transformed revenue data.

**Outlier Detection:**

**Z-Score Method:**
Calculate the mean and standard deviation of the transformed revenue.
Compute Z-scores to identify potential outliers.
Filter movies with Z-scores greater than 3 to highlight significant outliers.

**Modified Z-Score Method:**
Calculate the Median Absolute Deviation (MAD) of the transformed revenue.
Compute modified Z-scores to identify outliers more robustly.
Filter movies with modified Z-scores greater than 3.5 to identify outliers.

**Requirements**
Python 3.x
pandas
numpy

**Usage**
Data Analysis: The provided code snippets load and analyze the revenue data, converting values to millions and calculating necessary statistical metrics.
Outlier Detection: The code uses both traditional Z-scores and modified Z-scores to identify and filter out outliers, providing a robust method for outlier detection.
