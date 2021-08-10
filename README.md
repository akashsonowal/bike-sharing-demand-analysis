# bike-sharing-demand-analysis

## Objective:
To understand the various factors affecting the test score using regression analysis.

## Approach:
Multiple linear regression model is used to predict the test scores by successively adding the most significant attribute affecting the test score based on various factors like correlation coefficient, adjusted R<sup>2</sup>, RSE, etc.

## Results:
Achieved R<sup>2</sup>

## Data Source:
Dataset: Student performance in secondary school (for Mathematics)
https://archive.ics.uci.edu/ml/datasets/student%2Bperformance

## Variables description:
#### Independent variables (32):
- School: student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
- Sex: student's sex (binary: 'F' - female or 'M' - male)
- Age: student's age (numeric: from 15 to 22)
- Address: student's home address type (binary: 'U' - urban or 'R' - rural)
- Famsize: family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
- Pstatus: parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
- Medu: mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)
- Fedu: father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)
- Mjob: mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
- Fjob: father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
- Reason: reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
- Guardian: student's guardian (nominal: 'mother', 'father' or 'other')
- Traveltime: home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
- Studytime: weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
- Failures: number of past class failures (numeric: n if 1<=n<3, else 4)
- Schoolsup: extra educational support (binary: yes or no)
- Famsup: family educational support (binary: yes or no)
- Paid: extra paid classes within the course subject (Math) (binary: yes or no)
- Activities: extra-curricular activities (binary: yes or no)
- Nursery: attended nursery school (binary: yes or no)
- Higher: wants to take higher education (binary: yes or no)
- Internet: Internet access at home (binary: yes or no)
- Romantic: with a romantic relationship (binary: yes or no)
- Famrel: quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
- Freetime: free time after school (numeric: from 1 - very low to 5 - very high)
- Goout: going out with friends (numeric: from 1 - very low to 5 - very high)
- Dalc: workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
- Walc: weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
- Health: current health status (numeric: from 1 - very bad to 5 - very good)
- Absences: number of school absences (numeric: from 0 to 93)
- G1: first period grade (numeric: from 0 to 20)
- G2: second period grade (numeric: from 0 to 20)

#### Dependent Variable (1):
- G3: final grade (numeric: from 0 to 20, output target)

## References:
http://www3.dsi.uminho.pt/pcortez/student.pdf

day.csv have the following fields:
	
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
	
=========================================
License
=========================================
Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}

=========================================
Contact
=========================================
	
For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)
