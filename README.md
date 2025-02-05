# python-api-challenge
Module 6 Challenge

In this challenge we compared the weather for different parts of the world based on their latitude by comparing temperature, cloudiness, humidity, and wind speed. 

The following scatter plots show the comparison for each category:

output_data/image-1.png

output_data/image-2.png

output_data/image-3.png

output_data/image-4.png

THe following scatter plots with linear regression lines further compare these categories breaking them down by northern and southern hemisphere:

Latitude vs. Temperature - Northern Hemisphere:
The r^2-value is: 0.7207453997160479

output_data/image-5.png

Latitude vs. Temperature - Southern Hemisphere:
The r^2-value is: 0.14362007831281523

output_data/image-7.png

We can tell from the two scatter plots and the correlation coefficient for both the northern and southern hemisphere that the further you are away from the equator, the colder it is. The temperature continues to drop the further the latitude gets away from 0.

Latitude vs. Humidity - Northern Hemisphere:
The r^2-value is: 0.10441843516737334

output_data/image-8.png

Latitude vs. Humidity - Southern Hemisphere:
The r^2-value is: 0.19473206423206343

output_data/image-9.png

From the comparison between latitude and humidity we can see that the further north you get, the more humid it gets. The southern hemisphere linear regression line shows humidity going up the closer you get to the equator, but the northern hemisphere linear regression shows the humidity going up the further you get from the equator. 

Latitude vs. Cloudiness - Northern Hemisphere:
The r^2-value is: 0.036451271693236253

output_data/image-10.png

Latitude vs. Cloudiness - Southern Hemisphere:
The r^2-value is: 0.1215720303790543

output_data/image-11.png

There appears to be a strong correlation between cloudiness and latitude in the southern hemisphere where it gets cloudier the closer you get to the equator. However, in the northern hemisphere there is less of a correlation and there seems to be more of a grouping of eaither very cloudy places and places that are not cloudy at all across all distances from the equatoer.

Latitude vs. Wind Speed - Northern Hemisphere:
The r^2-value is: 0.00024142951873596852

output_data/image-12.png

Latitude vs. Wind Speed - Southern Hemisphere:
The r^2-value is: 0.14060173824218092

output_data/image-13.png

Wind speed does not seem to have much correlation to latitude. We can see the linear regression line for the northern hemisphere is almost flat. For the southern hemispher, there seems to be a slight correlation but the cities still all seemed to be grouped together under 10.

For the second part of this project, I used the cities.csv that I created from the weather project and looked for the cities with the best weather and came up with a list of hotels available in these cities. The map below shows each city with weather I'd be interested in and if you hover over the city, you can see if there is a hotel available in that city. The map is viewable in the jupiter notebook, Vacation.ipynb. 


