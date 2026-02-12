COVID‑19 Data Exploration Using SQL and Tableau
This project explores global COVID‑19 trends using SQL Server to analyze cases, deaths, infection rates, and vaccination progress. The analysis uses joins, window functions, temp tables, and views to answer key questions about the pandemic.

Tableau Dashboard
https://public.tableau.com/views/COVIDDashboard_16839140010380/Dashboard1

Dataset
Two main tables:
- CovidDeaths (cases, deaths, population, continent, date)
- CovidVaccinations (vaccination counts by date and location)

Project Overview
- Analyzed infection and death rates by country.
- Calculated death percentages and infection percentages.
- Identified countries with the highest infection and death counts.
- Summarized global cases and deaths over time.
- Calculated rolling vaccination totals using window functions.
- Created temp tables and views for reusable analysis.

Techniques Used
- SQL joins
- Window functions (rolling totals)
- Aggregate functions
- Temp tables
- Views
- Data type conversions

Key Insights
- Some countries experienced infection rates exceeding 20 percent of their population.
- Countries with the highest death counts were typically large populations with early outbreaks.
- Global death rates fluctuated depending on variant waves.
- Vaccination rollout varied significantly by country.

Tech Stack
- SQL Server
- Tableau
- GitHub

Files Included
- SQL exploration script
- Tableau workbook
- Excel data
- README documentation
