# ⚡ Electric Vehicle Population Data Analysis Using Python

> An end-to-end data analysis project exploring Electric Vehicle Population data using Python, Pandas, NumPy, Matplotlib, and Seaborn.

## 📌 Project Overview

The **Electric Vehicle Population Data Analysis Using Python** project focuses on analyzing electric vehicle registration data from **Washington State, USA**.

The project explores key characteristics of electric vehicles, including **Electric Vehicle Type, Manufacturer, Model Year, Electric Range, County, and CAFV Eligibility**.

The analysis follows a complete data analytics workflow, starting from **data inspection and data cleaning**, followed by **data transformation, feature engineering, statistical analysis, exploratory data analysis, visualization, bivariate analysis, and multivariate analysis**.

The main objective is to identify meaningful patterns and insights from the dataset that can support **electric vehicle market analysis, charging infrastructure planning, and data-driven decision-making**.

## 🎯 Project Objectives

The main objective of this project is to analyze the **Electric Vehicle Population Data** using Python and identify meaningful patterns in electric vehicle adoption.

### Key Objectives

- Analyze the distribution of **Electric Vehicle Types**.
- Identify the **top EV manufacturers**.
- Study EV distribution across **Model Years**.
- Analyze **Electric Range**.
- Identify counties with the **highest EV population**.
- Analyze **CAFV Eligibility**.
- Compare EV characteristics using **statistical analysis and visualization**.
- Generate insights to support **EV infrastructure planning and data-driven decision-making**.

## 📊 Dataset Information

The dataset used in this project is the **Electric Vehicle Population Data**, obtained from **Data.gov**.

| Feature | Details |
|---|---|
| **Dataset** | Electric Vehicle Population Data |
| **Source** | Data.gov |
| **Location** | Washington State, USA |
| **Records** | 289,564 |
| **Columns** | 16 |
| **Domain** | Electric Vehicles / Transportation |

### Key Variables

- Electric Vehicle Type
- Make
- Model
- Model Year
- Electric Range
- County
- City
- CAFV Eligibility

### 🔗 Data Source

