---
description: "Events in Melbourne"
featured_image: "/Figures_static/boxplot_gif.gif"
tags: ["scene"]
title: "The influence of Events in Melbourne on Pedestrian flow"
---

# Event Based Analysis

### Motivation:

The event based visualization is an effort towards understanding the pulse of the city of Melbourne. The Central Business District being an important area for socio cultural as well as business activity , would naturally be an ideal location for people to gather and express joy as they celebrate a win or usher in the new year. As a normal corollary, crowds would be expected to gather and demonstrations be called for to express their resentment towards a socio-political event, be it local or global.

A set of different events were chosen and the pedestrian traffic captures by the sensors on those days were plotted on a leaflet map. The visualization combines the volume based circle markers with an image and headline overlay relevant to the event.

![test](/Figures_static/NY19_gif.gif)

### Technical Overview:

Ipyleaflets along with Ipywidgets were used for this interactive visualization. Actual pedestrian volumes were plotted for the sensors based on their Latitude and Longitude information. Dropdowns were introduced to let the user pick the time of day and the event. Related images of the event and a newspaper headline related to the same were overlayed on the plot for a more intuitive experience of the reader

## A few data stories:

Following are a few events that told a story of their own via the sensors:

### Annual Event: New Years 2019

The sensors witnessed a shift in pedestrian volumes during the New Year celebrations at CBD. The average pedestrian volumes were comparatively higher than those witnessed on regular days.

![test](/Figures_static/events_NYE.png)

The above plot shows a comparison between the total pedestrian traffic by the hour on a regular Saturday, compared to the New Years eve which was a Saturday too. The pedestrian volumes are seen to rise during the late hours as people of Melbourne usher in the new year.

### Social Event: Global Climate Action day

We noticed a rise in the day time volumes until early evening on the day of 20-Sep-2019 a day when protesters hit the streets to demonstrate against global climate change. The crowds may have dispersed by the evening which is when we see the pedestrian volumes going back to normal levels.

![test](/Figures_static/events_GCC.png)

### Sporting Event: Melbourne defeats Adelaide to win the NBL Season

A rise in the pedestrian volumes was observed as compared to regular Saturdays during the evening hours on 31-Mar-2018 when Melbourne defeated Adelaide to clinch the NBL season. This could be attributed to the crowds coming out to watch the match together with their friends at the pubs or to rejoice the victory over mugs of beer

![test](/Figures_static/events_NBL.png)

### Synopsis:

The above stories give us an insight into the lives of people in Melbourne and triggers our imagination of how life is the city is. From our exploration of the data, an average office going "Melbourne-er" working at CBD would take the subway to work at around 8-9 am ( which probably explains the high volumes observed at some of the sensors). She would probably step out for a coffee break during to mid day or early afternoon and take short walk on the Bourke Street. Once she is done with the day's work, she is likely to catch up with her colleagues or friends for an informal chat during the evening at the restaurants and clubs(evening volumes in the sensors on weekdays and comparatively higher on Fridays) in that area before heading home. She may want to spend a longer time unwinding on Fridays as the weekend is here. Occasionally, she may witness a rally walking down the road during the day time(based on the pedestrian behavior during demonstrations) or hear a loud cheer coming from the nearby pubs in the evenings when the favorite sporting team brings the trophy home. 
