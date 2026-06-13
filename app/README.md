# Streamlit Dashboard Application

## Overview

This folder contains the interactive Streamlit dashboard developed for the DATA 606 Capstone project:

### Identifying U.S. Counties at Risk of Economic Decline Using Public Socioeconomic Indicators

The dashboard transforms county-level socioeconomic data into an interactive analytical platform that enables users to explore economic conditions across the United States, evaluate county risk levels, and identify regional patterns of economic vulnerability.

The application integrates socioeconomic indicators, economic risk scores, interactive visualizations, and geographic analysis into a single user-friendly interface.

---

## Dashboard Features

The Streamlit application provides:

* Interactive county-level economic risk analysis
* U.S. county economic risk map visualization
* Economic risk score exploration
* Risk category segmentation (Low, Medium, High Risk)
* State-level filtering and comparison
* Socioeconomic indicator analysis
* Dynamic charts and visualizations
* Summary metrics and key insights

---

## Data Used

The application uses the processed dataset:

```text
county_risk_app_ready.csv
```

The dataset contains county-level socioeconomic indicators including:

* Total Population
* Median Household Income
* Poverty Rate
* Unemployment Rate
* Educational Attainment
* Homeownership Rate
* Economic Risk Score
* Economic Risk Category

---

## Dashboard Components

### Executive Summary Metrics

Provides a high-level overview of:

* Total Counties Analyzed
* Average Economic Risk Score
* High-Risk County Count

### County Economic Risk Map

Interactive visualization displaying:

* County-level risk classifications
* Geographic distribution of economic vulnerability
* Risk category comparisons across regions

### Socioeconomic Analysis

Allows users to:

* Explore economic indicators by county
* Compare risk categories
* Identify regional socioeconomic trends
* Analyze relationships between key indicators

### Interactive Filters

Users can dynamically filter data by:

* State
* Risk Category

---

## Technologies Used

* Streamlit
* Pandas
* NumPy
* Plotly
* Scikit-Learn

---

## Running the Application

### 1. Clone the Repository

```bash
git clone https://github.com/aadityaa-dava/us-county-economic-risk-dashboard.git
cd us-county-economic-risk-dashboard
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the Dashboard

```bash
streamlit run app/app.py
```

---

## Live Dashboard

Access the deployed application:

https://umbc-data606-capstone-analysis.streamlit.app

---

## Folder Structure

```text
app/
│
├── app.py
└── README.md
```

| File        | Description                          |
| ----------- | ------------------------------------ |
| `app.py`    | Main Streamlit dashboard application |
| `README.md` | Application documentation            |

---

## Dashboard Capabilities

The dashboard enables users to:

* Explore county-level socioeconomic conditions
* Visualize economic risk across the United States
* Compare counties using multiple indicators
* Analyze economic vulnerability patterns
* Investigate regional disparities
* Interact with dynamic filters and charts

---

## Purpose

The application was developed to make county-level socioeconomic data more accessible, interpretable, and actionable through interactive analytics and visual storytelling.

It demonstrates how publicly available Census data can be transformed into meaningful insights that support economic analysis, regional planning, policy evaluation, and community development initiatives.
