# DDS_Budweiser_Project

Purpose: Perform a data analysis for CEO and CFO of Budewiser on the Beers and Breweries Datasets and presetation of interesting findings from the data. 

Description of Data Sets: The Beers data set contains a list of 2410 US craft beers and Breweries dataset contains 558 US breweries. The data sets descriptions are as follows.  The Beers_And_Breweries dataset was a combination of the Beers dataset and the Breweries dataset, containing all 2410 unique beers.  

We removed some non-beer results and determined missing Style, ABV, and IBU values.  The results of the data cleaning were put into the Beers_And_Breweries_Cleaned dataset, which had a total of 2356 unique beers.

Beers.csv:

		Name: Name of the beer.
		Beer_ID: Unique identifier of the beer.
		ABV: Alcohol by volume of the beer.
    		62 NA observations
		IBU: International Bitterness Units of the beer.
    		1005 NA observations 
		Brewery_ID: Brewery id associated with the beer.
		Style: Style of the beer. 
    		5 Blank observations
		Ounces: Ounces of beer.

Breweries.csv: 

		Brew_ID: Unique identifier of the brewery.
		Name: Name of the brewery.
		City: City where the brewery is located.
		State: U.S. State where the brewery is located.

  Beers_And_Breweries.csv:

  		Brewery_ID: Brewery id associated with the beer.
		Beer_Name: Name of the beer.
		Beer_ID: Unique identifier of the beer.
		ABV: Alcohol by volume of the beer.
    		62 NA observations
		IBU: International Bitterness Units of the beer.
    		1005 NA observations 
		Style: Style of the beer. 
    		5 Blank observations
		Ounces: Ounces of beer.
		Brewery_Name: Name of the brewery.
		City: City where the brewery is located.
		State: U.S. State where the brewery is located.

    Beers_And_Breweries_Cleaned.csv:

  		Brewery_ID: Brewery id associated with the beer.
		Beer_Name: Name of the beer.
		Beer_ID: Unique identifier of the beer.
		ABV: Alcohol by volume of the beer.
		IBU: International Bitterness Units of the beer.
		Style: Style of the beer. 
		Ounces: Ounces of beer.
		Brewery_Name: Name of the brewery.
		City: City where the brewery is located.
		State: U.S. State where the brewery is located.
