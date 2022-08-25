# Surfs_up Analysis
## Purpose of Analysis
The goal of this analysis was to analyze the temperature in specific areas of Hawaii using sqlalchemy and pandas in order to guide business decisions on the opening of a surfing/ice cream shop. 

The temperatures for the months of June and December will be queried separately using the sqlalchemy .extract function, and then descriptive statistics will be found about the temperature for those months. 

## Results of Analysis
### Questions to ask
Before doing analysis work the most important thing to have in mind is the goals. What are we actually trying to figure out with this data? Since our goal is to open a surf shop that means we want temperate weather during both the summer and winter months. The summer should not be too hot, and the winter should never get too cold. If we are able to show that, as well as consistency, then we will be able to make stronger business decisions. 

### June Results
<img src="https://github.com/sparrishmatt/surfs_up/blob/main/Resources/june_temps.png" height="300">

As expected, June weather in Hawaii looks very temperate. An average temperature of 75 degrees as well as a low of 64 which certainly isn't keeping people away from the outdoors and the surf shop. The max temperature is also only 85, which is just fine for the goals of the business. It should go without saying that with the relatively small range of temperatures that the standard deviation is also small at 3.26. From these descriptive statistics the most important detail that can be taken is that the June weather in Hawaii is very consistent, and hence the business should not have to worry about weather related issues. 

### December Results
<img src="https://github.com/sparrishmatt/surfs_up/blob/main/Resources/dec_temps.png" height="300">

These results are somewhat similar to the results from June. An average of 71 degrees is only 4 degrees cooler, with a max temperature of 83 being only 2 degrees cooler than the max from June. The minimum temperature is 56, which probably is not the best weather for surfing, but if we look at the standard deviation of 3.74, it seems that once again the weather will be pretty consistent. December in Hawaii may be a little cooler than June, but the outdoor weather is still perfectly habitable. 

## Summary
The statistics show that the weather in Hawaii during both June and December is very temperate. Not too hot ever and not too cold ever. Just right for opening a combination surfing/ice cream shop. As well as having good high and low temperatures, the most important thing for the shop is having a nice average temperature, and a good standard deviation which shows that the weather will be mostly consistent. 

### What other questions should be asked to make business decisions?
While we may have learned a lot about temperatures in June and December, there are more weather related insights that should be understood before opening a business. How is the temperature during the other winter months? Do some months have very high precipitation, and if so, do those line up with common vacation months? These are just a couple of the many important questions that can come up and be given to a data analyst that the analyst must be prepared for.

