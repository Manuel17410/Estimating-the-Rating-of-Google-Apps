# Customer-Segmentation: Analyzing Behavior of Credit Card Users for Targeted Marketing

- **Objective**: Develop a machine learning model to predict user ratings of Google Play apps based on various app features.

- **Analysis**: Examine features such as app category, size, price, and user feedback to identify key factors influencing app ratings.

- **Model**: The models tested are Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Support Vector Machine.

- **Impact**: Provide a robust predictive model that helps developers and stakeholders understand the factors affecting app ratings and improve app quality and user satisfaction.

## Resources Used

**Python Version**: 3.12.1

**Packages**: pandas,numpy,sklearn,matplotlib,seaborn,scipy

**Dataset**: https://www.kaggle.com/datasets/lava18/google-play-store-apps

## Data Cleaning

The process was not really straight forward since the data was quite messy. I made the following changes in the dataset.

- 474 duplicated rows were eliminated
- Column "Reviews" was converted to numeric and the symbols were eliminated
- Column "Last Updated" was set to be datetime type
- Column "Price" was converted to numeric, moreover the dollar sign and the commas were eliminated
- Column "Installs" was converted to numeric, and the plus signs were eliminated
- The Column "Size" had values in different k and M, so it was necessary to make them comparable. Moreover, it was converted to float.
- Outliers were eliminated
- Columns "App", "Current Ver", "Android Ver" and "Last Updated" were dropped, since they do not add any value to the analysis

## EDA

Many different graphs were made to understand the dataset better. Below some of them. 


