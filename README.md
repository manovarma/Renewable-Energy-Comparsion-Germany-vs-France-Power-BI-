## Project Overview

This project analyzes and compares renewable energy generation trends between Germany (DE) and France (FR) using open-source electricity data.
The analysis focuses on solar, onshore wind, and offshore wind generation, as well as total electricity demand (load).
All calculations and visuals were developed in Power BI, combining data cleaning, modeling, and visualization to answer key business questions about renewable performance.

## Objectives

Compare total renewable energy generation between Germany and France.

Measure each country’s renewable share (%) relative to total electricity load.

Analyze monthly and seasonal renewable production trends.

Identify dominant renewable sources (solar, onshore wind, offshore wind).

Evaluate if renewable energy meets national demand levels.

 ## Dataset

Source: Open Power System Data – Time Series (Hourly)

Period Used: 2015–2020

Countries Selected: Germany (DE) and France (FR)

Main Columns:

utc_timestamp

country

source_type

generation_mw

Calculated Measures (Load, Total Renewables, Renewable Share %)

## Data Preparation

Performed in Power Query:

Imported the dataset via Web URL.

Filtered for Germany and France.

Selected relevant renewable and load columns.

Replaced null values with 0.

Unpivoted data to create columns:
utc_timestamp, country, source_type, generation_mw.

## Created new DAX measures:

DE / FR Total Renewables (MW)

DE / FR Load (MW)

DE / FR Renewable Share (%)
