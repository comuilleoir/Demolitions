# Demolition Notification Analysis Using Data Analytics

## Project Overview
This project investigates patterns in demolition activities to aid urban development and planning. It merges demolition notice data with city-wide criminal incident reports to predict property vacancy or abandonment. The analysis utilizes data from January 2009 to April 2015, focusing on the City of Detroit.

## Methodology
- **Data Sources:** Demolition notifications from the Ferndale City Open Data site and city-wide criminal incident reports from Detroit.
- **Data Analytics Techniques:** Techniques include data preprocessing, normalisation, exploratory data analysis, and Random Forest modeling. A special focus is placed on balancing the model and incorporating crime data.
- **Visualization Tools:** Python’s Matplotlib and seaborn for data visualisation, highlighting patterns in demolition and crime data.

## Key Findings
- Identification of key geographical patterns in demolition activities and their correlation with crime rates.
- Despite model optimisations, challenges in predicting property status with high accuracy were observed, indicating the complexity of urban dynamics.

## Repository Contents
- `Data`: Original and preprocessed datasets of demolition notifications. The crime data file is too large for Github, but is available at https://data.world/detroit/dpd-crime-incidents-2009-2016
- `Scripts`: Python scripts and Jupyter notebooks for data cleaning, analysis, modeling, and visualisation.
- `Project_Images`: Generated graphs and charts illustrating demolition trends and their correlation with crime data.

## Images and Visualisations

### Data Analysis Visualisations

Geospacial Plot of Demolition Notifications

![Geospacial Plot](https://github.com/comuilleoir/Demolitions/blob/main/Project_Images/geospacial_dist.png)

Optimised Random Forest Confusion Matrix

![Optimised Random Forest Confusion Matrix](https://github.com/comuilleoir/Demolitions/blob/main/Project_Images/demos_conf_matrix.png)

### Insights and Correlations

Feature Importance Ranking

![Feature Importance Ranking](https://github.com/comuilleoir/Demolitions/blob/main/Project_Images/feat_import.png)

Reduced Level Random Forest Model Plot

![Reduced Level Random Forest Model Plot](https://github.com/comuilleoir/Demolitions/blob/main/Project_Images/small_tree.png)

## Conclusion
The project highlights the complex relationship between urban demolition activities and crime rates. While predictive modeling provides insights, the findings suggest a need for more nuanced data and advanced modeling techniques for more accurate predictions.
