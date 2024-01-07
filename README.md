# Recession-Analysis

## Overview
This repository contains an economic analysis of the United Kingdom's GDP growth, with the aim to visualize the fluctuations in the economy and identify periods of recession. The project uses monthly GDP data to generate a heatmap for initial visual assessment, converts this data to a quarterly scale for standard recession analysis, and highlights the duration and severity of each recession period.

## Dependencies
- Pandas
- Plotly

These Python libraries are used to process the data and create interactive visualizations that allow for an in-depth look at the UK's economic performance.

## Data
The dataset `UK_monthly_gdp.csv` includes the UK's monthly GDP growth rates. This data is critical for understanding the economic health of the nation and identifying trends over time.

## Preprocessing
The data is loaded into a Pandas DataFrame, with datetime conversions applied to facilitate the resampling of monthly data into quarterly data, which is the standard measure for assessing recessions.

## Model Training and Evaluation
This project does not involve traditional machine learning models but instead focuses on data transformation and visualization to evaluate economic conditions.

## Usage
To replicate the analysis:
1. Install the required dependencies.
2. Load the dataset using Pandas.
3. Follow the code to preprocess the data and generate visualizations.

## Results
The project's outputs include:
- A heatmap showcasing the changes in GDP growth over time, with color intensity indicating the growth magnitude.
- A line chart that overlays recession periods, providing a clear visual representation of economic downturns.
- A bar chart detailing the duration and severity of each recession, offering insights into the relative impact of each economic contraction.

This analysis provides a visual narrative of the UK's recent economic history, highlighting the challenges faced during recessionary periods and offering a foundation for further economic study or policy development.
