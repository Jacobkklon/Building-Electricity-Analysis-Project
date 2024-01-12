# Building-Electricity-Analysis-Project'

In this project I analyzed data describing the energy consumption of an apartment and office building. 

This project includes the following high-level steps:

- Analyzing corelation between HVAC demand and seasonal behavior in order to account for seasonality in the data
- Training and tested multi-variable linear regression models for predicting HVAC energy demand for each building
- Leveraging One-Hot encoding to create new categorical variables in order to encorporate seasonality into my regression models as a variable, mapping certain categorical/qualitative values to numerical values in a dataframe via Pandas
- I then extended beyond linear regression models and evaluated performance of some more advanced ML regression models, including an boosting regressor, a bagging regressor, support vector machines, and random forest regression. The final output of this analysis was a selected model for use in predicting HVAC energy demand.
