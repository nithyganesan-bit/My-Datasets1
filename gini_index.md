# Income inequality: Gini coefficient - Data package

This data package contains the data that powers the chart ["Income inequality: Gini coefficient"](https://ourworldindata.org/grapher/economic-inequality-gini-index?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For most countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

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


## Gini coefficient
The [Gini coefficient](#dod:gini) measures inequality on a scale from 0 to 1. Higher values indicate higher inequality.
Last updated: June 26, 2026  
Next update: December 2026  
Date range: 1963–2025  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
World Bank Poverty and Inequality Platform (2026) – with major processing by Our World in Data

#### Full citation
World Bank Poverty and Inequality Platform (2026) – with major processing by Our World in Data. “Gini coefficient – World Bank” [dataset]. World Bank Poverty and Inequality Platform, “World Bank Poverty and Inequality Platform (PIP) 20260324_2021, 20260324_2017” [original data].
Source: World Bank Poverty and Inequality Platform (2026) – with major processing by Our World In Data

### What you should know about this data
* Incomes are distributed very unequally, both between countries and within them. The Gini coefficient is a common measure of inequality, which summarizes the distribution and expresses it in terms of a number from 0 to 1. Higher values indicate higher inequality. We explain how it works in our article [Measuring inequality: what is the Gini coefficient?](https://ourworldindata.org/what-is-the-gini-coefficient), and discuss income inequality more broadly on our page on [economic inequality](https://ourworldindata.org/economic-inequality).
* Depending on the country and year, the data refers either to income (after taxes and benefits) or to consumption, [per capita](#dod:per-capita). These are not perfectly comparable: income equals consumption plus savings, and consumption tends to be more evenly distributed than income. For most countries, we have only one option available. But when both are available, we keep one observation per country and year. You can see these different series by selecting the option to show breaks in the data.
* Many people, today and in the past, have no monetary income. This data accounts for that by adding the estimated value of non-market income, like food grown by subsistence farmers for their own use.
* The data comes from the World Bank's Poverty and Inequality Platform (PIP), which draws on national household surveys. This gives it wide global coverage, but because it pools surveys with different methodologies and mixes income and consumption data, there are limitations to the comparability of the data points between countries and over time. Regional and global estimates are extrapolated to the year of the data release using GDP growth estimates and forecasts. For more details about the methodology, please refer to the [World Bank PIP documentation](https://datanalytics.worldbank.org/PIP-Methodology/lineupestimates.html#nowcasts).

### How is this data described by its producer - World Bank Poverty and Inequality Platform (2026)?
The Gini index measures the extent to which the distribution of income (or, in some cases, consumption expenditure) among individuals or households within an economy deviates from a perfectly equal distribution. A Lorenz curve plots the cumulative percentages of total income received against the cumulative number of recipients, starting with the poorest individual or household. The Gini index measures the area between the Lorenz curve and a hypothetical line of absolute equality, expressed as a percentage of the maximum area under the line. Thus, a Gini index of 0 represents perfect equality, while an index of 100 implies perfect inequality.

### Source

#### World Bank Poverty and Inequality Platform – World Bank Poverty and Inequality Platform (PIP)
Retrieved on: 2026-06-26  
Retrieved from: https://pip.worldbank.org  

#### Notes on our processing step for this indicator
For most countries in the dataset, estimates relate to disposable income or consumption, for all available years. Several countries, however, have a mix of income and consumption data points, with both data types sometimes available for particular years.

In most of our charts, we present the data with some data points dropped to present a single series for each country. This allows us to make readable visualizations that combine multiple countries. In choosing which data points to keep, we strike a balance between maintaining comparability over time and showing as long a time series as possible. As such, the exact approach varies across countries.


## World region according to OWID
Regions defined by Our World in Data, which are used in OWID charts and maps.
Last updated: January 1, 2023  
Date range: 2023–2023  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Our World in Data – processed by Our World in Data

#### Full citation
Our World in Data – processed by Our World in Data. “World region according to OWID” [dataset]. Our World in Data, “Regions” [original data].
Source: Our World in Data

### Source

#### Our World in Data – Regions


    