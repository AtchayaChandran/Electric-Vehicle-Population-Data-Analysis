# 🚗 Electric Vehicle Population Data Analysis Using Python

## 📌 Project Overview

This project analyzes Electric Vehicle (EV) population data using Python to understand EV adoption patterns, electric range, vehicle types, manufacturers, model years, CAFV eligibility, and geographic distribution.

The project follows a complete data analytics workflow, starting from data cleaning and preprocessing to Exploratory Data Analysis (EDA), statistical analysis, and data visualization.

The main objective is to transform raw Electric Vehicle data into meaningful insights by identifying key patterns, trends, distributions, and relationships within the dataset.

## 🎯 Business Problem

Electric Vehicle population data contains valuable information about vehicle characteristics and EV adoption. However, raw data alone does not clearly provide insights into:

- Which type of Electric Vehicles are most common?
- How is Electric Range distributed across vehicles?
- Which manufacturers have the highest number of registered EVs?
- How does Electric Range vary across different Model Years?
- How are vehicles distributed across CAFV eligibility categories?
- Which counties have higher EV adoption?
- What relationships exist between EV Type, Electric Range, Model Year, and Manufacturers?

This project addresses these questions using Python-based data analysis, statistical methods, and data visualization techniques to identify meaningful patterns and insights from the dataset.

## 🚀 Project Objectives

- Analyze the distribution of Electric Vehicles in the dataset.
- Understand the distribution and characteristics of Electric Range.
- Compare Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).
- Identify the top Electric Vehicle manufacturers based on vehicle count.
- Analyze the distribution of Electric Vehicles across different Model Years.
- Analyze the distribution of vehicles based on CAFV Eligibility.
- Identify counties with higher Electric Vehicle population.
- Perform statistical analysis using Mean, Median, Mode, Variance, Standard Deviation, Skewness, and Kurtosis.
- Perform Univariate, Bivariate, and Multivariate Analysis using appropriate visualizations.
- Derive meaningful insights and identify important patterns and relationships from the analysis.

## 📂 Dataset Information

The dataset used in this project contains information about registered Electric Vehicles and their characteristics.

### Dataset Details

| Feature | Details |
|---|---|
| Dataset | Electric Vehicle Population Data |
| File Type | Excel |
| Data Type | Vehicle Registration Data |
| Analysis Focus | Electric Vehicle Population and Characteristics |

### Key Features

| Feature | Description |
|---|---|
| Electric Vehicle Type | Type of Electric Vehicle such as BEV and PHEV |
| Electric Range | Electric driving range of the vehicle in miles |
| Model Year | Model year of the vehicle |
| Make | Manufacturer of the vehicle |
| County | County where the vehicle is registered |
| CAFV Eligibility | Clean Alternative Fuel Vehicle eligibility category |

The dataset was used to perform data cleaning, exploratory analysis, statistical analysis, and visualization to identify meaningful patterns in Electric Vehicle adoption.

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub
- Markdown

## 🔄 Project Workflow

