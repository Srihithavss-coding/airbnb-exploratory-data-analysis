# Airbnb Exploratory Data Analysis (NYC)

A detailed data cleaning and exploratory data analysis (EDA) project on New York City Airbnb listings, covering data from 2013 to 2023. This project focuses on understanding listing distributions, pricing patterns, geographical trends, and review activity through data preprocessing and visualization.

## 📌 Project Overview

Airbnb has transformed the short-term rental market by allowing property owners to offer accommodations to travelers. Analyzing Airbnb listing data helps uncover patterns in pricing, geographical distribution, availability, and customer engagement.

This project explores Airbnb data from New York City (NYC) to identify meaningful patterns, address data quality issues, and derive insights that can support further statistical analysis and predictive modeling.

## 🎯 Objectives

- Clean and preprocess raw Airbnb listing data.
- Identify and handle missing values, duplicates, and invalid records.
- Analyze pricing patterns across room types and neighbourhood groups.
- Explore the geographical distribution of Airbnb listings.
- Investigate historical review activity and seasonal trends.
- Prepare a consistent dataset for further analysis and modeling.

## 🛠️ Technologies Used

- **Python** – Data analysis and preprocessing
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis and documentation

## 📂 Project Workflow

### 1. Data Loading and Inspection
- Loaded the raw Airbnb dataset.
- Examined dataset dimensions, column names, and data types.
- Reviewed summary statistics and missing-value distributions.

### 2. Data Cleaning and Preprocessing
- Identified and handled missing and inconsistent values.
- Investigated duplicate records and potential anomalies.
- Addressed negative minimum-night values.
- Reviewed invalid future review dates.
- Corrected or excluded records with annual availability exceeding 365 days.
- Investigated unusual pricing patterns and suspicious placeholder values.

### 3. Exploratory Data Analysis
- Examined listing distributions across neighbourhood groups.
- Compared prices across room types and geographical areas.
- Analyzed review activity over time.
- Investigated seasonal patterns and changes in customer engagement.
- Used visualizations to identify trends, outliers, and potential data-quality issues.

## 📊 Key Findings and Insights

### 1. Uniform Pricing Structure
The analyzed dataset showed an identical median price of approximately **625** across room types and neighbourhood groups.

This unusual uniformity may indicate synthetic data, placeholder values, or other data-quality issues. It should not be interpreted as evidence that actual Airbnb prices are uniform across NYC.

### 2. Geographical Distribution
**Manhattan and Brooklyn** account for more than 80% of the listings in the analyzed dataset.

The Bronx and Staten Island represent much smaller shares, indicating that listings are concentrated in a few major geographical areas.

### 3. Historical Review Trends
Review activity generally increased from 2018 onward and peaked around mid-2019.

After excluding the August 2012 missing-data placeholder spike, the analysis showed a substantial decline during the COVID-19 pandemic period, followed by a partial recovery in late 2021.

These patterns describe the analyzed dataset and may not represent the entire NYC short-term rental market.

### 4. Improved Data Quality
Cleaning and validating anomalies, including negative minimum nights, future review dates, and availability values exceeding 365 days, helped improve dataset consistency.

The resulting dataset is better suited for exploratory analysis and potential downstream modeling.

## 💡 Overall Conclusion

The exploratory analysis highlights the concentration of Airbnb listings in Manhattan and Brooklyn, unusual uniformity in observed pricing, and changes in review activity over time.

The project also demonstrates the importance of data cleaning before drawing conclusions from real-world datasets. In particular, suspicious pricing patterns and historical anomalies must be investigated carefully to avoid misleading interpretations.

The cleaned dataset provides a foundation for additional analysis, including price prediction, neighbourhood comparisons, listing segmentation, and availability modeling.

## ⚙️ Installation and Setup

### Prerequisites
- Python 3.9 or later
- Jupyter Notebook or JupyterLab

### Steps

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd airbnb-exploratory-data-analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the project notebook and run the cells sequentially.

Ensure the dataset is available at the file path specified in the notebook.

## 📌 Limitations

- Uniform median prices may reflect data-quality problems rather than genuine market conditions.
- Missing or anomalous historical records may affect trend analysis.
- Observed patterns depend on the dataset's coverage, completeness, and preprocessing decisions.
- Correlation and descriptive patterns alone do not establish causation.

⭐ If you find this project useful, consider giving the repository a star!
