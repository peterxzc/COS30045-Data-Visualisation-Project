# DataViz_FinalProject
d3 visualization project using datasets: UN Migration Estimates, UCDP/PRIO Armed Conflict, Worldbank GDP

## processing_notebooks

Directory for iPython/jupyter notebooks reading data from raw_data, cleaning/organizing it, and writing to processed_data. 

## processed_data

**Total_stock_as_fraction.csv**: Total migrant stock for each country as a fraction of its population in a given year. `code` is alpha-3 ISO country code. Columns for years `1990, 1995, 2000, 2005, 2010, 2015`. `NaN` values were filled with `0.0`.


**GDP\_per\_capita.csv**: `code` is alpha-3 ISO country code. Columns for years `1990, 1995, 2000, 2005, 2010, 2015`. `NaN` values were filled with `0.0`.

## raw_data

**ISO\_codes.csv**: A complete set of numeric and alphanumeric country codes for combining data from files that use different codes. (We want alpha-3 for datamaps.)

**CountriesList.txt**: A list of country names and alpha-3 codes for all the countries that can used with datamaps.

**Migrate\_XXXX.xlsx**: Excel files of UN data by year, just cleaned up enough to read them into `pandas`.

**GDP.csv**: Yearly GDP data (Worldbank).

**Population.csv**: Yearly population data (Worldbank).

## js

Javascript files. See [datamaps.github.io](http://datamaps.github.io/) for datamaps documentation. 

