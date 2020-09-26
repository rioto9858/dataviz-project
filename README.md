# Data Visualization Project

## Data

The data I propose to visualize for my project is from the [Kaggle:PM2.5 Global Air Pollution 2010-2017 (Mean Annual Exposure for 240 Countries)](https://www.kaggle.com/kweinmeister/pm25-global-air-pollution-20102017) via  [Gist: PM2.5 Global Air Pollution Dataset (From 2010-2017)](https://gist.github.com/rioto9858/169d0de7a0e01e996ece1be53b1b79b9)

## Prototypes

I've created two concept visualization of this data. After processing and melting the data, two visualization of this data is realized to show the line chart of PM2.5 trend in each country.
In the first visualization, the countries are distinguished by color and all the countries are shown in one chart. We can clearly see which country have which value in each year and compare them.

[![Viz1](https://user-images.githubusercontent.com/49369552/94346090-5c13df80-fff8-11ea-9190-8db518ded736.png)](https://vizhub.com/rioto9858/b2a7232644da4eb18c2fb6ed690ef5b9)

In the second visualization, I choose a specifc country to show the PM2.5 air pollution value alone.(eg. China) I am working to figure out how to let user choose the country by themselves.

[![Vizspecificcountry](https://user-images.githubusercontent.com/49369552/94346277-7e5a2d00-fff9-11ea-9af3-62bef204e1b3.png)](https://vizhub.com/rioto9858/2d180c90d21148f9a241ffa110670845)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Is the PM2.5 air pollution value reduced these years?
 * What is the distribution of the PM2.5 air pollution in the world? 
 * Does the PM2.5 distribution change from 2010 to 2017?
 * Which country has the most effective way to control the pollution?

## Sketches

There are three sketches in this project.
* The first one is to show PM2.5 pollution value in each year in each country. The user can choose a specific year to compare all the countries' PM2.5 value. This visualization would answer if the PM2.5 air pollution value reduces these year.
* The second one is to show PM2.5 value on the map with different luminance to show the value. It can change by year and shows the trend and distribution of the PM2.5 value more clearly and intuitively. This visualization would clearly show the distribution of PM2.5 each year and tell the user the changes.
* The third one is to show each year's value in a specific country. The user can choose a specific country to see the line chart of this country and judge if the country have made effective efforts to reduce PM2.5 value.
![Page1](https://user-images.githubusercontent.com/49369552/94345692-caa36e00-fff5-11ea-8726-27dab6693e54.jpg)
![Page2](https://user-images.githubusercontent.com/49369552/94345964-6e414e00-fff7-11ea-8fc9-2d728157a3b5.jpg)

## Open Questions

* I am not sure how to get the geographic shapes to build up a map from this data.
* I am not sure whether I can implement a map only based on the country name without the latitude and longitude.
* I do not clearly know how to implement interaction elements on html.
