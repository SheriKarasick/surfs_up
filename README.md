# surfs_up
![Logo](wavy.png)

## Summary
We seek to set up a surf and shake shop on the island of Oahu, Hawaii.  In order to do this, we need to augment our business plan with quantitative and qualitative data about weather that will help them determine where to locate the business in Oahu, and other factors we may want to consider to ensure the businesses success. This will update the business plan to accomodate for previous failure that W.Avy has seen in similar ventures on the island and will get him more excited to be on board with investing in the business plan.

## Findings
With a surf shop, location, location, location is critical to ensuring the success of the business. Oahu is a small island, but with its rugged volcanic terrain, and Pacific location there are many physical structures that influence how wind passes over the island, where wind and how strong wind will come ashore, and when the rainy season will slow business to a virtual halt.  Given this knowledge coming into the analysis: an understanding of the island topography that is bolstered by 1) temperature data 2) precipitation data and 3) wave data will strengthen the proposal to ensure success.

### Analysis

###### Air temperature and precipitation
On the island of Oahu, there are 9 active monitoring stations that continuously gather data about air temperature and precipitation.  Let's begin our analysis by looking at how those variables vary throughout the year.

| Variable  | June | December
| ------------- | ------------- | ----------- |
| Air Temperature: Minimim (in)  | 64 F  | 56 F |
| Air Temperature: Maximum (in)  | 85 F  | 83 F |
| Air Temperature:Average (in)  | 75 F  | 71 F |
| Air Temperature:Std Dev  | 3.26  | 3.75 |
| Air Temperature  | Content Cell  | ------------ |
| Precipitation: Minimum (in)  | 0.0 |  0.0 |
| Precipitation: Maximum (in)  | 4.43  |  6.4 |
| Precipitation: Average (in)  | 0.14  |  0.22 |
| Precipitation  | Content Cell  |  ------------ |

![Comparative Histograms](/TempPrecipOahuFit.png)


###### Island topography
The Hawaiian Islands are characterized by seven types of geographic areas which significantly influence their climate. The result is great hyperlocal climatic variation, an important variable to note in planning.  Behind this climatic differential is 1) whether or not the area of the island is windward (subjected to direct wind) or leeward (buffered by wind by natural terrain.  In Oahu, the East side of the Island is windward, the West is leeward.  Between these two sides, terrain can be mountainous and tall or lowland depending on how the island was formed.  Oahu is noted for its interior lowlands and are subject to intense local aftermnoon showes with cloud formations associated with localized heating of terrestrial areas during the daytime.

###### Wind and waves
Surface waves require three key ingredients to build into the kinds of waves that surfers dream of.  Wind strength, fetch, duration all play important factors in ensuring quality and consistent waves.  Let's take a quick look at the wind conditions around the island of Oahu for the two months we are analyzing to see where, and during which months we could anticipate the best surfing conditions. 

Oahu lies in the 0 to 30 latitude range which is subject to strong tradewinds through the year (easterlies).  This means the East side of the island will enjoy strong winds that have had a significant unimpeded fetch on a year round basis.  Headlands are areas where wind forces converge, and there are four notable headlands where a surf and shake shop would be juxtapositioned to better wind conditions which will support the surf side of the business robustly.

The Pacific Station of the International Ocean Observing System maintains real-time data about wind velocity for the Island of Oahu.
![Sample wind vector images](samplewinds2.png)

###### Advisories
* Hawaii, like other areas of the world near water has a season where major storms are more predictable and regular.  During the months of Octtober through March (inclusive), major storm events occur regularly.  These storm systems bring strong winds, but also significant, torrential rain.  These storms generally coincide with the passing of a cold front through the area or a low pressure system. 
* Regular land and sea circulation patterns that result from heating of land during the day leading to convection currents that drive wind and rain patterns are a regular part of coastal living.  These pockets of air exchange can be very localized based on the characteristics of topography in the area.  ON the island of Oahu, the Ewa-Waianae Coast is an area where these diurnal patterns are quite regular bringing a sea breeze on shore in the afternoons. These patterns are associated with erratic patterns of weather bringing in rain, loocal storms, and winds reliably.

## Recommendations for future research

* This station data represents nine different station on one island which is subject to high variability in micro-climates across the island. While an analysis that examines all data across a time period for the island is interesting, the island itself is subject to great variability from station to station.  I would suggest using the wind data to determine two or three sites on Oahu that have sufficient wind to warrant a surf shop then perform a meta-analysis on the weather conditions for those stations in particular.
* The months of June and December were selected for this analysis, however wind data across a twelve month period shows that wind patterns vary greatly across the islands depending on the trade winds.  As two or three locations that appear more likely emerge, I would recommend evaluating wind patterns through the year so that slow seasons for surfing could be identified and alternative activities that are not wind dependent could be offered to potential customers (paddle boarding, kayaking, etc).
* With two or three sites in mind, I would examine the availability of transportation from major airports as a variable in location of the surf shop.  While winds might be optimal on some windward headlands, travel time from Honolulu airport to the surf shop may limit the number of travelers who will access the beach and utilize the services.  Tourist visitor data from hotels or local businesses could significantly augment the analysis.

## 
