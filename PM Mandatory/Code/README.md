# Air Quality Data Analysis

This notebook contains a set of Python scripts that analyze air quality data collected from multiple sensors. The main objectives of the analysis are to clean the data, evaluate sensor performance, and assess feature importance for predicting PM2.5 concentrations using machine learning. The analysis includes the following major tasks:

- **Data Preprocessing**: Remove outliers and clean data for analysis.
- **Performance Evaluation**: Calculate and compare model performance metrics.
- **Feature Importance**: Use LightGBM to analyze feature importance for predicting PM2.5 concentrations.
- **Visualization**: Generate plots to visualize data distributions, performance metrics, and feature importances.
- **Data Grouping & Concatenation**: Handle data grouped by location and sensor.

## Requirements

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - lightgbm