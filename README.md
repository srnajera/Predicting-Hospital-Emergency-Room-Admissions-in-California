# Predicting Hospital Emergency Room Admissions in California

## Overview
This project aimed to leverage predictive analytics to forecast daily Emergency Room (ER) admissions across hospitals in California. By focusing on hospital characteristics such as type, size, and location, the project sought to improve resource allocation, reduce patient wait times, and enhance the overall efficiency of hospital operations.

## Objective
The primary goal was to explore the intricacies of ER admissions, identifying key patterns, drivers, and temporal trends. Through this analysis, we hoped to gain insights to assist in staffing decisions, optimized resource allocation, and effective hospital management strategies, ultimately contributing to more efficient and patient-focused healthcare service delivery.

## Data Source
The analysis utilized comprehensive data from the California Health and Human Services Agency, covering 439 hospitals. This dataset included crucial operational metrics like daily ER admissions, offering a deep dive into the state's healthcare system's operational facets.

## Methodology
- **Data Preparation:** The dataset was cleaned and preprocessed, focusing on ER-related metrics. Feature selection and scaling were applied to prepare the data for modeling.
- **Exploratory Data Analysis (EDA):** A thorough EDA phase utilized PCA, scatter plots, and correlation heatmaps to understand data structure and relationships.
- **Model Building:** A combination of RandomForestRegressor, LightGBM, and a Stacked Ensemble model was used for predicting ER visits, with models evaluated based on MSE and R² metrics.

## Key Findings
- **Predictive Insights:** Net patient revenue and gross patient revenue emerged as significant predictors of ER visits, alongside operational metrics like bed availability and staffing.
- **Model Performance:** The Stacked Ensemble model demonstrated superior predictive accuracy, highlighting the potential for predictive models to aid in strategic planning and resource allocation for ER operations.

## Ethical Considerations
The project adhered to strict data privacy guidelines and aimed to mitigate potential biases within the dataset, ensuring ethical and reliable model predictions.

## Recommendations
- Integrate predictive models into hospital information systems for real-time analytics.

## Conclusion
The project underscores the importance of predictive analytics in healthcare, showcasing how data-driven insights can enhance operational efficiency and patient care in hospital emergency rooms. The findings suggest that predictive models can be invaluable tools for hospital management, aiding in resource allocation and strategic planning.

## References
- California Health and Human Services Agency. (2024). Hospital Data. Retrieved from [California Health and Human Services](https://data.chhs.ca.gov/).
