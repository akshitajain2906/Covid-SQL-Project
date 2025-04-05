# COVID SQL Project – Data Exploration & Analysis

This project explores global COVID-19 data using SQL, focusing on infection, death, and vaccination trends across countries and continents.

---

## Overview

The dataset includes daily COVID-19 statistics for each country, including cases, deaths, and vaccinations. The aim was to extract meaningful insights using SQL and understand how the virus spread and impacted populations globally.

Key focus areas included:
- Tracking infection and death rates across countries  
- Comparing case counts to total population  
- Exploring vaccination rollout trends  
- Identifying countries with the highest impact  
- Aggregating global statistics to monitor pandemic progression  

Two datasets—`CovidDeaths` and `CovidVaccinations`—were used in combination.

---

## What I Looked At

### 1. Infection and Death Trends
- Tracked total cases and deaths over time  
- Calculated death percentage by country to show mortality rate  
- Compared total cases to population to measure infection penetration  

### 2. Country and Continent Comparisons
- Ranked countries by infection rate relative to population  
- Found countries with the highest total death count  
- Aggregated death counts at the continent level  

### 3. Global Aggregations
- Summed new cases and deaths by date to track the virus globally  
- Calculated global death percentage for each day  
- Analyzed total global deaths overall  

### 4. Vaccination Rollout
- Used CTE and window functions to calculate cumulative vaccinations  
- Joined death and vaccination datasets on location and date  
- Tracked rolling vaccination count as a percentage of population  

### 5. Data Storage for Reuse
- Created temporary tables and views to store transformed data  
- Views were built to support future visualizations and analysis  

---

## Sample Insights

- Some countries reported infection rates exceeding 20% of their population.  
- Nations like the U.S. and Brazil had the highest total deaths.  
- Global death rates were under 3% for most of the pandemic period.  
- Rolling vaccination analysis showed a clear trend of vaccine distribution across 2021–2022.