```text
Data Collection
      ↓
Data Understanding
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis (EDA)
      ↓
Statistical Analysis
      ↓
Univariate Analysis
      ↓
Bivariate Analysis
      ↓
Multivariate Analysis
      ↓
Insights & Interpretation
      ↓
Conclusion

## 🧹 Data Cleaning & Preprocessing

Data cleaning and preprocessing were performed to improve data quality and prepare the dataset for further analysis.

The following steps were performed:

- Inspected the dataset structure and dimensions.
- Checked column names and data types.
- Identified missing values across the dataset.
- Checked for duplicate records.
- Handled missing values in categorical columns using appropriate imputation techniques.
- Verified numerical and categorical variables before analysis.
- Prepared the cleaned dataset for Exploratory Data Analysis and visualization.

These preprocessing steps helped ensure that the dataset was suitable for statistical analysis and data visualization.

## 📊 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the structure, distribution, and key characteristics of the Electric Vehicle dataset.

The analysis focused on the following areas:

- Dataset structure and dimensions
- Data types and variable identification
- Missing value analysis
- Duplicate record analysis
- Descriptive statistics
- Electric Vehicle Type distribution
- Electric Range distribution
- Top EV manufacturers
- Model Year distribution
- CAFV Eligibility distribution
- County-level EV population

EDA helped identify important patterns and characteristics in the dataset and provided a foundation for further statistical analysis and visualization.

## 📈 Statistical Analysis Metrics

Statistical analysis was performed on the Electric Range variable to understand its central tendency, variability, and distribution shape.

The following statistical measures were calculated:

| Metric | Value | Interpretation |
|---|---:|---|
| Mean | 37.40 miles | Represents the average Electric Range of the vehicles. |
| Median | 0 miles | Represents the middle value of the Electric Range data. |
| Mode | 0 miles | Represents the most frequently occurring Electric Range value. |
| Variance | 5889.14 | Measures the overall variability of Electric Range values. |
| Standard Deviation | 76.74 miles | Indicates the typical spread of Electric Range around the mean. |
| Skewness | 2.23 | Indicates a positively skewed Electric Range distribution. |
| Kurtosis | 3.67 | Indicates relatively heavier tails and the presence of extreme observations. |

### 📌 Key Statistical Insights

- The **Mean (37.40 miles) is higher than the Median (0 miles)**, indicating that the Electric Range distribution is strongly influenced by higher-range observations.
- The **Mode of 0 miles** shows that zero is the most frequently occurring Electric Range value.
- The **Standard Deviation of 76.74 miles** indicates considerable variation in Electric Range across vehicles.
- The **positive Skewness value of 2.23** indicates that the distribution has a longer tail towards higher Electric Range values.
- The **Kurtosis value of 3.67** indicates the presence of relatively heavy tails and extreme observations.
- Overall, the statistical measures indicate considerable variability and a positively skewed Electric Range distribution.

## 📌 Mean Electric Range

The mean represents the average Electric Range of the vehicles in the dataset.

### Metric

**Mean Electric Range: 37.40 miles**

### 📊 Visualization

![Mean Electric Range](## 🧹 Data Cleaning & Preprocessing

Data cleaning and preprocessing were performed to improve data quality and prepare the dataset for further analysis.

The following steps were performed:

- Inspected the dataset structure and dimensions.
- Checked column names and data types.
- Identified missing values across the dataset.
- Checked for duplicate records.
- Handled missing values in categorical columns using appropriate imputation techniques.
- Verified numerical and categorical variables before analysis.
- Prepared the cleaned dataset for Exploratory Data Analysis and visualization.

These preprocessing steps helped ensure that the dataset was suitable for statistical analysis and data visualization.

## 📊 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the structure, distribution, and key characteristics of the Electric Vehicle dataset.

The analysis focused on the following areas:

- Dataset structure and dimensions
- Data types and variable identification
- Missing value analysis
- Duplicate record analysis
- Descriptive statistics
- Electric Vehicle Type distribution
- Electric Range distribution
- Top EV manufacturers
- Model Year distribution
- CAFV Eligibility distribution
- County-level EV population

EDA helped identify important patterns and characteristics in the dataset and provided a foundation for further statistical analysis and visualization.

## 📈 Statistical Analysis Metrics

Statistical analysis was performed on the Electric Range variable to understand its central tendency, variability, and distribution shape.

The following statistical measures were calculated:

| Metric | Value | Interpretation |
|---|---:|---|
| Mean | 37.40 miles | Represents the average Electric Range of the vehicles. |
| Median | 0 miles | Represents the middle value of the Electric Range data. |
| Mode | 0 miles | Represents the most frequently occurring Electric Range value. |
| Variance | 5889.14 | Measures the overall variability of Electric Range values. |
| Standard Deviation | 76.74 miles | Indicates the typical spread of Electric Range around the mean. |
| Skewness | 2.23 | Indicates a positively skewed Electric Range distribution. |
| Kurtosis | 3.67 | Indicates relatively heavier tails and the presence of extreme observations. |

### 📌 Key Statistical Insights

- The **Mean (37.40 miles) is higher than the Median (0 miles)**, indicating that the Electric Range distribution is strongly influenced by higher-range observations.
- The **Mode of 0 miles** shows that zero is the most frequently occurring Electric Range value.
- The **Standard Deviation of 76.74 miles** indicates considerable variation in Electric Range across vehicles.
- The **positive Skewness value of 2.23** indicates that the distribution has a longer tail towards higher Electric Range values.
- The **Kurtosis value of 3.67** indicates the presence of relatively heavy tails and extreme observations.
- Overall, the statistical measures indicate considerable variability and a positively skewed Electric Range distribution.

## 📌 Mean Electric Range

The mean represents the average Electric Range of the vehicles in the dataset.

### Metric

**Mean Electric Range: 37.40 miles**

### 📊 Visualization

<img width="941" height="611" alt="Mean Electric Range" src="https://github.com/user-attachments/assets/XXXX" />


### 🔍 Insight

The mean Electric Range is approximately **37.40 miles**, representing the average electric driving range across the vehicles in the dataset. Since the dataset contains a large number of low or zero-range observations along with some higher-range vehicles, the mean is influenced by the overall distribution of the data. Therefore, the mean should be interpreted together with the median and mode to obtain a clearer understanding of the Electric Range distribution.
