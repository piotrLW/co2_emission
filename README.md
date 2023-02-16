# CO2 emission by country

The project aims to study the relationship between the CO2 emissions of the world's countries and the economic factors and sources of the energy they produce.<br>
Two datasets were used for this - the first, containing information on power plants from around the world, and the second, consisting of general demographic and economic data. <br>
In the data_cleaning.ipynb file, the two datasets are cleaned and then combined into a single dataset, which is then written to the data_joined.csv file. The data from this file is then analyzed in the parsing.csv notebook. The analysis culminates with the division of countries into groups that differ in terms of CO2 emissions and GPD, among other things. The k-means algorithm was used to make the division.
