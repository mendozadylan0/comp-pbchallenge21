# project-pbchallenge_spr21

**Context:**\
Pitney Bowes uses predictive maintenance to reduce down-times of mailing meters. Since Pitney Bowes' mailing meters are an integral part of their clients' business operations, they must be able to proactively identify potential complications early on to avoid service disruptions for their clients. Predictive maintenance allows Pitney Bowes to have the required replacement parts where they are needed. Additionally, predictive maintenance also allows Pitney Bowes to proactively schedule appointments with customers if needed.

**Objective:**\
Using the training sample provided by the Pitney Bowes team, build a model that can reliably predict which meters will fail within the next 7 days (7 days from data collection). We were given free reign when it came to defining the metrics and KPI's for measuring the reliability of said model.

**Tools Used:**\
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Imblearn, Local Interpretable Model-Agnostic Explanations (LIME)

**Skills Demonstrated:**\
Data Preprocessing, Exploratory Data Analysis, Feature Engineering, Model Building, Model Validation

**Data Source:**\
2 CSV files containing sample performance/operation data collected from 40,000 mailing meters.
- train.csv: Sample data for meters with a flag whether they fail within the next 7 days.
- test.csv: Sample data without fail flag. Predictions for these meters is part of the final deliverable

Data dictionary found below:\
![image](https://user-images.githubusercontent.com/82073881/150061179-7407e95f-84bd-47b3-bc67-3f721256d77f.png)
