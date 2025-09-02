🏗️ Toronto Building Permits (TBP) Analysis

This repository contains a Jupyter Notebook that analyzes the Toronto Building Permits dataset. The project demonstrates a full workflow: data loading, cleaning, exploratory analysis, visualization, anomaly detection, and extended advanced techniques.

📂 Project Overview
The notebook walks through the following steps:
1.  Data Loading
      -  Loads the Toronto Building Permits dataset (Toronto Building Permits.csv) into a Pandas DataFrame.
2.  Missing Values Analysis
      -  Visualizes missing data using heatmaps.
      -  Counts and lists missing values per column.
3.  Exploratory Data Analysis (EDA)
      -  Summarizes dataset statistics.
      -  Plots categorical and numerical features for better understanding.
      -  Identifies trends and distributions of key attributes.
4.  Outlier & Anomaly Detection
      -  Uses Isolation Forest to detect unusual records.
      -  Applies Z-Score analysis for extreme outliers.
      -  Visualizes anomalies.
5.  Data Visualization
      -  Histograms, boxplots, scatter plots.
      -  Highlights anomalies visually.
6.  Future Improvements (Advanced Section)
      -  Automated preprocessing (missing value imputation).
      -  Geospatial visualization with interactive maps (Folium).
      -  Advanced anomaly detection using Autoencoders.
      -  Interactive dashboards (Plotly Express).
      -  Time-series analysis for seasonal trends.

🛠️ Tech Stack
-  Languages & Libraries
    -  Python 3.x
    -  NumPy, Pandas
    -  Matplotlib, Seaborn
    -  Scikit-learn, SciPy
    -  Folium (maps)
    -  TensorFlow/Keras (Autoencoder anomaly detection)
    -  Plotly Express (interactive dashboards)

📊 Dataset
  -  Source: Toronto Building Permits dataset
  -  Format: CSV file (excel_work-data/Toronto Building Permits.csv)
  -  Content: Permit details including type, status, application/issue dates, and construction info.

🚀 How to Run
  -  Clone this repository:
        -  git clone <your-repo-url>
        -  cd TBP_analysis
  -  Install dependencies:
        -  pip install -r requirements.txt
  -  Launch Jupyter Notebook:
        -  jupyter notebook
  -  Open TBP_analysis_future.ipynb and run the cells step by step.

📈 Key Insights
  -  Identified missing data patterns.
  -  Highlighted most common permit categories and trends.
  -  Detected anomalies with Isolation Forest, Z-Score, and Autoencoders.
  -  Mapped permits on an interactive Toronto map.
  -  Built dashboards and explored monthly trends in applications.

🔮 Future Work
  -  Deploy dashboards as a web app (Dash or Streamlit).
  -  Integrate real-time permit data (if available via API).
  -  Enhance anomaly detection with clustering (DBSCAN, LOF).
  -  Expand geospatial analysis (heatmaps, zoning overlays).

📌 Author
      - This notebook was created for exploratory analysis of Toronto Building Permits.
