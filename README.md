# Daily-Ambient-Temp-and-Crime-Rates-for-the-City-of-Vancouver
Assessing the Relationship Between Daily Ambient Temperature and Crime Rates for the City of Vancouver: A Big Data Approach

Abstract
Past literature in the field of psychology has shed light on the relationship between high ambient temperatures and aggressive behaviours exhibited by individuals under these conditions (Hipp et. al., 2014; Steinberg, 1979; Anderson & Anderson, 1998). Using both real-world secondary data collection, as well as lab experiments, past researchers have shown the positive relationship between temperature and violent crimes, such as assault (Feldman & Jarmon, 1979; Michael & Zumpe, 1983a; Rotton & Frey, 1985), rape, and burglary (Cohn, 1990). Using big data analytics, we aim to replicate these past findings utilizing open crime and weather data provided by the City of Vancouver (crime) and the National Weather Service (weather). While taking in to account possible confounds addressed in past literature, we anticipate finding a positive correlation between crime rates and daily temperature.

Introduction
It is no secret that whenever the weather starts looking bright, the city streets become more and more crowded with people looking to enjoy some time outside. Hipp & colleagues elaborates on a concept they call “Temperature-Aggression Theory”, which states that due to underlying biological mechanisms, “hot temperatures lead to greater discomfort, which in turn gives rise to more aggressive behaviour” (Hipp, Bauer, Curran, & Bollen,2004). Not only is it put forward that heat influences aggressive behaviours, but work done by several researchers suggests that a positive correlation exists between temperature and assaults (Feldman & Jarmon, 1979; Michael & Zumpe, 1983a; Rotton & Frey, 1985). Taking this into consideration, we aim to highlight the positive correlation between temperature and the rate of crime in Vancouver by analyzing public data records for both weather and crime.
The advantage of using these naturally occurring data sets is that it increases external validity in our research. Obtained results are from a large population size so results can be generalized to make predictions about the population. The data shows the involvement of temperature in individual’s decisions and behaviors through crime. By using real data from crime rates and temperature, all results, findings, and analysis can be used to characterize likely behaviors during certain temperatures. Temperature, as an environmental component, can be used to determine factors that shape the cognitive processes.
This year, we have broken a 61-year old record for rainfall, and clear weather is in high demand (Judd, 2017). While this may be true, we also speculate that amidst the increase in outdoor activities, there is also an increase in criminal behaviour. By finding a positive correlation between crime and weather here in Vancouver, while isolating and ruling out confounds, we aim to educate our local community on this phenomenon so they may take precautions when summer does arrive.
One can argue that along with the hot weather there are other variables at play which can influence the crime rate, and we have taken these into consideration. The temperature-aggression theory forgoes the statistical perspective suggested by the routine activity theory (Cohn & Rotton, 2000), which states that since people are outside and interacting more, they inevitably run into more opportunities to engage in conflict or criminality (Pedersen, 2016). Looking at this possible confound, we have reached out to TransLink BC to gather ridership data to roughly address the amount of foot traffic throughout the city by analyzing the number of people utilizing their services year-round. Since the same amount of people may be outside in 15-degree weather vs. 20-degree weather, the Routine Activity Theory may not be able to explain why there may be more crimes in both scenarios. To elaborate on this phenomenon, Steinberg’s (1979) general aggression model also suggests that hot weather makes people uncomfortable and irritated, which reinforces the predictions of Temperature-Aggression Theory. 
Further facilitating this research, Anderson and Anderson’s (1998) General Affect (GA) model suggests that extreme temperatures facilitate affective aggression, which they describe as being aggression with the purpose of causing personal injury. In Baron and Bell’s (1976) study, they highlight the relationship between aggression and heat through the theory known as Negative Affect Escape. Their study showed that lower levels of aggression were seen when temperature increases from 80 degrees Fahrenheit to 95 degrees Fahrenheit, as participants found the temperature unbearable. It was theorized that unbearable temperatures may suppress aggression because people want to leave the heat (Baron and Bell, 1976). Aggression leading to crime may go up when it is warm outside but when the heat becomes extreme, the crime goes down again.
As suggested by the routine activity theory, warm weather makes people spend more time outside, which leads to more opportunity for crime. Mares (2013) references the routine activities perspective which states that many crimes are motivated when offenders encounter alluring targets in the absence of guardians. Changes in temperature will affect the number of motivated offenders and targets as people like to go outside more in warm weather, increasing the chances that offenders will encounter possible targets (Agnew, 2011).	
As researchers have considered these possible confounds, there is not a complete consensus regarding temperature’s influence on total number of crimes, many researchers have comfortably stated that crimes such as assaults, burglaries, collective acts of violence, domestic violence, and rape all tend to positively correlate to the mean temperature over many geographical and demographic areas (Cohn, 1990). On the relationship between temperature and violent crimes (preceded by aggression), we seek to further validate these findings using the big data available to us here in Vancouver. In doing so, we will also highlight the relationship between temperature and total crime rates, including property and victimless crimes.

