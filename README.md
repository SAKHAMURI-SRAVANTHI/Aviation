# ✈️ Flight Delay Analysis
## 📊Project Overview

The Flight Delay Analysis Dashboard is designed to evaluate airline performance and flight operations using detailed data from flights, airports, and airlines.

This project provides valuable insights and recommendations for improving on-time performance, route optimization, flight scheduling, and overall operational efficiency.

The analysis supports decision-making in critical areas such as arrival and departure management, delay prediction, and network reliability.


### 🧾Data Source:

Flights Dataset: Contains over 1,045,000 records with 37 columns (2015 data).

Airlines Dataset: Includes airline codes and names.

Airports Dataset: Contains information on airport locations and codes.


### 🧰Tools Used:

Excel: Data Cleaning and initial exploration

SQL: Data Analysis and KPI generation

Power BI: Dashboard creation and visualization

Tableau: Advanced visualization and trend analysis


### 🧹Data Cleaning:

In the data preparation phase, the following tasks were performed:

Loading and inspecting over 1 million flight records

Converting time fields (HHMM → 24-hour format)

Handling missing values and inconsistent records

Resolving type conversion issues for numeric and time-based data

Structuring the schema into a Star Schema with:

Fact Table: Flights

Dimension Tables: Airlines, Airports



### Data Analysis

SQL was used to analyze flight data and derive KPIs, including:

Total flights, cancellations, and diversions

Airline-wise delay performance

Weekday vs Weekend flight trends

Delay causes and their correlation between departure and arrival

Taxi-in/out performance for ground efficiency



## 🗂️ Key Features of the Dashboard

### Excel Dashboard


Quick overview of flight delays, cancellations, and punctuality trends

<img width="1707" height="885" alt="image" src="https://github.com/user-attachments/assets/2fad548f-0ff1-4c5b-a36e-ac1c765fa8be" />



### Power BI Dashboard

Dynamic visuals for delay trends, top airlines, busiest routes, and delay causes

<img width="1361" height="769" alt="image" src="https://github.com/user-attachments/assets/a2d1614d-17d7-44b1-b7b4-887df8a26c8e" />


### Tableau Dashboard

Interactive maps and charts to analyze airport performance, flight routes, and delay distribution

<img width="1867" height="954" alt="image" src="https://github.com/user-attachments/assets/c4d64da0-ca95-4bf4-95eb-7bcd5ec1b61c" />


### SQL Queries

Used to extract, filter, and analyze flight data for key performance metrics such as total flights, cancellations, delays, and airline-wise punctuality.

<img width="1294" height="736" alt="image" src="https://github.com/user-attachments/assets/892128e7-376c-4230-b92b-cb1d6c325dbc" />

<img width="1395" height="747" alt="image" src="https://github.com/user-attachments/assets/a26ae9be-cd82-4e3b-b311-d02aba304d56" />





## 📈Results / Findings:

Analyzed over 1.04 million flights — around 40,000 were cancelled and 2,500 were diverted.

56% of flights were either early or on-time, showing strong overall performance.

Weekdays handled more flights (~769K) and saw more delays than weekends (~277K).

Major delays were caused by late aircraft and airline-related issues, not weather.

Early arrivals (≈559K) outnumbered late arrivals (≈421K).

Research & Development airports (e.g., LAX, JFK) showed highest traffic and delay patterns.



## 💡 Recommendations:

Implement predictive analytics to forecast delays and optimize schedules.

Distribute flight loads more evenly during weekday peaks.

Focus on reducing “Late Aircraft” delays by improving turnaround coordination.

Enhance maintenance and monitoring systems for routes prone to delays.

Collaborate with Air Traffic Control (ATC) to reduce peak-hour congestion.

Set performance benchmarks for airlines with lower punctuality (e.g., F9, MQ, NK).



