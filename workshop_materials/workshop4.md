# Workshop   
##  Historical map ontologies through Palestine Open Maps 
with Majd Al-Shihabi on [day 4](../day4.md)  

### Resources  
[Resources of Levantine mappers](https://majdal.cc/gis-resources/) 

Our mapathon document is [here](https://docs.google.com/document/d/12poogpx1TjYOpxR4hY6Gixd7KyiZLDjrW2vvmokktcg/edit#)

## Independant tutorial: using the open data from Palestine Open Maps

Now that you have used the iD editor to extract data out of the maps, let's try a more advanced editor, and make a simple map from the data. 

We will use [JOSM](https://josm.openstreetmap.de/), for two reasons: 
1) It has a lot of features for advanced users 
2) It allows you to download the data out of the map, and re-open it in other tools



**STEP 0:** 

Start by downloading [JOSM](https://josm.openstreetmap.de/) and [QGIS](https://qgis.org/en/site/forusers/download.html) 

Get a physical mouse. It *really* helps. 
 
**STEP 1:** Add PalOpenMaps map tiles and data source

Open JOSM, and in the main menu, click Imagery > Imagery preferences 

Click on + TMS button to add a new tile map service


URL: `https://palopenmaps.org/tiles/pal20k-1940s/{z}/{x}/{y}.jpg`

Name: Palestine Open Maps 20k


IN THE SAME PREFERENCES DIALOGUE BOX, go to the "connection settings for the OSM server"

In the OSM server url field, use: `http://data.palopenmaps.org/api`

Press OK 

**STEP 2**: Download the data

In the top ribbon bar, click on the green down arrow to download data. 

Draw a bounding box around Haifa in Palestine to download PalOpenMaps data for that region. 

The data is now downloaded on your laptop, and you can see it in the layers panel on the right!

From the Imagery menu item, select Palestine Open Maps 20k to see the base map. Feel free to switch to satellite imagery from today to compare and contrast the data.


**STEP 3:** inspect some data

Click around the features on the map, play with them. See what tags they have. 

**STEP 4**: export the data

In the layers panel to the right, you will see a layer titled "Data layer 1". Right click > save as, and save the data to a specific location of your choosing. 

**STEP 5**: Open the data in QGIS

Start a new project in QGIS, and drag and drop the file you just exported into the project. You will get a dialogue box asking you which type of data would you like to import. Select all the types and click OK. 

Zoom in, pan around and see what data you have. It'll look a bit ugly, because everything has the same symbology. 

We'll make a map of the road network. Roads are always lines, so uncheck the multiline strings, multipolygons, and points layers in the left hand panel. 

**STEP 6:** Colour the data

Right click on the lines layer > Properties > Symbology > Categorized 

Value: highway

Then classify (at the bottom), then apply. Your map will show each type of road in a different colour, randomly selected. You can edit the colour and the style of the line by double clicking on the respective line in its own category and modifying its parameters. 



------

[day 0](../day0.md) | [day 1](../day1.md) | [day 2](../day2.md) | [day 3](../day3.md) | [day 4](../day4.md) | [day 5](../day5.md)  

return to [road map](../road_map.md)
