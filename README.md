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

**Data Dictionary:**\
- fail_7 – Binary variable indicating whether the device failed in the next 7 days from the last record 	
- Deviceid – Unique ID for each meter
- avg_time_charging_lag – Average amount of time the device was charging ‘i’ days prior
- avg_time_discharging_lag - Average amount of time the device was discharging ‘i’ days prior 
- charging_rate_lag4 -  Rate of Charging of the meter ‘i’ days prior
- discharging_rate_lag – Rate of discharge of the meter ‘i’ days prior
- charge_cycle_time_below_12 – Charging+Discharging time <12	
- chargecycles/dischargecycles -	No. of times meter is charged and discharged
- total_off_time	- Average amount of time device spends switched off
- number_times_restart	- Average number of times device is restarted 
- avg_volt_change_charging – Average change in voltage during charging	
- avg_volt_change_discharging – Average change in voltage during discharging	
- avg_time_charging - Average amount of time the device spent charging
- avg_time_discharging - Average amount of time the device spent discharging	
- max_voltage_day – Average value of the highest voltage attained everyday 	
- piececount – Average number of pieces processed in a day	
- cycle_time – Charging + Discharging time	
- LastRecord – Date of last recorded event 
- Date Deployed – Date on which device was put into us

