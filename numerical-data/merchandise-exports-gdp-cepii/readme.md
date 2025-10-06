# Value of exported goods as  a share of GDP - Data package

This data package contains the data that powers the chart ["Value of exported goods as  a share of GDP"](https://ourworldindata.org/grapher/merchandise-exports-gdp-cepii?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on September 24, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Value of global merchandise exports as a share of GDP (Fouquin and Hugot; CEPII 2016; National data)
The value of exports, by country and regions, expressed as a share of GDP. Uses CEPII national trade data.
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Fouquin and Hugot (CEPII 2016) – processed by Our World in Data

#### Full citation
Fouquin and Hugot (CEPII 2016) – processed by Our World in Data. “Value of global merchandise exports as a share of GDP (Fouquin and Hugot; CEPII 2016; National data)” [dataset]. Fouquin and Hugot (CEPII 2016) [original data].
Source: Fouquin and Hugot (CEPII 2016) – processed by Our World In Data

### Additional information about this data
To calculate country exports (imports) to (from) the rest of the world, the total value of exports (imports) by country, per year, is divided by the country's GDP. Calculations use Fouquin and Hugot (CEPII 2016) national trade data.

The time series 'World' corresponds to the World's total exports (imports) (i.e. the sum of exports (imports) reported by all countries in the dataset).

The total export (import) values of regional income aggregates have been calculated using the World Bank's income groupings. These time series begin in 1970, where the number of countries are more representative. Similarly, total export (import) values by continental grouping begin in 1960. 

Germany's time series is comprised of West Germany, and Germany. East Germany has been excluded for the purposes of Germany's calculations.
Russia's time series comprises Russia and the USSR.


    