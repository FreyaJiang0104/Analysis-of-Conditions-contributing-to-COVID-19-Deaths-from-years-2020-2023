# BA-780-Project: Analysis of Conditions contributing to COVID-19 Deaths from years 2020-2023

This dataset shows us the total number of people that have died from various reasons from 2020 to 2023 in the United States and its regions. This was the time when COVID-19 started and we are using this dataset to evaluate and analyze the impact of COVID-19 alongside other health conditions in the United States.

## Motivation and Report Summary:
We aim to assess the regions and demographic age groups most susceptible to COVID-19-related mortality, allowing us to strategically allocate our vaccination resources to target these high-risk areas. This is done due to the countless people who suffered from this disease and we aim to help organizations better understand this data to make better public health decisions.

### Data Source:
Center for Disease Control and Prevention.
Link to access the data source is provided below.
https://data.cdc.gov/NCHS/Provisional-COVID-19-Deaths-by-Sex-and-Age/9bhg-hcku

State Population Totals and Components of Change (2020-2022):
https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html

Each row represents a time period (months/years) when deaths occured and tells us whether those deaths were from COVID-19, Influenza, Pneumonia, or any other reason.

* Date As of: Date data was collected
* Start Date: Date data collection for the row started
* End Date: Date Data collection for the row ended
* Group: Data grouped by (Year, Month, Total)
* Year: Year (2020, 2021, 2022, 2023)
* Month
* State
* Age Group
* COVID-19 Deaths
* Total Deaths
* Pneumonia Deaths
* Pneumonia and Covid-19 Deaths
* Influenza Deaths
* Pneumonia, Influenza and COVID-19 Deaths
* Footnotes

#### In this project, we are:
* Analyzing the total number of deaths per state in US categorized by year.
* Evaluating and determining the trend of COVID-19, Influenza and Pneumonia deaths against the total number of deaths.
* Determining how COVID-19 deaths are distributed amoung different age groups and which age group is more susceptible to COVID-19 more than others thereby highlighting those in need of special care and attention.
* Comparing the COVID-19 deaths with deaths due to other conditions alongside COVID-19 for each given year.
* Comparing the COVID-19 Deaths by Sex for each year.

#### Basic Information
Dataset has
* 16 Columns
* 133700 Rows
We will be using Pandas, NumPy, Matplotlib and Seaborn to make our plots and visualizations to showcase the data.
