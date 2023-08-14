# IndigenousResilience: Native Americans and the United States Criminal Justice System
## A Solo Capstone Project: Data Journalism
### Introduction
In this project, I am analyzing datasets from the U.S. Census Bureau and the Bureau of Justice Statistics to identify what disparities, if any, exist in the following areas:
Incarceration rates for different races
Poverty and incarceration rate correlation for different races

I would like to begin to answer the question: Are there concerning differences in incarceration rates for Native Americans that warrant further investigation and mitigation strategies?
### Data
Incarceration Data: I retrieved incarceration data from the Inter-university Consortium for Political and Social Research (ICPSR), a unit within the University of Michigan's Institute for Social Research. The dataset I used is provided by the United States Bureau of Justice Statistics as part of their National Prison Statistics series. Relevant variables include those with the count of prisoners for each race and the total count of prisoners. The Terms of Use provided by ICPSR when downloading data indicates that I do not have permission to redistribute the dataset itself, but the data files are available at the following URL: https://www.icpsr.umich.edu/web/NACJD/studies/38555
Poverty Data: I retrieved data on poverty rates from the U.S. Census Bureau. The dataset I used is for the year 2021 and includes race and poverty data by state and nation for the U.S. Relevant variables include those identifying total population, population by race, and population by race below poverty. Data is available at the following URL: https://data.census.gov/table?q=Income+and+Poverty&t=Poverty&y=2021&tid=ACSST1Y2021.S1701
### How to Run
Notebook 1.ipnyb runs all the code to clean and wrangle the data. The API key for my Plotly dashboard has been removed, so the lines that deliver the visualizations to my Plotly dashboard have been commented out. In addition, the data from ICPSR indicates that redistribution of the data itself is not allowed. It is available at the URL above, so one could copy this notebook, download that data for themselves, and then run the code. Census data is included in this repository.

