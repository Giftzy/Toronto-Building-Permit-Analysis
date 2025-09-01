# Toronto Building Permit Analysis

Overview

This notebook analyzes Toronto Building Permit (TBP) data to identify trends, visualize distributions, handle missing values, and detect anomalies using machine learning methods.
The workflow covers data loading, cleaning, visualization, and anomaly detection.

Key Steps

  1.  Data Loading
        -  Reads the Toronto Building Permits dataset from CSV into a Pandas DataFrame.
  2.  Exploratory Data Analysis (EDA)
        -  Inspects data structure, missing values, and distributions.
        -  Provides summary statistics.
  3.  Data Cleaning
        .  Handles missing values (e.g., filling with zeros).
        .  Prepares dataset for further analysis.
  4.  Visualization
        .  Heatmaps for missing values.
        .  Pair plots of key features segmented by permit type.
        .  Distribution plots for permit categories.
  5.  Outlier & Anomaly Detection
        .  Applies Isolation Forest (sklearn) to detect anomalies in building permits data.
        .  Compares with statistical methods (e.g., z-scores via scipy.stats).

Technologies Used
  .  Python
  .  Libraries:
        .  numpy, pandas – data handling
        .  matplotlib, seaborn – visualization
        .  scipy – statistical analysis
        .  sklearn – anomaly detection (Isolation Forest)

File Structure
  .  TBP_analysis.ipynb – main notebook containing analysis.
  .  Toronto Building Permits.csv – dataset (not included here, ensure it is placed in the same directory).

How to Run
  .Install dependencies:
        pip install numpy pandas matplotlib seaborn scikit-learn scipy
  .  Place the dataset Toronto Building Permits.csv in the working directory.
  .  Open and run the notebook:
  .  jupyter notebook TBP_analysis.ipynb

Results
    .  Visual insights into permit types and distributions.
    .  Identification of missing values and cleaned dataset.
    .  Outlier detection highlighting unusual permits or patterns.

Future Improvements
    .  Advanced ML Models: Use clustering (DBSCAN, K-Means) for anomaly grouping.
    .  Feature Engineering: Extract temporal features (year, month) and geospatial insights.
    .  Interactive Dashboards: Use Plotly or Dash for dynamic exploration.
    .  Model Validation: Apply cross-validation and compare anomaly detection methods.

Scalability: Transition analysis pipeline into a reusable Python module or ETL workflow.

Geospatial Analysis: Map permit locations with Folium or GeoPandas for better urban insights.
