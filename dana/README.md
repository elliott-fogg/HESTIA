*missing datasets:* - pc_mapping.csv - Postcode to LSOA - source [geoportal.statistics](https://geoportal.statistics.gov.uk/datasets/postcode-to-output-area-to-lower-layer-super-output-area-to-middle-layer-super-output-area-to-local-authority-district-february-2018-lookup-in-the-uk/data)

*original data:* - HM Land Registry Price Paid Data - https://www.gov.uk/guidance/about-the-price-paid-data

*other useful links:*

Weather data - [metoffice](https://www.metoffice.gov.uk/climate/uk/summaries/datasets)

IMD - [english-indices-of-deprivation-2015](https://www.gov.uk/government/statistics/english-indices-of-deprivation-2015)

UK postcode areas - [postcode-areas](https://www.summergardenbuildings.co.uk/postcode-areas.html)



**What can be found in this repository:**

- brexit, imd, income, weather - folders which contain raw data

- brexit.ipynb, IMD_index_data.ipynb, income.ipynb, weather_data.ipynb - jupyter notebooks to handle raw data

- plotting_price.ipynb - scatter plots for various variables (saved in a 'plots' folder)

- **OUTPUT data (.csv files):**
  - *brexit_postcodes.csv* - brexit vote vs postcode
  
  - *imd.csv* - IMD vs postcode
  
  - *income_postcodes.csv* - income vs postcode
  
  - *gdp_percapita_uk.csv* - GDP per capita vs years (1995-2018)

