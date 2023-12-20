# Demolition Notification Analysis Using Data Analytics

## Project Overview
This project investigates patterns in demolition activities to aid urban development and planning in the City of Detroit. By merging demolition notice data with city-wide criminal incident reports, it aims to predict property vacancy or abandonment. The analysis covers data from January 2009 to April 2015.

## Methodology
- **Data Sources:** Demolition notifications from the Ferndale City Open Data site and Detroit's city-wide criminal incident reports.
- **Data Analytics Techniques:** The process involves data preprocessing, normalization, exploratory data analysis, and modeling with a Random Forest algorithm. Special attention is given to model balancing and the integration of crime data.
- **Visualization Tools:** Utilizing Python’s Matplotlib and seaborn to visualize patterns in demolition and crime data.

## Key Findings
- **Geographical Patterns:** Identified key geographical patterns in demolition activities and their correlation with crime rates.
- **Modeling Challenges:** Despite efforts in model optimization, including bagging techniques, challenges in accurately predicting property status were observed. This underlines the complexity of urban dynamics and the possible need for additional data.
- **Reduced Scope:** Given the limitations in improving model performance with existing data, a decision was made to reduce the scope of the outcomes.

## Repository Contents
- `Data`: Original and preprocessed datasets of demolition notifications. The crime data file is too large for Github but is available [here](https://data.world/detroit/dpd-crime-incidents-2009-2016).
- `Scripts`: Python scripts and Jupyter notebooks for data cleaning, analysis, modeling, and visualization.
- `Project_Images`: Graphs and charts illustrating demolition trends and their correlation with crime data.

## Images and Visualisations

### Data Analysis Visualisations

Geospatial Plot of Demolition Notifications
![Geospatial Plot](https://github.com/comuilleoir/Demolitions/blob/main/Project_Images/geospacial_dist.png)

Optimized Random Forest Confusion Matrix
![Optimized Random Forest Confusion Matrix](https://github.com/comuilleoir/Demolitions/blob/main/Project_Images/demos_conf_matrix.png)

### Insights and Correlations

Feature Importance Ranking
![Feature Importance Ranking](https://github.com/comuilleoir/Demolitions/blob/main/Project_Images/feat_import.png)

Reduced Level Random Forest Model Plot
![Reduced Level Random Forest Model Plot](https://github.com/comuilleoir/Demolitions/blob/main/Project_Images/small_tree.png)

## Conclusion
The project highlights the complex interplay between urban demolition activities and crime rates. While predictive modeling offers valuable insights, the findings emphasize the need for more nuanced data and advanced modeling techniques for more accurate predictions.
