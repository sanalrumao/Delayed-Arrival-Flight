** Project Overview**

This project aims to analyze Delayed in Arrival Flights of LAS data.The goal is to help better understand the key factors contributing to delays and improve forecasting.Using Python, we perform data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling to gain insights into this industry.

** Objectives**

Data Cleaning & Preprocessing: Handle missing values, normalize data, and ensure consistency.

Exploratory Data Analysis (EDA): Identify Delayed in Arrival Flights.

Trend Analysis: Examine Delayed and Arrival Timmings

Predictive Modeling: Use regression models to predict Delay based on various features.

Data Visualization: Generate graphs and charts for better insights.

**** Tech Stack

Programming Language: Python

Libraries Used:

pandas (Data manipulation)

numpy (Numerical analysis)

matplotlib & seaborn (Data visualization)

scikit-learn (Machine learning models)

plotly (Interactive visualizations)

** Dataset**

The dataset includes details such as:

carrier_code  
date	
flight_number	
tail_number	
origin_airport	
scheduled_arrival_time	
actual_arrival_time	
scheduled_elapsed_time_minutes	
actual_elapsed_time_minutes	
arrival_delay_minutes	
wheels-on_time	
taxi-in_time_minutes	
delay_carrier_minutes	
delay_weather_minutes	
delay_national_aviation_system_minutes	
delay_security_minutes	
delay_late_aircraft_arrival_minutes


The model achieved an accuracy of 86%, with a precision of 90% and recall of 1 (adjust with your actual metrics). Feature importance shows that departure delay and time of day are strong predictors of arrival delays
