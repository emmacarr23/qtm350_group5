# Codebook for QTM350 project, group 5

## Dataset 1: cleaned_data
### Description
This dataset is the cleaned version of the raw data provided by databank.worldbank.org.

### Variables
| **Variables** | **Description** | **Type** | **Values** | **Missing Values** |
|---------------|-----------------|----------|------------|--------------------|
| country_name | The names of the countries specified by the World Bank country classifications | String | Country names, e.g (`Afghanistan`, `Albania`, `Algeria`, etc.)| N/A |
| country_code | The acryonyms of countries based on the ISO 3166-1 alpha-3 standard | String | Acronyms of countries, e.g. (`AFG`, `ALB`, `DZA`) | N/A |
| series_name | The type of variable in a row | String | `Adjusted net national income per capita (annual % growth)`,<br> `Employment to population ratio, 15+, total (%) (national estimate)`, <br>`GDP growth (annual %)`,<br> `GDP per capita (constant 2015 US$)`,<br> `Research and development expenditure (% of GDP)`, <br>and `Tax revenue (% of GDP)`| N/A |
| yrxxxx | Multiple columns, data for year xxxx where xxxx is in (2004,2005,...,2023) | Numeric | Continuous | None |
| regions | The regions countries belong to by the World Bank classifications | String | `South Asia`,<br>`Europe & Central Asia`,<br> `Middle East & North Africa`, `East Asia & Pacific`, <br>`Sub-Saharan Africa`, <br>`Latin American & Caribbean`,<br> `North America`,  | N/A |

## Dataset 2: top_10_data
### Description
This datasets provide the data from only the top 10 countries with the highest gdp's in 2022.

### Variables
| **Variables** | **Description** | **Type** | **Values** | **Missing Values** |
|---------------|-----------------|----------|------------|-----------|
| country_name | The names of the countries specified by the World Bank country classifications | String | `Cayman Islands`, `Bermuda`, `Ireland`, `Luxembourg`, `Monaco`, `Norway`, `Qatar`,`Singapore`, `Switzerland`, `United States` | N/A |
| country_code | The acryonyms of countries based on the ISO 3166-1 alpha-3 standard | String | Acronyms of countries, e.g. (`AFG`, `ALB`, `DZA`) | N/A |
| series_name | The type of variable in a row | String | `Adjusted net national income per capita (annual % growth)`,<br> `Employment to population ratio, 15+, total (%) (national estimate)`,<br> `GDP growth (annual %)`, <br>`GDP per capita (constant 2015 US$)`,<br> `Research and development expenditure (% of GDP)`, and <br>`Tax revenue (% of GDP)`| N/A |
| yrxxxx | Multiple columns, data for year xxxx where xxxx is in (2004,2005,...,2023) | Numeric | Continuous | None |
| regions | The regions countries belong to by the WOrld Bank classifications | String | `South Asia`,<br>`Europe & Central Asia`, <br>`Middle East & North Africa`, `East Asia & Pacific`,<br> `Sub-Saharan Africa`,<br> `Latin American & Caribbean`,<br> `North America`,  |

## Dataset 3: total_average
### Description
This dataset provides the average of each series_name type in each year from 2004-2023

### Variables
| **Variables** | **Description** | **Type** | **Values** | **Missing Values** |
|---------------|-----------------|----------|------------|-----------|
| series_name | The type of variable in a row | String | `Adjusted net national income per capita (annual % growth)`,<br> `Employment to population ratio, 15+, total (%) (national estimate)`, <br>`GDP growth (annual %)`,<br> `GDP per capita (constant 2015 US$)`,<br> `Research and development expenditure (% of GDP)`, and <br>`Tax revenue (% of GDP)`| N/A |
| avgxxxx | Multiple columns, data for the average of year xxxx where xxxx is in (2004,2005,...,2023) | Numeric | Continuous | None |


## Dataset 4: regional_avg
### Description
This dataset provides the average of each series_name type for each region in each year from 2004-2023

### Variables
| **Variables** | **Description** | **Type** | **Values** | **Missing Values** |
|---------------|-----------------|----------|------------|-----------|
| regions | The regions countries belong to by the WOrld Bank classifications | String | `South Asia`,<br>`Europe & Central Asia`, <br>`Middle East & North Africa`, `East Asia & Pacific`,<br> `Sub-Saharan Africa`,<br> `Latin American & Caribbean`, <br>`North America`,  | N/A |
| series_name | The type of variable in a row | String | `Adjusted net national income per capita (annual % growth)`,<br> `Employment to population ratio, 15+, total (%) (national estimate)`, <br>`GDP growth (annual %)`, <br>`GDP per capita (constant 2015 US$)`,<br> `Research and development expenditure (% of GDP)`, and <br>`Tax revenue (% of GDP)`| N/A |
| avg_xxxx | Multiple columns, data for the average for regions of year xxxx where xxxx is in (2004,2005,...,2023) | Numeric | Continuous | None |

## Dataset 5: regional_max
### Description
This dataset provides the max of each series_name type for each regions in each year from 2004-2023

### Variables
| **Variables** | **Description** | **Type** | **Values** | **Missing Values** |
|---------------|-----------------|----------|------------|-----------|
| regions | The regions countries belong to by the WOrld Bank classifications | String | `South Asia`,`Europe & Central Asia`,<br> `Middle East & North Africa`, <br>`East Asia & Pacific`, <br>`Sub-Saharan Africa`,<br> `Latin American & Caribbean`, and <br> `North America`,  | N/A |
| series_name | The type of variable in a row | String | `Adjusted net national income per capita (annual % growth)`,<br> `Employment to population ratio, 15+, total (%) (national estimate)`, <br>`GDP growth (annual %)`,<br> `GDP per capita (constant 2015 US$)`, <br>`Research and development expenditure (% of GDP)`, <br>and `Tax revenue (% of GDP)`| N/A |
| max_xxxx | Multiple columns, data for the max for regions of year xxxx where xxxx is in (2004,2005,...,2023) | Numeric | Continuous | None |


## Dataset 6: regional_min
### Description
This dataset provides the min of each series_name type for each regions in each year from 2004-2023

### Variables
| **Variables** | **Description** | **Type** | **Values** | **Missing Values** |
|---------------|-----------------|----------|------------|-----------|
| regions | The regions countries belong to by the WOrld Bank classifications | String | `South Asia`,`Europe & Central Asia`,<br> `Middle East & North Africa`, <br>`East Asia & Pacific`,<br> `Sub-Saharan Africa`, <br>`Latin American & Caribbean`,<br> `North America`,  | N/A |
| series_name | The type of variable in a row | String | `Adjusted net national income per capita (annual % growth)`,<br> `Employment to population ratio, 15+, total (%) (national estimate)`,<br> `GDP growth (annual %)`,<br> `GDP per capita (constant 2015 US$)`,<br> `Research and development expenditure (% of GDP)`,<br> and  `Tax revenue (% of GDP)`| N/A |
| min_xxxx | Multiple columns, data for the min for regions of year xxxx where xxxx is in (2004,2005,...,2023) | Numeric | Continuous | None |

