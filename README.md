# Alcohol, Temperature, and Religion: Who Drinks the Most, and Where?
Data exploration in R and Tableau of fivethirtyeight.com dataset regarding world alcohol consumption. Data cleaned partially in Excel and partially in R. Data plotted in R and Tableau.

Dataset info and discussion:
I found a dataset on fivethirtyeight containing data on alcoholic beverage consumption for the world: https://github.com/fivethirtyeight/data/tree/master/alcohol-consumption. I decided to use this dataframe as a basis for an expanded analysis. I was curious if there was a correlation between extreme temperatures and increased alcohol consumption. I also wanted to see which world regions drank the most alcohol.

The world temperature data was obtained from https://www.revolvy.com/page/List-of-countries-by-average-yearly-temperature. The data reflects average temperatures from 1961-1990. 

Next I created the World_Region csv file with the help of www.worldatlas.com and Pew Research Center. There was great variation on the Internet for divvying up the world into regions. For the purposes of this analysis, I split the world’s countries into eight regions: Africa, Asia, Caribbean, Europe, Middle East, North America, Oceania, and South America. I chose to combine Central America with Canada and the USA for the sake of comparison.

After some analysis, I became curious to see how majority belief system might be connected to alcohol consumption. I added data in Excel to the drinks_join dataframe, then re-import the dataframe into RStudio. The belief system data was obtained from the Pew Research Center Global Religious Futures project: http://www.globalreligiousfutures.org.

Conclusions: There was a weak negative correlation between average temperature and average servings. Regions which observed some form of Christianity as the majority belief system also had the highest number of average servings. Asia has the greatest belief system diversity; almost all major religions are observed on that continent, with the exception being Judaism.

