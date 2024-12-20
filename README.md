# Berlin's Crime Landscape

## Executive Summary
This project explores crime trends in Berlin from 2013 to 2022, aiming to provide insights into neighborhood safety for residents and the general public. As a non-German resident and parent living in Berlin, this analysis stems from a personal motivation to understand the city’s safety, especially with a young child, while addressing claims that link crime rates to migration.

## Key Findings
- **Mitte Leads in Crime:** Mitte consistently ranks as the district with the highest crime rate, largely due to its role as a hub for tourists and dense urban activity.
- **Migration and Population Growth:** There is no direct correlation between increasing foreign populations and crime rates, challenging stereotypes and suggesting a need to investigate other contributing factors.
- **Theft and Neighborhood Crime Dominate:** Theft and neighborhood-level crimes are the most common across all Berlin neighborhoods, particularly in high-density, tourist-heavy areas such as Alexanderplatz and Tiergarten Süd.
- **Poverty Risk and Crime:** No clear relationship between district poverty risk and crime rates was observed, indicating that socio-economic factors may interact in more complex ways.


## Motivation:
As a non-German resident of Berlin, I wanted to understand the city’s safety. Despite not experiencing crime personally, frequent news reports suggest rising crime rates. With a young son, I aim to identify safer districts and neighborhoods. Additionally, I seek to examine claims suggesting a correlation between rising crime rates and the influx of non-Germans into the city, as echoed by public sentiment and some political groups. 

## Objective:
Pinpoint neighborhoods with higher and lower crime risks.
Identify prevalent crime types in Berlin’s districts.
Explore correlations between crime rates, population trends, and poverty risk.

## Scope:
This analysis only covers 2013 to 2022, and risk of poverty data is only for 2022.

## Data limitation
### Crime Data Limitations
**1.	Granularity:**
   -  Crime data is only available at the neighborhood level and does not include specific street or area information.
**2.	Incomplete Crime Reporting:**
   - Crimes with untraceable locations (e.g., pickpocketing where the victim cannot recall the incident location) and certain categories like shoplifting, fare evasion, terrorism, racism, or discrimination are excluded.
**3.	Underreporting:**
 - Some crimes might go unreported, leading to incomplete data representation. 

### Population Data Limitations
**1.	Lack of Combined Demographics:**
  -	Population data is broken into separate attributes such as gender, nationality, and migration background but does not provide combined views (e.g., non-German females).
**2. Granularity:**
  - Population data only includes the total population of Berlin, and does not include district or neighborhood granularity.

## Data Questions
**1.	Overall Crime Trends:**
  -	How have crime rates changed in Berlin from 2013 to 2022?
  -	Are there specific crime categories with a noticeable increase or decrease over time?
**2.	Geographical Crime Analysis:**
  -	Which neighborhoods or districts have the highest and lowest crime rates per 100,000 population?
  -	Are certain types of crimes more prevalent in specific districts or neighborhoods?
**3.	Temporal Analysis:**
  -	How do crime rates vary over the years within individual districts?
**4.	Correlation with Population:**
  -	Do districts with higher populations have a higher rate of certain crimes per 100,000 population?
**5.	Nationality and Migration Background:**
  -	Is there any relationship between crime rates and the proportion of Germans versus foreigners in Berlin?
  -	Does the proportion of individuals with or without migration backgrounds correlate with crime rates in the city?


# Data Sources
Population with migration background - [Amt für Statistik Berlin-Brandenburg](https://www.statistik-berlin-brandenburg.de/kommunalstatistik/einwohnerbestand-berlin), accessed 9 December 2024

Berlin crime rate - [Polzei Berlin](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/atlas.html), accessed 9 December 2024

Berlin population from 1950 - 2035 (projected) - [Macrotrend](https://www.macrotrends.net/global-metrics/cities/204296/berlin/population), accessed 13 December 2024

Berlin Poverty Risk- [Amt für Statistik Berlin-Brandenburg](https://www.statistik-berlin-brandenburg.de/archiv/a-i-10-a-i-11-a-vi-2-j), accessed 13 December 2024

Berlin Geodata - [Open Data Informationsstelle Berlin](https://daten.odis-berlin.de/), accessed 12 December 2024
