# Data Visualization Project

## Data

The data for this project is from  [Kaggle:PM2.5 Global Air Pollution 2010-2017 (Mean Annual Exposure for 240 Countries)](https://www.kaggle.com/kweinmeister/pm25-global-air-pollution-20102017) via [Gist: PM2.5 Global Air Pollution Dataset (From 2010-2017)](https://gist.github.com/rioto9858/169d0de7a0e01e996ece1be53b1b79b9)

## Project Description

Based on the dataset above a visualization is developed to show the PM2.5 value worldwide from 2010-2017 intuitively.

[Introduction video of this project on YouTube](https://www.youtube.com/watch?v=gR1HWzyMlqA)

[Run this visualization](https://vizhub.com/rioto9858/bbc505c2d4cb467592bf28d9c9a1e668?mode=full)

[![FinalProject](https://user-images.githubusercontent.com/49369552/97757338-e73e3480-1ad2-11eb-8ab8-97d8941c09b7.png)](https://vizhub.com/rioto9858/bbc505c2d4cb467592bf28d9c9a1e668?mode=full)

## Ideas for Interaction

The visualization would be divided into three parts:(1) World choropleth map (2) Line chart of all countries (3) An option panel to let the user choose year and show the selected country data.

The world choropleth map:
* Zoom in/Out and drag to show the detail of the world map.
* Click on a specific country to select the country (the selected country on the map would be come red) and get a selected view.
* Hover on a specific country will show the PM2.5 value of that country in that year

The line chart of all countries:
* Show all the data on this chart.
* The year line (purple) would change with the selected year.
* If a country is selected on the choropleth map, the related line on the line chart would stand out and becomes red.

The option panel:
* The slider can select the year of data shown on the choropleth map and the year line on the line chart.
* The slider would be disabled when the a country is selected.
* There is a small line chart to show the data of the selected country.
* The country label will change by the mouse move.
* If a country is selected, the point of the data shown on the small line chart would become red and the detail of this point would be shown when the mouse is hover on them.


## Questions & Tasks

The following tasks and questions drive the visualization and interaction decisions for this project:

 * Is the PM2.5 air pollution value reduced these years?
 * What is the distribution of the PM2.5 air pollution in the world? 
 * Does the PM2.5 distribution change from 2010 to 2017?

## Sketches

There are three sketches in this project.
* The first one is to show PM2.5 pollution value in each year in each country. The user can choose a specific year to compare all the countries' PM2.5 value. This visualization would answer if the PM2.5 air pollution value reduces these year.
* The second one is to show PM2.5 value on the map with different luminance to show the value. It can change by year and shows the trend and distribution of the PM2.5 value more clearly and intuitively. This visualization would clearly show the distribution of PM2.5 each year and tell the user the changes.
* The third one is to show each year's value in a specific country. The user can choose a specific country to see the line chart of this country and judge if the country have made effective efforts to reduce PM2.5 value.
![Page1](https://user-images.githubusercontent.com/49369552/94345692-caa36e00-fff5-11ea-8726-27dab6693e54.jpg)
![Page2](https://user-images.githubusercontent.com/49369552/94345964-6e414e00-fff7-11ea-8fc9-2d728157a3b5.jpg)

## Prototypes

Six visualizations of this data are created in the develop process. 

After processing and melting the data, three visualization of this data is realized to show the line chart of PM2.5 trend. One of them is to realize a Choropleth Map to show the PM2.5 value worldwide. The other two is to combine all the things together and realize the interactions.

In the first visualization, the countries are distinguished by color and all the countries are shown in one chart. We can clearly see which country have which value in each year and compare them.

[![Viz1](https://user-images.githubusercontent.com/49369552/94346090-5c13df80-fff8-11ea-9190-8db518ded736.png)](https://vizhub.com/rioto9858/b2a7232644da4eb18c2fb6ed690ef5b9)

In the second visualization, a specifc country is chosen to show the PM2.5 air pollution value alone.

[![Vizspecificcountry](https://user-images.githubusercontent.com/49369552/94346277-7e5a2d00-fff9-11ea-9af3-62bef204e1b3.png)](https://vizhub.com/rioto9858/2d180c90d21148f9a241ffa110670845)

In the third visualization, a menu is created to let the user choose the country they want to check.

[![VizMenu](https://user-images.githubusercontent.com/49369552/95296371-ae4dcf80-0846-11eb-91f7-dabfee2f21f2.png)](https://vizhub.com/rioto9858/ecaaddfb735345189bd28722a3167731)

In the fourth visualization, a Choropleth Map of the world is created to show the PM2.5 value in a specific year and the distribution around the world.

[![VizGlobal](https://user-images.githubusercontent.com/49369552/95713455-94d8c900-0c34-11eb-9010-f0df4fce0599.png)](https://vizhub.com/rioto9858/8b93000aebda4b828985a428d19edade)

In the fifth visualization, the Choropleth Map is combined with the line chart in Multiple views. And the user can highlight a specific country to see the PM2.5 value of that country.

[![combine](https://user-images.githubusercontent.com/49369552/97065319-967e8700-157a-11eb-8e97-760957284542.png)](https://vizhub.com/rioto9858/a7f67ce64d59425dbe8c69dae9c2e5d9)

In the final visualization, all the parts are combined together and all the interaction is realized to let the user know the PM2.5 trend from 2010-2017 worldwide.

[![FinalProject](https://user-images.githubusercontent.com/49369552/97757338-e73e3480-1ad2-11eb-8ab8-97d8941c09b7.png)](https://vizhub.com/rioto9858/bbc505c2d4cb467592bf28d9c9a1e668)

## Schedule of Deliverables
      
**[DONE]**~~* Task 1 - Learn how to draw a world map: Try to draw a world map using d3 and React.  (estimate deliver date: 2020-10-14)~~

**[DONE]**~~* Task 2 - Load the data into the World map: Load the data into the world map to draw the distribution.  (estimate deliver date: 2020-10-18)~~  
**[DONE]**~~* Task 3 - Make the world map change by year: Make a menu to select a year which would cause the map to show data from that year.  (estimate deliver date: 2020-10-21)~~
**[DONE]**~~* Task 4 - Finish the Line Chart: Complete the line chart to let the user drag the cursor and select year.  (estimate deliver date: 2020-10-25)~~  
**[DONE]**~~* Task 5 - Connect the world map and the line chart : Try to connect the world map and the line chart.  (estimate deliver date: 2020-10-28)~~  
**[DONE]**~~* Task 6 - Hightlignt the country: Realize the function of highlighting the country in the world map and line chart in the same time. (estimate deliver date: 2020-11-2)~~   
**[DONE]**~~* Task 7 - Drag to control the map: Realize the function of dragging the cursor in the line chart to show the data from that year in the world map.  (estimate deliver date: 2020-11-7)~~

**[DONE]**~~* Task 8 - Complete a small line chart to show the specific country view.(estimate deliver date: 2020-11-7)~~  
**[DONE]**~~* Task 9 - Complete the project: Complete the project and check the function (debugging and checking).  (estimate deliver date: 2020-11-11)~~  

## Future Work 
* Function: Zooming in the Map filters the data on the Line Chart
