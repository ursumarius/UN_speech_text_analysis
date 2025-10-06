# Literacy rate of young men vs. women - Data package

This data package contains the data that powers the chart ["Literacy rate of young men vs. women"](https://ourworldindata.org/grapher/literacy-rate-of-young-men-and-women?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Literacy rate among young men aged 15–24
Share of men aged 15 to 24 years who can read and write.
Last updated: May 1, 2025  
Next update: May 2026  
Date range: 1970–2023  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
UNESCO Institute for Statistics (2025) – with minor processing by Our World in Data

#### Full citation
UNESCO Institute for Statistics (2025) – with minor processing by Our World in Data. “Literacy rate among young men aged 15–24” [dataset]. UNESCO Institute for Statistics, “UNESCO Institute for Statistics (UIS) - Education” [original data].
Source: UNESCO Institute for Statistics (2025) – with minor processing by Our World In Data

### What you should know about this data
* Literacy is a foundational skill. Children need to learn to read so that they can read to learn. When we fail to teach this foundational skill, people have fewer opportunities to lead the rich and interesting lives that a good education offers.
* This indicator measures the percentage of people who can read and write a simple sentence about their daily life. It’s calculated as the number of people in a given age group who report being able to do so, divided by the total number in that group. UNESCO tracks this across different generations – including youth, adults, and older people – to show how literacy is changing over time.
* Most of the data comes from national surveys. In some countries, people are asked directly whether they can read and write; in others, they take a short test.
* In many high–income countries, literacy rates reached near–universal levels by the late 20th century. As a result, regular tracking has been scaled back, since changes are small and less relevant for education policy.
* This data tells us whether someone can read and write at a very basic level – for example, reading simple sentences or writing their name. But it doesn’t tell us whether they can use reading and writing in everyday life, like filling out a job application or reading health instructions. Those kinds of skills take more years of schooling and are much harder to measure, especially when comparing across countries and over time.

### How is this data described by its producer - UNESCO Institute for Statistics (2025)?
Number of males age 15 to 24 years who can both read and write with understanding a short simple statement on their everyday life, divided by the male population in that age group. Generally, ‘literacy’ also encompasses ‘numeracy’, the ability to make simple arithmetic calculations. Divide the number of people aged 15 to 24 years who are literate by the total population in the same age group and multiply the result by 100.

### Source

#### UNESCO Institute for Statistics – UNESCO Institute for Statistics (UIS) - Education
Retrieved on: 2025-05-01  
Retrieved from: https://databrowser.uis.unesco.org/resources/bulk  


## Literacy rate among young women aged 15–24
Share of women aged 15 to 24 years who can read and write.
Last updated: May 1, 2025  
Next update: May 2026  
Date range: 1970–2023  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
UNESCO Institute for Statistics (2025) – with minor processing by Our World in Data

#### Full citation
UNESCO Institute for Statistics (2025) – with minor processing by Our World in Data. “Literacy rate among young women aged 15–24” [dataset]. UNESCO Institute for Statistics, “UNESCO Institute for Statistics (UIS) - Education” [original data].
Source: UNESCO Institute for Statistics (2025) – with minor processing by Our World In Data

### What you should know about this data
* Literacy is a foundational skill. Children need to learn to read so that they can read to learn. When we fail to teach this foundational skill, people have fewer opportunities to lead the rich and interesting lives that a good education offers.
* This indicator measures the percentage of people who can read and write a simple sentence about their daily life. It’s calculated as the number of people in a given age group who report being able to do so, divided by the total number in that group. UNESCO tracks this across different generations – including youth, adults, and older people – to show how literacy is changing over time.
* Most of the data comes from national surveys. In some countries, people are asked directly whether they can read and write; in others, they take a short test.
* In many high–income countries, literacy rates reached near–universal levels by the late 20th century. As a result, regular tracking has been scaled back, since changes are small and less relevant for education policy.
* This data tells us whether someone can read and write at a very basic level – for example, reading simple sentences or writing their name. But it doesn’t tell us whether they can use reading and writing in everyday life, like filling out a job application or reading health instructions. Those kinds of skills take more years of schooling and are much harder to measure, especially when comparing across countries and over time.

### How is this data described by its producer - UNESCO Institute for Statistics (2025)?
Number of females age 15 to 24 years who can both read and write with understanding a short simple statement on their everyday life, divided by the female population in that age group. Generally, ‘literacy’ also encompasses ‘numeracy’, the ability to make simple arithmetic calculations. Divide the number of people aged 15 to 24 years who are literate by the total population in the same age group and multiply the result by 100.

### Source

#### UNESCO Institute for Statistics – UNESCO Institute for Statistics (UIS) - Education
Retrieved on: 2025-05-01  
Retrieved from: https://databrowser.uis.unesco.org/resources/bulk  


## World regions according to OWID
Regions defined by Our World in Data, which are used in OWID charts and maps.
Last updated: January 1, 2023  
Date range: 2023–2023  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Our World in Data – processed by Our World in Data

#### Full citation
Our World in Data – processed by Our World in Data. “World regions according to OWID” [dataset]. Our World in Data, “Regions” [original data].
Source: Our World in Data

### Source

#### Our World in Data – Regions


    