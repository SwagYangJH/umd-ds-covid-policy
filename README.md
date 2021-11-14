# State Specific Covid Policy Effectiveness (USA)

## Team
- __Samarth Negi__ [samarth](https://github.com/tigboatnc)
- __Ally__
- __Chao Cao__
- __Jinhua Yang __

------------ 

## HEAD 


#  1. State Profiling `ally`

## Description


All state profile dataset to be managed by ally. 
>Send it to him in this format 
>|stateCode|stateName|Property{Obesity,bachelorOrHigher,.....}|
>|----|----|----|
>|AZ|Arizona|24.3|
>|....|....|....|

## State Profile Data Gathering

|Property|Assigned To|Source|Location in Repository|Year|Status|Description|
|---|--|--|---|---|----|---|
| __stateName__|`global`|[random github](https://github.com/jasonong/List-of-US-States/blob/master/states.csv )|[us_states](datasets/us_states.csv)
| __stateCode__| `global`|[random github](https://github.com/jasonong/List-of-US-States/blob/master/states.csv )|[us_states](datasets/us_states.csv)
| __peak1__| `george`|
| __peak2__| `george`|
| __peak3__|`george`|
| __peak4__| `george`|
| __obesity__| `chao`|https://www.cdc.gov/obesity/data/prevalence-maps.html#downloads|[chao_obesity](datasets/chao_obesity.csv)|2020|Done|Prevalence of Self-Reported Obesity by State and Territory, BRFSS, 2020|
| __employmentRate__|`samarth`|[.gov census page](https://data.census.gov/cedsci/map?q=Total%20Population&tid=PEPPOP2019.PEPANNRES&cid=DATE_CODE&vintage=2019&layer=VT_2019_040_00_PP_D1)|[sam_censusdata_merged.csv](datasets/sam_censusdata_merged.csv)|2019|To Verify|
| __employerEstablishments__|`samarth`|[.gov census page](https://data.census.gov/cedsci/map?q=Total%20Population&tid=PEPPOP2019.PEPANNRES&cid=DATE_CODE&vintage=2019&layer=VT_2019_040_00_PP_D1)|[sam_censusdata_merged.csv](datasets/sam_censusdata_merged.csv)|2019|To Verify|
| __totalHousingUnits__|`samarth`|[.gov census page](https://data.census.gov/cedsci/map?q=Total%20Population&tid=PEPPOP2019.PEPANNRES&cid=DATE_CODE&vintage=2019&layer=VT_2019_040_00_PP_D1)|[sam_censusdata_merged.csv](datasets/sam_censusdata_merged.csv)|2019|To Verify|
| __withoutHealthcareCoverage__|`samarth`|[.gov census page](https://data.census.gov/cedsci/map?q=Total%20Population&tid=PEPPOP2019.PEPANNRES&cid=DATE_CODE&vintage=2019&layer=VT_2019_040_00_PP_D1)|[sam_censusdata_merged.csv](datasets/sam_censusdata_merged.csv)|2019|To Verify|
| __totalHouseholds__|`samarth`|[.gov census page](https://data.census.gov/cedsci/map?q=Total%20Population&tid=PEPPOP2019.PEPANNRES&cid=DATE_CODE&vintage=2019&layer=VT_2019_040_00_PP_D1)|[sam_censusdata_merged.csv](datasets/sam_censusdata_merged.csv)|2019|To Verify|
| __hispanicOrLatinos__|`samarth`|[.gov census page](https://data.census.gov/cedsci/map?q=Total%20Population&tid=PEPPOP2019.PEPANNRES&cid=DATE_CODE&vintage=2019&layer=VT_2019_040_00_PP_D1)|[sam_censusdata_merged.csv](datasets/sam_censusdata_merged.csv)|2019|To Verify|
| __medianAge__|`samarth`|
| __noInternetSubscription__|`samarth`|
| __olderPopulation65__|`samarth`|
| __veterans__|`samarth`|
| __medianHouseholdIncome__|`samarth`|[.gov census page](https://data.census.gov/cedsci/map?q=Total%20Population&tid=PEPPOP2019.PEPANNRES&cid=DATE_CODE&vintage=2019&layer=VT_2019_040_00_PP_D1)|[sam_censusdata_merged.csv](datasets/sam_censusdata_merged.csv)|2019|To Verify|
| __poverty__|`samarth`|
| __population__|`samarth`|[.gov census page](https://data.census.gov/cedsci/map?q=Total%20Population&tid=PEPPOP2019.PEPANNRES&cid=DATE_CODE&vintage=2019&layer=VT_2019_040_00_PP_D1)|[sam_censusdata_merged.csv](datasets/sam_censusdata_merged.csv)|2019|To Verify|
| __bachelorsOrHigher__|`samarth`|[.gov census page](https://data.census.gov/cedsci/map?q=Total%20Population&tid=PEPPOP2019.PEPANNRES&cid=DATE_CODE&vintage=2019&layer=VT_2019_040_00_PP_D1)|[sam_censusdata_merged.csv](datasets/sam_censusdata_merged.csv)|2019|To Verify|
| __mentalDisorders__ |`ally`|
| __politicalAfiliation__|`george`|[Gallup Historical Trends](https://https://news.gallup.com/poll/15370/party-affiliation.aspx
| __voterTurnout__|`george`|[IDEA usa](https://www.idea.int/data-tools/country-view/295/40
| __noHospitals__|`george`|
| __hospitalBeds__|`george`|[WHO hospital beds](https://www.who.int/data/gho/data/indicators/indicator-details/GHO/hospital-beds-(per-10-000-population)
| __q1Mobility__|`chao`|
| __q2Mobility__|`chao`|
| __q3Mobility__|`chao`|
| __q4Mobility__|`chao`|
|__fireDeptByState__|`chao`|[This NFPA Paper](https://www.nfpa.org/-/media/Files/News-and-Research/Fire-statistics-and-reports/Emergency-responders/osNumberOfFireDeptInUS.ashx)|[chao_fire.csv](datasets/chao_fire.csv)|2017|


[Might help but currently unvalidated](https://www.ahd.com/state_statistics.html)
[Scrape this](https://data.census.gov/cedsci/profile?g=0400000US02)




# 2. Effectiveness Metric `chao` `george`

## Description

## Effectiveness Metric Data Gathering
|Property|Assigned To|Source|Location in Repository|Year|Status|Description|
|---|--|--|---|---|----|---|
| __appleDataMobilityUsa__|`chao`|[Apple Mobility](https://covid19.apple.com/mobility)|[apple_data_mobility.csv](datasets/apple_data_mobility.csv)|9 November 2021|Country Mobility by apple|
| __googleDataMobilityUsa__|`chao`|[Google Mobility](https://www.google.com/covid19/mobility/)|[google_data_mobility_usa.csv](datasets/google_data_mobility_usa.csv.zip)|9 November 2021|Country Mobility by google|

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
