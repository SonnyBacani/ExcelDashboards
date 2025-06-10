# Traffic Accidents Dashboard

## Overview: 
This dashboard presents an analysis of road traffic accidents using Excel and provide insights into accidents, injuries and fatalities based on time and different conditions.

## Process:
### 1. Data Cleaning:
Used Excel PowerQuery to clean up data. Loaded data into the Data Model and establish relationship between source tables
   - Removed unnecessary columns
   - Add column using Date option (Year, Month Name and Hour)
   - Change column datatype
   - Standardized values for multiple columns
   - Used DAX to add new columns (ex. calculate part of the day based on hour)
### 2. Pivot Tables
   - Aggregated number of accidents, injuries and fatalities by:
       - Year, Month and Day
       - Part of the day (Afternoon, Evening, Morning and Night)
       - Conditions (weather, lighting, road and traffic control)
### 3. Dashboard
   - KPIs: Total Accidents, Injuries and Fatalities
   - Column Chart: Accidents by Year, Day of the Week, Injuries by Traffic Control
   - Bar Chart: Accidents by Part of the Day, Injuries by Weather Condition
   - Pie Chart: Fatalities by Part of the Day, Injuries by Road Condition
   - Line Chart: Injuries by Part of the Day, Injuries Monthly Trend
   - Donut Chart: Different Injury Types, Injuries by Lighting Condition
   - Slicer: By Intersection Related, Year

#### Dataset Source: Kaggle
