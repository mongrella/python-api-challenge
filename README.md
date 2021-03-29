# python-api-challenge

WEATHERPY:

Your first requirement is to create a series of scatter plots to showcase the following relationships:

NOTE: All codes used for this portion were used to create a scatter plot of a weather variable (Y-Axis) in relation to latitude (X-Axis).

Temperature (F) vs. Latitude
- Max temperature peaks at around 20 degrees latitude and then steeply drops as latitude increases in the Northern Hemisphere. The relationship is non-linear and there is a slight positive relationship, then a negative relationship after 20 degrees latitude. The Southern hemisphere has higher max temps
Humidity (%) vs. Latitude
- There seems to be no relationship between the two variables, as humidity looks fairly consistent across. If anything, there is a slight increase as you get further north.
Cloudiness (%) vs. Latitude
- Cloudiness is fairly equally spread across Northern and Southern hemisphere. There seems to be no relationship between the two variables.
Wind Speed (mph) vs. Latitude
- Wind speed is fairly equally spread across latitude with a few outliners as latitude increases into the Northern hemisphere, so there seems to be no relationship between the two.

After each plot add a sentence or too explaining what the code is and analyzing.
Your second requirement is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
- There is a negative correlation between Max Temp and Latitude. As you get further into the N. Hemisphere, Max Temps decrease. This is very similar to what we saw in the scatterplot of both hemispheres. As you get to that 20 lat mark, max temps decrease as you go further north.
Southern Hemisphere - Temperature (F) vs. Latitude
- In the southern hemisphere, we see the opposite happening, as there is a moderate positive correlation. As you get closer to the equator, max temps increase. This is very similar to what we saw in the scatterplot of both hemispheres, where you see an increase in max temps as you get closer to 0 degress lat.
Northern Hemisphere - Humidity (%) vs. Latitude
- Here, the line is nearly flat, indicating there is essentially no correlation between humidity and latitude in the northern hemisphere. This is similar to what we saw in the scatterplot that included both hemispheres.
Southern Hemisphere - Humidity (%) vs. Latitude
- Unlike in the Northern Hemisphere, there is a very, very weak negative correlation between humidity and latitude as you get closer to the equator in the southern hemisphere. Humidity decreases slightly as you get to the equator.
Northern Hemisphere - Cloudiness (%) vs. Latitude
- Once again, we have a very weak positive correlation, with our r value being very close to 0. There is no relationship between cloudiness and latitude in the northern hemisphere. This is similar to what we saw in the previous cloudiness scatterplot that included both hemispheres. Cloudiness increases slightly as you go further north.
Southern Hemisphere - Cloudiness (%) vs. Latitude
- Again, there is a very, very weak negative correlation (r is very close to 0) between cloudiness and latitude as you get closer to the equator in the southern hemisphere. Cloudiness decreases slightly as you get closer to the equator.
Northern Hemisphere - Wind Speed (mph) vs. Latitude
- We can see a weak positive correlation between wind speed and lat as you get further North from the equator. Wind speeds do increase, but very slightly. This is visually similar to what we saw when we looked at both hemispheres together, and you can still see those outliers further north
Southern Hemisphere - Wind Speed (mph) vs. Latitude
- We can see a weak negative correlation between wind speed and latitude in the southern hemisphere. Wind speeds do decrease, but very slightly as you get closer to the equator. This is a bit visually different from when we looked at both hemispheres, as the Southern side of that scatterplot looked to be more dense than here.

VACATION PY:
Create a heat map that displays the humidity for every city from the part I of the homework.
Narrow down the DataFrame to find your ideal weather condition. For example:
- A max temperature lower than 80 degrees but higher than 70.
- Wind speed less than 10 mph.
- Zero cloudiness.
- Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.