[Electric Vehicle Population Data – Data.gov](https://catalog.data.gov/dataset/electric-vehicle-population-data)

## 🛠️ Tools & Technologies

### Programming Language
- **Python**

### Environment
- **Google Colab**

### Libraries
- **Pandas** – Data cleaning and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization

### Analysis Techniques
- Data Cleaning
- Data Transformation
- Feature Engineering
- Statistical Analysis
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Data Visualization

## 🔄 Project Workflow

The project follows a structured data analysis workflow:

**Data Collection → Data Cleaning → Data Transformation → Feature Engineering → Statistical Analysis → Data Visualization → Univariate Analysis → Bivariate Analysis → Multivariate Analysis → Insights & Recommendations**

## 🔍 Data Loading & Initial Inspection

The dataset was loaded using **Pandas** and initially inspected to understand its structure, data types, and overall quality.

The initial inspection included:

- Dataset shape and column information
- Data types
- Missing values
- Duplicate records
- Descriptive statistics

## 🧹 Data Cleaning

The dataset was cleaned and prepared before performing the analysis.

The main data cleaning steps included:

- Checking for missing values
- Checking for duplicate records
- Handling missing values where required
- Removing unnecessary columns
- Ensuring the data was suitable for further analysis

After cleaning, the dataset was prepared for **data transformation, statistical analysis, and visualization**.

## 🔄 Data Transformation & Feature Engineering

After cleaning the dataset, additional transformations were performed to make the data more useful for analysis.

### Data Transformation

A new **Vehicle Age** feature was created using the Model Year to understand the age of the registered vehicles.

### Feature Engineering

A **Range Category** feature was created by grouping vehicles based on their Electric Range:

- 0–100 miles
- 101–200 miles
- 201–300 miles
- 301–400 miles
- 400+ miles

These derived features were used to support further **statistical analysis and visualization**.

## 📐 Statistical Analysis

Statistical analysis was performed to understand the **central tendency and variability** of important numerical variables in the dataset.

### Measures of Central Tendency

The following measures were calculated:

- **Mean**
- **Median**
- **Mode**

The analysis was performed for:

- Electric Range
  <img width="1009" height="618" alt="Screenshot 2026-09-08 180020" src="https://github.com/user-attachments/assets/e475cc6e-8f6e-4a20-8936-3119e01a5ae1" />

- Model Year
  <img width="1001" height="617" alt="Screenshot 2026-09-08 180059" src="https://github.com/user-attachments/assets/fec7a7e9-682b-4fd0-b811-0051d4be9e8f" />

- Vehicle Age
  <img width="1003" height="620" alt="Screenshot 2026-09-08 180126" src="https://github.com/user-attachments/assets/322c37cf-d33c-4116-aea8-e2e800c5191e" />


### Measures of Dispersion

To understand the variability in the data, the following were analyzed:

- **Variance**
<img width="999" height="614" alt="Screenshot 2026-09-08 200759" src="https://github.com/user-attachments/assets/13095db3-8f1f-405a-ba41-d45fd71c5f2c" />
<img width="993" height="607" alt="Screenshot 2026-09-08 200817" src="https://github.com/user-attachments/assets/067f443b-e2f2-46ec-ac1c-a6d38f716380" />
<img width="994" height="610" alt="Screenshot 2026-09-08 200835" src="https://github.com/user-attachments/assets/0e3435fa-2f12-467d-af17-5aa1c222923d" />


- **Standard Deviation**
  <img width="1254" height="619" alt="Screenshot 2026-09-08 202132" src="https://github.com/user-attachments/assets/1047b0c5-dc87-498b-a031-ad982ece96d7" />
  <img width="1252" height="611" alt="Screenshot 2026-09-08 202156" src="https://github.com/user-attachments/assets/b4a926bf-6b2a-4027-a59a-bff45bba929c" />
  <img width="1248" height="615" alt="Screenshot 2026-09-08 202209" src="https://github.com/user-attachments/assets/87450676-ec19-4a61-9654-8d38c14bf34f" />


The results showed that **Electric Range has higher variability**, while Model Year and Vehicle Age are more concentrated around recent values.

## 📊 Univariate Analysis

Univariate analysis was performed to understand the distribution of individual variables in the dataset.

The following variables were analyzed:

- **Electric Range**
  <img width="1110" height="697" alt="Screenshot 2026-09-08 204647" src="https://github.com/user-attachments/assets/58da06a8-a4ae-463c-a861-1582540261e4" />

- **Electric Vehicle Type**
  <img width="922" height="686" alt="Screenshot 2026-09-08 204850" src="https://github.com/user-attachments/assets/c5eb80bb-4704-47d1-9f32-0114cc439157" />

- **Top 10 Manufacturers**
  <img width="1166" height="699" alt="Screenshot 2026-09-08 211118" src="https://github.com/user-attachments/assets/70bb6193-30fc-499d-b83d-bf518f6a71bd" />
- **Model Year**
  <img width="1115" height="696" alt="Screenshot 2026-09-08 211257" src="https://github.com/user-attachments/assets/ac4ff891-bd13-4af2-98d8-8b5358555c1b" />
- **CAFV Eligibility**
  <img width="1585" height="687" alt="Screenshot 2026-09-08 211637" src="https://github.com/user-attachments/assets/52584386-6c15-4d12-9a0a-3225a8d71a75" />
The analysis used appropriate charts and visualizations to identify the most common categories, distributions, and patterns within each variable.

## 🔗 Bivariate Analysis

Bivariate analysis was performed to understand the relationship between two variables and identify meaningful patterns in the dataset.

The following relationships were analyzed:

- **EV Type vs Electric Range**
  <img width="1076" height="697" alt="Screenshot 2026-09-08 211924" src="https://github.com/user-attachments/assets/0701015e-f777-4cec-b245-f3ac127c337e" />

- **Model Year vs Electric Range**
  <img width="1084" height="696" alt="Screenshot 2026-09-08 213416" src="https://github.com/user-attachments/assets/9bc9f408-1052-4270-8851-7e6acb1c94c6" />

- **Manufacturer vs EV Type**
  <img width="1366" height="699" alt="Screenshot 2026-09-08 213727" src="https://github.com/user-attachments/assets/66efcc6f-9269-4aac-a286-0a1d3a3bd383" />

- **County vs EV Population**
<img width="1142" height="691" alt="Screenshot 2026-09-08 213920" src="https://github.com/user-attachments/assets/8c696686-5dc6-40ed-bd55-e0604e99d6ee" />

These relationships were explored using suitable visualizations such as **box plots, scatter plots, and comparison charts**.

## 🔬 Multivariate Analysis

Multivariate analysis was performed to understand patterns involving **multiple variables simultaneously**.

The following relationships were analyzed:

- **Model Year + Electric Range + EV Type**
  <img width="1077" height="696" alt="Screenshot 2026-09-08 214607" src="https://github.com/user-attachments/assets/e08a1a7a-e0b2-4e0c-ac8a-b2d480bc343b" />

- **Manufacturer + Electric Range + EV Type**
  <img width="1273" height="885" alt="Screenshot 2026-09-08 214633" src="https://github.com/user-attachments/assets/5ff4a103-7bc7-4c8d-b1ee-e156a4bce883" />

- **County + EV Type + EV Population**
  <img width="1336" height="800" alt="Screenshot 2026-09-08 214653" src="https://github.com/user-attachments/assets/77f651d6-ea6e-42ce-9ad3-6649667418f2" />


These visualizations help provide a deeper understanding of how vehicle characteristics vary across different **vehicle types, manufacturers, model years, and locations**.

## 💡 Key Insights & Findings

The analysis revealed several important patterns in the Electric Vehicle Population dataset:

- 🔋 **BEVs dominate the dataset**, with significantly more registrations than PHEVs.
- 🏭 **Tesla has the highest representation** among the manufacturers analyzed.
- 📅 **Recent Model Years are strongly represented**, indicating a large presence of newer EVs.
- 📈 **Electric Range shows high variability** across vehicles.
- 📍 **EV adoption is geographically concentrated**, with King County having the highest EV population.
- 🔄 **Electric Range varies across EV Types, Manufacturers, and Model Years**, highlighting differences in vehicle characteristics.
- 🌱 The results provide useful insights for **EV market analysis and charging infrastructure planning**.

## 🧠 Recommendations / Decision Support

Based on the analysis, the following recommendations can be considered:

- 🔋 **Prioritize BEV-focused charging infrastructure** due to the higher representation of BEVs in the dataset.
- 📍 **Focus infrastructure planning on high-EV counties**, particularly areas with higher EV populations.
- ⚡ **Consider Electric Range differences** when planning charging facilities and understanding user requirements.
- 🏭 **Consider manufacturer and EV type patterns** for EV market and technology analysis.
- 📅 **Account for the growing presence of newer EV models** when planning future EV infrastructure.

## 🚀 Future Enhancements

This project can be further extended with the following improvements:

- 📊 **Interactive Dashboard** – Build an interactive dashboard using Power BI or Streamlit.
- 🤖 **Predictive Analysis** – Apply machine learning techniques to predict future EV adoption trends.
- 🗺️ **Geographical Analysis** – Use maps and heatmaps to identify EV adoption hotspots.
- 📐 **Advanced Statistical Analysis** – Apply additional statistical tests to explore relationships between variables.
- 📈 **Time-Series Analysis** – Analyze EV adoption trends across different time periods.

## 📁 Repository Structure

```text
Electric-Vehicle-Population-Data-Analysis/
│
├── README.md
├── Electric_Vehicle_Population_Data_Analysis_Using_Python.ipynb
├── Electric Vehicle Population Data.csv
│
├── assets/
│   ├── 05-statistical-analysis.png
│   ├── 07-electric-range-distribution.png
│   ├── 08-ev-type-distribution.png
│   ├── 09-top-manufacturers.png
│   ├── 10-model-year-distribution.png
│   ├── 11-cafv-eligibility.png
│   ├── 12-ev-type-vs-range.png
│   ├── 13-model-year-vs-range.png
│   ├── 14-manufacturer-vs-ev-type.png
│   ├── 15-top-counties.png
│   ├── 16-multivariate-model-year-range-type.png
│   ├── 17-multivariate-manufacturer-range-type.png
│   └── 18-multivariate-county-ev-type.png
│
└── requirements.txt

## 🏆 Conclusion

This project provides an end-to-end analysis of the **Electric Vehicle Population Data** using Python.

The analysis explored EV types, manufacturers, model years, electric range, CAFV eligibility, and county-level EV distribution through statistical analysis and data visualization.

The findings highlight the strong presence of **BEVs, newer EV models, major manufacturers, and geographically concentrated EV adoption**.

Overall, the project demonstrates how **Python and data analysis techniques** can be used to transform real-world data into meaningful insights for **EV market understanding and infrastructure planning**.


## 📚 Data Source

The dataset used for this project is the **Electric Vehicle Population Data** from **Data.gov**.

**Source:** Data.gov  
**Dataset:** Electric Vehicle Population Data  
**Location:** Washington State, USA

🔗 [View Dataset on Data.gov](https://catalog.data.gov/dataset/electric-vehicle-population-data)


## 👩‍💻 Author

### Atchaya Chandran

**Project:** Electric Vehicle Population Data Analysis Using Python

### Skills Demonstrated

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data Cleaning
- Data Analysis
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization

## 📓 Google Colab Notebook

The complete Python analysis and visualizations are available in the Google Colab notebook.

🔗 **[Open the Project in Google Colab](https://colab.research.google.com/drive/1kXHWte1I9nrKJQNyXIEBCOLWz1P8hP6X?usp=sharing)**

