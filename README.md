# Pitney Bowes Data Challenge - Spring '21

![21-mktc-05288-pitneybowe-logo-1100x400-1](https://user-images.githubusercontent.com/82073881/151915766-8d8b5a71-5674-46dc-aff0-2615e36693b9.jpg)

**Context:**\
Pitney Bowes uses predictive maintenance to reduce down-times of mailing meters. Pitney Bowes' mailing meters are an integral part of their clients' business operations. As a result, they must be able to proactively identify potential complications early on to avoid service disruptions for their clients. Predictive maintenance allows the company to have the required replacement parts where they are needed. Additionally, predictive maintenance also allows the aforementioned company to proactively schedule appointments with customers if needed.

**Objective:**\
Using the training sample provided by the Pitney Bowes team, build a model that can reliably predict which meters will fail within the next 7 days (7 days from data collection). Defining the KPI's for measuring the performance of the model was left up to the team's discretion.

**Tools Used:**\
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Imblearn, Local Interpretable Model-Agnostic Explanations (LIME)

**Skills Demonstrated:**\
Data Preprocessing, Exploratory Data Analysis, Feature Engineering, Model Building, Model Validation

**Data Source:**\
2 CSV files containing sample performance/operation data collected from 40,000 mailing meters.
- train.csv: Sample data for meters with a flag whether they fail within the next 7 days.
- test.csv: Sample data without fail flag. Predictions for these meters is part of the final deliverable.


