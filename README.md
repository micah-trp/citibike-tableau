# citibike-tableau
The following repository is required to create the Citibike tableau file.
The repository compares bike rental trip data over the summer months of 2019 / 2020 (June -August).
The purpose of the dashboard is to identify impacts as a result of the 2020 New York Lockdoan in trip time, distance, and renter demographics.  

### Findings
Analysis identified that younger people made more trips in 2020. Those in working age made less.   
All groups had an increase in the trip duration (+44.1% overall) and made  longer journeys (+0.3km average increase). 
  
We saw a stark increase in the overall percentage of trips > 4km - with the top stations along the west side of Manhattan Island. 
Review Images tab. This may be an indicator that more people are using citibikes as a public transport substitution in 2020 where we saw an increase to this bucket - in line with the average New York public transport transit of 9.5 km [source](https://moovitapp.com/insights/en/Moovit_Insights_Public_Transit_Index-countries).  

## Tableau Story Link
Access the following link to view the story of the overall project and findings.
- [Citibike Story Link](https://public.tableau.com/app/profile/micah.raquena.pequeno/viz/CitiBikeStory_16901975991970/CitiBikeAnalysis?publish=ye)

## Tableau Map Dashboard
Access the following link to view the Citi Bike Map dashboard- filterable by Trip Journey and year- with a view of each station - Bubble size and color set to the match the monthly trips results. 
- [Tableau Map Dashboard](https://public.tableau.com/app/profile/micah.raquena.pequeno/viz/CitiBikeMap_16901950070280/MapDashboard?publish=yes)

## Tableau Age Group Dashboard
Access the following to view Citibike Map summary by age group..
- [Tableau Age Group Dashboard](https://public.tableau.com/app/profile/micah.raquena.pequeno/viz/CitiBikeAge_16901980427950/AGE?publish=yes)

## Tableau Distance Group Dashboard
Access the following to view Citibike Map summary by agdistancee group.
- [Tableau Distance Group Dashboard](https://public.tableau.com/app/profile/micah.raquena.pequeno/viz/CitiBikeDistance/Distance?publish=yes)


## Data Preparation
Refer to notebook file "citi_bike_python.ipynb" for data cleaning ane prearation.  

## Data Source & New ExtractCreation 
Extracts for Jun-Aug 2019 & 2020 were downloaded from website [Citibike- Trip History](https://citibikenyc.com/system-data) and ingested during the datafetch process.
Final data sources were created: 
- map_data.csv
- start_1920_age_group.csv
- start_20190_distance_group.csv
- stations.csv
