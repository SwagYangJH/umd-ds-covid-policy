# State Specific Covid Policy Effectiveness (USA)

## Team
- __Samarth Negi__ [samarth](https://github.com/tigboatnc)
- __Ally__
- __Chao Cao__
- __Jingua Yang / Jang ?__

------------ 

## HEAD 


#  1. State Profiling `ally`
All state profile dataset to be managed by ally. 
>Send it to him in this format 
>|stateCode|stateName|Property{Obesity,bachelorOrHigher,.....}|
>|----|----|----|
>|AZ|Arizona|24.3|
>|....|....|....|

#### Metric Completion Table

|Property|Assigned To|Source|Location in Repository|Year|Status|Description|
|---|--|--|---|---|----|---|
| __stateName__|`global`|
| __stateCode__| `global`|[random github](https://github.com/jasonong/List-of-US-States/blob/master/states.csv )|[us_states](datasets/us_states.csv)
| __peak1__| `samarth`|
| __peak2__| `samarth`|
| __peak3__|`samarth`|
| __peak4__| `samarth`|
| __obesity__| `chao`|https://www.cdc.gov/obesity/data/prevalence-maps.html#downloads|datasets/chao_obesity.csv|2020|Done|Prevalence of Self-Reported Obesity by State and Territory, BRFSS, 2020|
| __bachelorOrHigher__|`samarth`|
| __employmentRate__|`samarth`|
| __totalHousingUnits__|`samarth`|
| __withoutHealthcareCoverage__|`samarth`|
| __totalHouseholds__|`samarth`|
| __medianAge__|`samarth`|
| __noInternetSubscription__|`samarth`|
| __olderPopulation65__|`samarth`|
| __veterans__|`samarth`|
| __medianHouseholdIncome__|`samarth`|
| __poverty__|`samarth`|
| __population__|`samarth`|
| __bachelorsOrHigher__|`samarth`|
| __mentalDisorders__ |`ally`|
| __politicalAfiliation__|`george`|
| __voterTurnout__|`george`|
| __noHospitals__|`george`|
| __hospitalBeds__|`george`|


[Might help but currently unvalidated](https://www.ahd.com/state_statistics.html)
[Scrape this](https://data.census.gov/cedsci/profile?g=0400000US02)




# 2. Effectiveness Metric `chao` `george`


## Moving Average 
> To Judge the effectiveness of a covid policy, we use moving averages of new daily cases as a metric. 


__IDEAS__<br/>
1. [Pandas Rolling](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.rolling.html)
2. 


# 3. Final Model `samarth` `ally` `george` `chao`



<!-- ## Datasets  -->
<!-- | Dataset  | Location | Link |
| ------------- | ------------- |----|
| Covid Factors  | datasets/Conditions_Contributing_to_COVID-19_Deaths__by_State_and_Age__Provisional_2020-2021.csv  ||
|US States|datasets/us_states.csv|-->
