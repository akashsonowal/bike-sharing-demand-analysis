# bike-sharing-demand-analysis

## Objective:
To understand the factors affecting the demand for shared bikes in the American market to help us come up with a mindful business plan to be able to accelerate its revenue.

## Approach:
- Carried out multivariate statistical regression analysis to study significant variables in predicting bike sharing demand.
- Performed distplots analysis, multicollinearity check using VIF, Feature selection using RFE based on p values.

## Results:
Achieved Adjusted R<sup>2</sup> of 0.728 with the final OLS model of only 7 input features with 95% confidence.

## Dataset Characteristics:

[Dataset](https://www.kaggle.com/gauravduttakiit/bike-sharing) have the following fields:
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered
	


#### License:

Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, [doi:10.1007/s13748-013-0040-3](http://dx.doi.org/10.1007/s13748-013-0040-3).

#### Contact:
For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)