Proposed Methods
The purpose of this correlational study is to explore factors related to temperature and crime rates within the Vancouver area. Our study will utilize archived data gathered in 2003 to 2017 (Vancouver) daily. We obtained the data from the Government of Canada, for climate, and the City of Vancouver, for crime.
There are many studies linking weather and crime. In Mares (2013) article, she analyzes Rotton and Cohn’s study examining the link between weather and crime. The study examined examining 50 large cities in the US for a prolonged period. As well as Anderson, Bushman and Grooms (1997) study which found that “violent crimes in particular are likely to face upward pressure as climate changes increases temperature anomalies” (Mares, 2013).
the temporal resolution of the data is crucial for you. For example, a year of data broken down to weekly averages will not give you a strong correlation, but a year of data broken down to hourly averages may. 

Years of Data Used
Taking the methods of past research into consideration, the time frame for our study is between January 1, 2003 and June 16, 2017, and will include analysis of hourly temperature and crime fluctuations, as well as a year-by-year comparison. During this time frame the Vancouver Police Department logged 512,038 crimes in the area.

Research Question
RQ: Is there a strong positive correlation between temperature and crime rates in Vancouver?

Research Method
To address the study research question, the correlation study will generate insightful information on crime rates and weather patterns. The study is utilized to understand the analysis of the archived data. The correlation design is used for the research study as it offers a way to look at the data with multiple variables and determine the relationships between them.

Population and Sampling
The population for weather data comes from the area of Vancouver . As for crime data, the population came from the people who committed the crimes (theft, homicide, etc.). The data used for the study was archived by the Government of Canada, for climate, and the City of Vancouver, for crime. Since the data utilized was archived with public access there was no consent required.

Data Analysis
The weather data for each year and crime rates during these have been obtained, and calculations will be run for each year. The temperatures from each month and day will be examined. Temperature and crime rate data will be cross referenced to find correlations. All days from January 1, 2003 to June 16, 2017 will be taken and grouped by recorded temperature. The crimes committed during specific temperatures will be added together. The number of crimes committed at a given temperature will be cross-referenced within all days. To accomplish this analysis, the full CSV file of 512,038 crimes were downloaded as well as the weather data for the time-period chosen.
Include example MySQL calls
How will you set up the MySQL database? Describe tables, and columns, and their definitions. 
Describe your Amazon AWS virtual server

Confounding Variables
Higher temperatures have been reported to lead to un-comfortability, which leads to less desire to commit crime. Baron and Bell (1976) show this in their study on the relationship between aggression and heat through the theory known as “Negative Affect Escape.” Their study showed that lower levels of aggression were seen when temperature increases from 80 degrees Fahrenheit to 95 degrees Fahrenheit, as participants found the temperature unbearable. It was theorized that unbearable temperatures may suppress aggression because people want to leave the heat (Baron and Bell, 1976). Aggression leading to crime may go up when it is warm outside but when the heat becomes extreme the crime goes down again.
Further, Warm weather makes people spend more time outside, which leads to more opportunity for crime, as suggested by the Routine Activity Theory. Mares (2013) references the routine activities perspective which states that many crimes are motivated when offenders encounter alluring targets in the absence of guardians. Changes in temperature will affect the number of motivated offenders and targets. Warmer weather alters routine activities. People like to go outside more in warm weather, “increasing the likelihood that motivated offenders will encounter victims and leaving more homes unprotected.” (Agnew, 2011).	
The time of day could play a part in crime rates as well. “Both time of day and assaults are strongly correlated with temperature, but in opposite directions.” Though time of day does also correlate with the temperature. Such as, cooler temperatures in the early morning or late evening hours. Also, during different times of the day there are different types of activities and environments people involved in (Bushman, Anderson and Wang, 2005).
The type of area will be a considerable factor in number and type of crime rates. The correlation between weather and crime is shown to be strongest in rural areas by Ikegaya and Suganami (2008), where as people in rural areas “tend to be influenced by weather to a greater extent.”
Research reveals that food and freshwater shortages are linked with negative emotions, such as frustration and anger (Agnew, 2011). With the increase of negative emotions comes the increase of crimes. With such shortages, it was supposed that the negative emotions would lead to individual crimes. Individuals feel they must take steps to survive and protect others close to them. However, there is little research on the effect of the food and fresh water shortages on crime rates (Agnew, 2011).
In addition to food and freshwater shortages, climate change will increase poverty. Agnew (2011) explains numerous reasons for this relationship. Poverty is a stressor which may lead to secondary stressors and then to crime. Research reveals “poverty and inequality are among the best predictors of crime” (Agnew, 2011).

Data Analysis Sample
	As an example of our intended analysis, we arbitrarily chose 5 days from both January and July in the years 2003 and 2007 for a total of 20 data points. Using Microsoft Excel to scrape through the data, the total number of crimes were recorded for each day and are displayed beside the mean temperature for each day referenced (Table. 1). The data is also displayed in a scatterplot (Figure. 1) to visualize the distribution of crimes committed in relation to mean temperature.
	By running a correlational analysis on the 2 variables, a value of -0.43 was determined. This moderate negative relationship between temperature and crime rates is contrary to our initial hypothesis; however, due to the extreme size difference between our sample and the totality of the available data, we anticipate that our findings may differ greatly. In the case that our later analysis mirrors our sample shown here, we will further investigate the possible causes 
