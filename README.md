<img src="Images/car-accidents-banner.jpg">

# Project 2: US Vehicle Accidents EDA (Python)

This repository is for the analysis done on the Kaggle: US Vehicle Accidents dataset. Below you will find an overview of the data, code, and results. The goal of this project was to perform an exploratory data analysis (including the use of GeoPandas) and to prepare (i.e., clean and impute) for future predictive modeling use.

## Vehicle Accidents Dataset

The dataset was gathered from [Kaggle](https://www.kaggle.com/sobhanmoosavi/us-accidents) and, at the time of collection, spanned from February 2016 to December 2020. The dataset contained 47 variables and 2,906,610 accident records.

### Variables
`continent`, `location`, `date`, `total_cases`, `new_cases`, `new_cases_smoothed`, `total_deaths`, `new_deaths`, `new_deaths_smoothed`, `total_cases_per_million`, `new_cases_per_million`, `new_cases_smoothed_per_million`, `total_deaths_per_million`, `new_deaths_per_million`, `new_deaths_smoothed_per_million`, `reproduction_rate`, `icu_patients`, `icu_patients_per_million`, `hosp_patients`, `hosp_patients_per_million`, `weekly_icu_admissions`, `weekly_icu_admissions_per_million`, `weekly_hosp_admissions`, `weekly_hosp_admissions_per_million`, `total_tests`, `new_tests`, `total_tests_per_thousand`, `new_tests_per_thousand`, `new_tests_smoothed`, `new_tests_smoothed_per_thousand`, `positive_rate`, `tests_per_case`, `tests_units`, `total_vaccinations`, `people_vaccinated`, `people_fully_vaccinated`, `new_vaccinations`, `new_vaccinations_smoothed`, `total_vaccinations_per_hundred`, `people_vaccinated_per_hundred`, `people_fully_vaccinated_per_hundred`, `new_vaccinations_smoothed_per_million`, `stringency_index`, `population`, `population_density`, `median_age`, `aged_65_older`, `aged_70_older`, `gdp_per_capita`, `extreme_poverty`, `cardiovasc_death_rate`, `diabetes_prevalence`, `female_smokers`, `male_smokers`, `handwashing_facilities`, `hospital_beds_per_thousand`, `life_expectancy`, `human_development_index`, `excess_mortality`

## COVID19_Queries.sql

This file contains the 27 queries I performed in Microsoft SQL Server on the database which I created from the dataset. Seven views were created to aid in creating the data tables used in Tableau.

## Results and Application

### COVID-19 World Summary Dashboard

Figure 1 shows the dashboard for the COVID-19 World Summary created in Tableau. For the interactive version, [click here](https://public.tableau.com/app/profile/michael.bryant5195/viz/COVID-19WorldSummaryJuly312021/Dashboard1).

<figure>
<img src="Images/COVID19-World-Summary.png">
  <figcaption>Figure 1: COVID-19 World Summary dashboard created in Tableau.</figcaption>
</figure>

### COVID-19 US Summary Dashboard

Figure 2 shows the dashboard for the COVID-19 US Summary created in Tableau. For the interactive version, [click here](https://public.tableau.com/app/profile/michael.bryant5195/viz/COVID-19USSummaryJuly312021/Dashboard1).

<figure>
<img src="Images/COVID-19-US-Summary.png">
  <figcaption>Figure 2: COVID-19 US summary dashboard created in Tableau.</figcaption>
</figure>

### Application

This project can help keep people informed about the current status of COVID-19. A website or app can be created as an interface. The query process and Tableau dashboard creation can be automated so that a user may select the region they are interested in and the variables they want to view.

Specifically, the visualizations can help businesses, schools, and politicians make informed policy decisions for implementing closures or lockdowns to mitigate the spread of COVID-19. The hospitalization and ICU patient forecast visualizations can be used by medical institutions to ensure equipment and staffing needs are met.

## Resources

1. [Our World in Data. Statistics and Research: Coronavirus Pandemic (COVID-19)](https://ourworldindata.org/coronavirus)
2. [YouTube. Alex The Analyst: Data Analyst Portfolio Project | SQL Data Exploration | Project 1/4](https://www.youtube.com/watch?v=qfyynHBFOsM)
3. [YouTube. Alex The Analyst: Data Analyst Portfolio Project | Tableau Visualization | Project 2/4](https://www.youtube.com/watch?v=QILNlRvJlfQ)
4. [City of Melbourne: Harbor City. COVID-19 Updates](https://www.melbourneflorida.org/about/covid-19)
5. [GitHub | owid/covid-19-data: Dataset by Our World in Data](https://github.com/owid/covid-19-data)






## Resources

1. [Kaggle: US Accidents (3 million records -- updated)](https://www.kaggle.com/sobhanmoosavi/us-accidents)
2. [DiTomaso Law: Cherry Hill Car Accident Lawyers](https://www.ditomasolaw.com/practice-areas/car-accidents/multi-vehicle-auto-accidents/)
