# Aviation
Project Overview
The Flight Delay Analysis Dashboard is designed to evaluate airline performance and flight operations using detailed data from flights, airports, and airlines.
This project provides valuable insights and recommendations for improving on-time performance, route optimization, flight scheduling, and overall operational efficiency.
The analysis supports decision-making in critical areas such as arrival and departure management, delay prediction, and network reliability.


Data Source:
Flights Dataset: Contains over 1,045,000 records with 37 columns (2015 data).
Airlines Dataset: Includes airline codes and names.
Airports Dataset: Contains information on airport locations and codes.


Tools Used:
Excel: Data Cleaning and initial exploration
SQL: Data Analysis and KPI generation
Power BI: Dashboard creation and visualization
Tableau: Advanced visualization and trend analysis


Data Cleaning:
In the data preparation phase, the following tasks were performed:
Loading and inspecting over 1 million flight records
Converting time fields (HHMM → 24-hour format)
Handling missing values and inconsistent records
Resolving type conversion issues for numeric and time-based data
Structuring the schema into a Star Schema with:
Fact Table: Flights
Dimension Tables: Airlines, Airports



Data Analysis

SQL was used to analyze flight data and derive KPIs, including:

Total flights, cancellations, and diversions

Airline-wise delay performance

Weekday vs Weekend flight trends

Delay causes and their correlation between departure and arrival

Taxi-in/out performance for ground efficiency



Excel Dashboard

Quick overview of flight delays, cancellations, and punctuality trends
<img width="1707" height="885" alt="image" src="https://github.com/user-attachments/assets/2fad548f-0ff1-4c5b-a36e-ac1c765fa8be" />


