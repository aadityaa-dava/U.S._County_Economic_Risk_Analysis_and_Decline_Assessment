# Notebooks

This folder contains the Jupyter notebooks used throughout the DATA 606 Capstone project:

## Identifying U.S. Counties at Risk of Economic Decline Using Public Socioeconomic Indicators

The notebooks document the complete analytical workflow, from raw data preprocessing to economic risk modeling and interactive visualization development.

---

# Overview

The notebooks follow a structured end-to-end data science pipeline:

1. Data Cleaning and Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Economic Risk Modeling and Validation  
4. Visualization and Streamlit Application Integration  

Each notebook builds upon the previous stage to create a reproducible and interpretable workflow for county-level economic risk analysis.

---

# Folder Structure

```text
notebooks/
│
├── 01_cleaning_preprocessing.ipynb
├── 02_eda_economic_risk.ipynb
├── 03_economic_risk_modeling.ipynb
├── 04_visualization_streamlit.ipynb
└── README.md
```

---

# Notebook Descriptions

## `01_cleaning_preprocessing.ipynb`

This notebook focuses on data preparation and integration.

### Key Tasks
- Loads raw ACS datasets
- Cleans and standardizes variables
- Handles missing and inconsistent values
- Merges datasets using `county_fips`
- Performs feature engineering and transformations
- Creates the unified county-level dataset

### Output
```text
county_master.csv
```

---

## `02_eda_economic_risk.ipynb`

This notebook performs exploratory analysis of socioeconomic indicators across U.S. counties.

### Key Tasks
- Generates descriptive statistics
- Explores variable distributions
- Analyzes regional disparities
- Creates interactive visualizations
- Identifies relationships between indicators

### Tools Used
- Plotly
- Pandas
- NumPy

---

## `03_economic_risk_modeling.ipynb`

This notebook develops the economic risk framework used in the project.

### Key Tasks
- Constructs the economic risk score
- Combines multiple socioeconomic indicators
- Categorizes counties into:
  - Low Risk
  - Medium Risk
  - High Risk
- Evaluates and validates scoring methodology
- Identifies key drivers of economic decline

---

## `04_visualization_streamlit.ipynb`

This notebook prepares the final outputs for the Streamlit application.

### Key Tasks
- Generates application-ready visualizations
- Prepares dashboard-compatible datasets
- Exports final processed data
- Supports interactive analytics integration

### Output
```text
county_risk_app_ready.csv
```

---

# Workflow Summary

```text
Raw ACS Data
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Economic Risk Modeling
      ↓
Final Processed Dataset
      ↓
Streamlit Dashboard Application
```

---

# Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- Scikit-learn
- Jupyter Notebook

---

# Purpose

These notebooks demonstrate a complete and reproducible data science workflow for analyzing county-level socioeconomic conditions and identifying economic risk patterns.

The notebooks support:
- Academic research and analysis
- Data preprocessing and feature engineering
- Exploratory and statistical analysis
- Interpretable modeling approaches
- Interactive dashboard integration
