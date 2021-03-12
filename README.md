# 479-COVID-19-Project
This is project for STAT 479 in UW-Madison

Both covid-19-cases-deaths-and-hospitalization.csv and covid-19-vaccination-cases-and-hospitalization.csv are the curated data sets we want to use in Milestone 3.

Note: All the public data come from CDC website and the Atlantic's COVID Tracking Project.
Note: The public csv file only contains several row of the curated data. We basically selected them randomly.
## covid-19-cases-deaths-and-hospitalization.csv
    Columns: Date, state_abb, hospitalized, hospitalizedCumulative, hospitalizedCurrently, hospitalizedIncrease, tot_cases, new_cases, tot_deaths, new_deaths, total_cases, total_deaths
    
    tot_cases, new_cases, tot_deaths, new_deaths are refered into state level
    
    total_cases, total_deaths are refered into national level
    
## covid-19-vaccination-cases-and-hospitalization.csv
    Columns: Date, state_abb, hospitalized, hospitalizedCumulative, hospitalizedCurrently, hospitalizedIncrease, tot_cases, new_cases, tot_deaths, new_deaths, people_vaccinated, state_total_pop, vaccination_ratio, daily_vaccine
    
    We did not update the state_total_pop during the COVID-19 pandemic, so the vaccination_ratio would be a rough measurement
