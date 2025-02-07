# AA2024


## Description

This project involves data analysis and predictive modeling for electric vehicle charging sessions. The project is divided into several parts, with the following order of execution:

1. **Data Preparation**: Cleaning and preparing the data for analysis.
2. **Descriptive Analytics**: Analyzing the data to understand patterns and trends.
3. **Cluster Analysis**: Grouping similar charging sessions together to identify different charging behaviors.
4. **Predictive Analysis**: Building predictive models to forecast future charging sessions.

## Data Preparation

The data preparation phase involves cleaning and transforming the raw data. This includes handling missing values, converting data types, and merging different datasets. The prepared data is saved in the `cleanData` directory.

- [data preparation/dataPreparation.ipynb](1_data%20preparation/dataPreparation.ipynb)
- [data preparation/weatherDataPrep.ipynb](1_data%20preparation/weatherDataPrep.ipynb)

## Descriptive Analytics

In this phase, we perform exploratory data analysis to understand the data better. This includes generating plots and summary statistics.

- [descriptive_analytics/descriptive_analytics_2a.ipynb](2_descriptive_analytics/descriptive_analytics_2a.ipynb)
- [descriptive_analytics/descriptive_analytics_2b.ipynb](2_descriptive_analytics/descriptive_analytics_2b.ipynb)

## Cluster Analysis

We perform cluster analysis to group similar charging sessions together. This helps in identifying different charging behaviors and optimizing the charging infrastructure.

- [ClusterAnalysis/Cluster_Analysis_complete.ipynb](3_clusterAnalysis/Cluster_Analysis_complete.ipynb)

## Predictive Analysis

We build predictive models to forecast future charging sessions. This includes time series analysis using ARIMA and machine learning models like Random Forest.

- [predictiveAnalysis/arima.ipynb](4_predictiveAnalysis/arima.ipynb)
- [predictiveAnalysis/predictive_analytics_dataPrep.ipynb](4_predictiveAnalysis/predictive_analytics_dataPrep.ipynb)

## Data Files


- `data preparation/`: Contains raw data files and notebooks for data preparation.
- `descriptive_analytics/`: Contains notebooks for descriptive analytics.
- `clusterAnalysis/`: Contains notebooks for cluster analysis.
- `predictiveAnalysis/`: Contains notebooks for predictive analysis.
- `cleanData/`: Contains cleaned data files.

## How to Run

1. Clone the repository.
2. Install the required dependencies.
3. Open the Jupyter notebooks in the respective directories to explore the analysis and models.

## Dependencies

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels
- ast
- keras
- scipy
- sklearn
- pmdarima