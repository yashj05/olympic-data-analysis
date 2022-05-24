
# Olympic Data Analysis

### About the project:

An in-depth analysis of Olympics Data (1896-2016), according to country, Sports, Athletes and much more.
Note that the Winter and Summer Games were held in the same year up until 1992. After that, they staggered
them such that Winter Games occur on a four year cycle starting with 1994, then Summer in 1996, then Winter in 1998, 
and so on. A common mistake people make when analyzing this data is to assume that the Summer and Winter Games have always been staggered.
### About the dataset: 

The file athlete_events.csv contains 271116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event (athlete-events). The columns are:

	ID - Unique number for each athlete
	Name - Athlete's name
	Sex - M or F
	Age - Integer
	Height - In centimeters
	Weight - In kilograms
	Team - Team name
	NOC - National Olympic Committee 3-letter code
	Games - Year and season
	Year - Integer
	Season - Summer or Winter
	City - Host city
	Sport - Sport
	Event - Event
	Medal - Gold, Silver, Bronze, or NA

### Insights to be found out:

Project is divided into 4 categories:
1. Medal Tally:	
        
		* Overall Tally of the medals(1896-2016).
		* Overall particular country performance.

2. Overall Analysis:	
		
		*Overview of overall analysis that includes:
			-Top Statistics.
			-Participating Nations over the years
			-Event over the years.
			-Athletes over the years.
			-Number of events over the time(Heatmap).
			-Most successful Athletes.

3. Countrywise Analysis:	
		
		* Medal tally over the years for a particular country.
		* Particular country's performance in following sports.
		* Top 10 Athletes of that particular country.

4. Athletewise Analysis:	
		
		* Distribution of Age.
		* Distribution of Age wrt Sports(Gold Medalist).
		* Height vs Weight.

### Key Insights:

* The most medals won by a country is USA a total of 2545 medals, second is Russia 1577 medals and third is Germany 1392 medals.
* Top Statistics:

	*Total official count of the olympics are 28. 
	
	*206 nations participated. 

	*52 sports and 651 events played.

	*Total 116122 athletes have participated in Olympics so far.

* Michael Fred Phelps, II is the most successful athlete from USA having won total of 28 medals.

* There is a dip in participating countries in olympics in 1904 and 1980.
	
	In 1904 tensions caused by the Russo–Japanese War, and the difficulties of getting to St. Louis in 1904, contributed to very few top-class athletes from outside the US and Canada taking part in the Games.
	
	In 1980 led by the United States, 66 countries boycotted the games entirely, because of the Soviet–Afghan War.

	**... and many more inside the report ! **

## Deployed App:https://share.streamlit.io/yashj05/olympic-data-analysis/main/app.py