Date/Time	Year	Month	Day	Mean Temp (°C)	Total Number of Crimes Committed
2003-01-01	2003	1	1	6.9	191
2003-01-02	2003	1	2	8.8	149
2003-01-03	2003	1	3	9.6	160
2003-01-04	2003	1	4	9.6	146
2003-01-05	2003	1	5	7.1	120
2003-07-01	2003	7	1	16.8	142
2003-07-02	2003	7	2	15.9	120
2003-07-03	2003	7	3	17.5	138
2003-07-04	2003	7	4	18.5	147
2003-07-05	2003	7	5	19.3	133
2007-01-01	2007	1	1	6.7	157
2007-01-02	2007	1	2	9.1	133
2007-01-03	2007	1	3	6.5	139
2007-01-04	2007	1	4	4.5	109
2007-01-05	2007	1	5	4.4	123
2007-07-01	2007	7	1	17.3	112
2007-07-02	2007	7	2	19.4	103
2007-07-03	2007	7	3	20.1	115
2007-07-04	2007	7	4	20.1	98
2007-07-05	2007	7	5	19.5	105
for the phenomenon. For this reason, the samples provided are for reference only.

References
Agnew, R. (2011). Dire forecast: A theoretical model of the impact of climate change on crime. Theoretical Criminology, 15(3), 1–22. doi:10.1177/1362480611416843. 
Anderson, C. A., & Anderson, K. B. (1998). Temperature and aggression: Paradox, controversy, and a (fairly) clear picture, In R. Geen & E. Donnerstein, (Eds), Human Aggression: Theories, Research and Implications for Social Policy. San Diego, CA: Academic Press.
Anderson, C. A., Bushman, B. J., & Groom, R. W. (1997). Hot years and serious and deadly assault: Empirical tests of the heat hypothesis. Journal of Personality and Social Psychology, 73, 1213–1223. doi:10.1037/0022-3514.73.6.1213
Baron, R. A., & Bell, P. A. (1976). Aggression and heat: The influence of ambient temperature, negative affect, and a cooling drink on physical aggression. Journal of Personality and Social Psychology, 33, 245–255.  doi:10.3758/BF03337050
Bushman, B. J., Wang, M. C., & Anderson, C. A. (2005). Is the curve relating temperature to aggression linear or curvilinear? Journal of Personality and Social Psychology, 89(1), 74–75. doi:10.1037/0022-3514.89.1.74
Cohn, E. G., & Rotton, J. (2000). Weather, seasonal trends and property crimes in Minneapolis, 1987-1988. A moderator-variable time-series analysis of routine activities. Journal of Environmental Psychology, 20, 257-272. doi:10.1016/S0272-4944(05)80216-6.
Cohn, E. (1993). The prediction of police calls for service: The influence of weather and temporal variables on rape and domestic violence. Journal of Environmental Psychology, 13, 71-83
Cohn, E. G. (1990). Weather and crime. British Journal of Criminology, 30(1), 51-64.
Feldman, H. S., & Jarmon, R. G. (1979). Factors influencing criminal behaviour in Newark: A local study in forensic psychiatry. Journal of Forensic Science, 24, 234-239.
Hipp, J. R., Bauer, D. J., Curran, P. J., & Bollen, K. A. (2004). Crimes of opportunity or crimes of emotion? Testing two explanations of seasonal change in crime. Social Forces, 82(4), 1333-1372. doi:10.1353/sof.2004.0074.
Ikegaya, H., & Suganami, H. (2008) Correlation between climate and crime in eastern Tokyo. Canadian Journal of Criminology and Criminal Justice, 50(2): 225–238.
Judd, A. (2017, March 29). Metro Vancouver breaks 61-year-old rainfall record. Retrieved from http://globalnews.ca/news/3342245/metro-vancouver-breaks-61-year-old-rainfall-record/.
Mares, D. (2013). Climate change and crime: Monthly temperature and precipitation anomalies and crime rates in St. Louis, MO 1990-2009. Crime Law Soc Change 59, 185-208. doi:10.1007/s10611-013-9411-8.
Michael, R. P., & Zumpe, D. (1983). Annual rhythms in human violence and sexual aggression in the United States and the role of temperature. Social Biology, 30, 263-278. 
Pedersen, T. (2016, June 25). Why is hot weather linked to more violent crime? Retrieved from https://psychcentral.com/news/2016/06/25/why-is-hot-weather-linked-to-more-violent-crime/105329.html.
Rotton, J., & Frey, J. (1985). Air pollution, weather, and violent crimes: Concomitant time-series analysis of archival data. Journal of Personality and Social Psychology, 49, 1207-1220
Steinberg, H. (1979). The weather and psychopathology. Hillside Journal Of Clinical Psychiatry, 1(2), 231-243.

![image](https://user-images.githubusercontent.com/128402927/229387269-823df0ae-a090-46db-a426-c85fddf1c8b7.png)
