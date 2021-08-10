# bike-sharing-demand-analysis

## Objective:
To understand the various factors affecting the test score using regression analysis.

## Approach:
Multiple linear regression model is used to predict the test scores by successively adding the most significant attribute affecting the test score based on various factors like correlation coefficient, adjusted R<sup>2</sup>, RSE, etc.

## Results:
Achieved R<sup>2</sup>

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

#### Contact
For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)
