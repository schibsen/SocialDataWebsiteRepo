---
description: "covid"
featured_image: "/Figures_static/covid_months_weekdays_accumulated.png"
tags: ["scene"]
title: "Influence of the Covid pandemic in Melbourne"
---
## 2020 - Influence of the Pandemic

In 2020 Melbourners had to live through, what have been termed one of the worlds most strict lockdown. So let's explore what happens when the most liveable city finds itself under one of the worlds hardest lockdowns. We have done some exploration, and build an interactive setup that allows you to explore further.  

Lockdowns are messy, there is no simple 'is' or 'is not' label you can put on a city on a given date, nor is there a well defined scale for stages of lockdown, as restrictions can be (and have been) combined in numerous ways. Even within the same city, some parts of the lockdowns taking place have been geographically differentiated. Furthermore, in a city, that usually attracts large amounts of tourists, pedestrian levels can be assumed not just to be influenced by local lockdowns, but also travelling restrictions from abroad, or from other parts of the country. Thus, instead of defining one lockdown period or creating a scale, we consider 2020 a 'special year', and study the temporal and spacial patterns, bearing in mind that especially from march-may and july-october, there were particularly strict regulations. However we also study patterns of 'recovery' and 'pauses' in the lockdown, seeing that especially december were close to 'corona free'.Still it is possible to pick days and weeks in which it can't be argued, that a strict lockdown were in place, and study pedestrian patterns during this time, compared to the same time the years before.  

#### Temporal patterns

2020 was not 'just covid'. In the first two month, WHO had not yet decared the global pandemic, and most cities around the world were not really affected. Also reaching December, Melbourne and all of the state of Victoria was 'corona free' for the majority of the month. Regulations shift constantly in an attempt to do what is necessary, but not more that that. 

Though every city have their individual heartbeat, the heartneats ahare many similarities. On weekdays we work. On Friday and Saturday, we are more likely to go out at night. On weekdays leisure activities dominate. Thus, the way the pandemic influence these speres of life, can be expected to be reflected in out data. 

So what does the weekly and monthly pedestrian volumes tell us?

![test](/Figures_static/covid_months_weekdays_accumulated.png)

The left plot shows the accumulated monthly counts of pedestrians over melbourne for the years 2018-2020. Notice, that where there were fewer pedestrians in january and feruary 2019 than the year before, the trend shifted, and february 2020 were the 10th consecutive month, where pedestrian volumes were higher that the same month the year before. Pedestrian volumes in Melbourne were on an upward trend when covid19 hit. 

The green bars representing 2020 clearly shows the two waves of covid in Melbourne. In april the pedestrian volumes ht a minimum, then restrictions were lifted a little, and in may and june, we see some recovery, before the second wawe hits, and volumes dips even lower, for a longer duration this time. Towards the end of the year though, volumes are clearly rising again. However, we dont see a full return to pre-corona levels, even though december 2020 epidemiologically was 'corona free' untill 30th of december (having epidemiologically eliminated the virus by the end of november with 28 consecutive days with 0 new cases, and 0 deaths and 0 active cases, which lasted untill 30th of December).  

The plot to the right show the weekly patterns. It is clear that the most busy day is Friday, and the least busy is Sunday, and that this tendency has been somewhat 'flattened' in 2020, though it still exist. In order to understand if this is only an effect of the two first month, we must further disaggregate the data, to reflect both weekly and montly variations. Furthermore it will be more informative to also be able to look at the data for specific sensor locations. 

### Spacial patterns

As we know from the data analysis the pedestrian volumes differ a lot between the sensors. So do the degree to which the volume has droped from 2018 to 2020. 

On the plot below, the pedestrian volume for each sensor is plotted for the years 2018-2019-2020 as a proportion of their volume in 2018. It is noticed that the volumes fpr 2020 varies between one third and two third of the volume from 2018. 

![test](/Figures_static/covid_spacial_n.png)

### Temporal and spacial patterns - 3 areas hit differently

![test](/Figures_static/three_covid_stories.png)

The first of the three plots above is from Lydon in July, between the first two wawes. The patterns from 2018 and 2019 where volumens are highest on fridays and saturdays, indicates an active nghtlife. With sundays having higher volumes than weekdays also leisure activities. In July 2020 on the other hand, there is no difference between the weekdays.

The second plot, which is from Spencer St-Collins Station (South), shows a very different pattern. Here weekdays are much busier than weekends, indicating that this is a business district. This area is also the one where 2020 differs most from the previous year, indicating that the activities in this area were due to severe restictions (offices or other activities, that could be carried out remotely or were deemed non-essential). 

The final plot is from New Quay. Here pedestian volumes do not show a strong weekly pattern, and also the difference between 2020 and previous years is smaller. This indicated, that the majority of pedestrians passing this sensor are doing so, while engaged in everyday activities such as grossary shopping. 

Are you curious about other locations or months? Go explore in the interactive plot below



{{< covid_bokeh2 >}}



