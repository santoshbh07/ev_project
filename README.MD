# Electric Vehicle Adoption Analysis

## Overview
This project analyzes electric vehicle (EV) adoption trends using Washington State vehicle registration data. The analysis focuses on adoption growth, geographic concentration, and electric range characteristics while explicitly handling real-world data quality issues.

## Data
- Source: Washington State Electric Vehicle Population Data
- URL: https://catalog.data.gov/dataset/electric-vehicle-population-data
- Size: ~270,000 vehicle records
- Key fields: model year, county, vehicle type, electric range, legislative district

## Workflow
1. Data audit and quality checks  
2. Data cleaning and type enforcement  
3. Exploratory data analysis (EDA)  
4. Feature engineering  
5. Analysis and insights

## Key Insights
- EV adoption has increased rapidly since 2020  
- Battery Electric Vehicles (BEVs) dominate registrations  
- EV ownership is concentrated in a small number of counties  
- Missing electric range data can distort averages if not handled explicitly

## Outputs
- Time-series of EV adoption
- Average BEV electric range (valid records only)
- Top counties by EV registrations

Plots are saved in the `figures/` directory.

## Tools
- Python
- Pandas
- Matplotlib
- NumPy

## Notes
Electric range is not reported for all vehicles. Analyses involving range are restricted to records with valid values to avoid misleading conclusions.
