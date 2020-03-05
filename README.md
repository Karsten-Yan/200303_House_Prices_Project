# House price prediction for King County, Washington

In this project I analysed the data sample on house price sales in King County, Washington.

In [King_County_House_prices.csv](https://github.com/Karsten-Yan/200303_House_Prices_Project/blob/master/King_County_House_prices_dataset.csv) you can find the Raw Data, which serves as the basis for the analysis. 

[column_names.md](https://github.com/Karsten-Yan/200303_House_Prices_Project/blob/master/column_names.md) contains explanations and details for the columns.

The notebook [200303_Karsten_Yan_Project1.ipnyb](https://github.com/Karsten-Yan/200303_House_Prices_Project/blob/master/200303_Karsten_Yan_Project1.ipynb) contains the main analysis of the data. I mainly focused on newly renovated or newly built (<= 5 Years) Houses and modeled my predictions and visualisations for that subset.

You can find the non technical presentation under [king_county_presentation.pdf](https://github.com/Karsten-Yan/200303_House_Prices_Project/blob/master/king_county_presentation.pdf) or directly on [Google Presentations](https://docs.google.com/presentation/d/1K6o0T1po-ulo1qJ-qshlzQHv9AFTnLXRhBhZZVrgOoA/edit#slide=id.g70f25a3caa_0_353)

The notebook is split into 9 subcategories.

1.  Business understanding:
  * Formulation of target
2.  Data mining:
  * Import of necessary modules and accessing raw data into pandas data frame
3.  Data Cleaning:
  * removal of unnecessar columns (view and id) and conversion of sqft_basement to numerical values
4. Feature engeneering:
  * years since last renovation or construction
  * bathroom/bedroom ratio
  * zip code price ranks
  * quality
  * dummy variables
  * cleanup
  * definition of parameters
5.  Data exploration:
  * correlation heatmap
  * pairplots
6.  Statistic modeling:
  * brute force approach, iterating through each variable, choosing highest r sqaure adj, begin loop from beginning including formerly chosen variable
  * modeling for all homes according to search parameters
  * modeling for newly constructed homes (less than 5 years)
7. Visualisation:
  * visualisations for newly constructed homes
  * comparing quality and quantity and some basic features
A. Summary
B. Future Work
