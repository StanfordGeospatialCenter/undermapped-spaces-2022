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



### STEP 0: 
**Set Up**  

1. Start by downloading [JOSM](https://josm.openstreetmap.de/) and [QGIS](https://qgis.org/en/site/forusers/download.html) 

2. Get a physical mouse if you can. It *really* helps. 
 
### STEP 1:  
**Add PalOpenMaps map tiles and data source**  

1. Open JOSM  
2. In the main menu, click Imagery > Imagery preferences   
3. Click on + TMS button to add a new tile map service  

<!-- is this information they should be pasting into fields? -->
URL: `https://palopenmaps.org/tiles/pal20k-1940s/{z}/{x}/{y}.jpg`  
Name: Palestine Open Maps 20k    

4. IN THE SAME PREFERENCES DIALOGUE BOX, go to the "connection settings for the OSM server"  
5. In the OSM server url field, enter: `http://data.palopenmaps.org/api`  
6. Click OK  

### STEP 2  
**Download the data**  

1. In the top ribbon bar, click on the green down arrow to download data.  
2. Draw a bounding box around Haifa in Palestine to download PalOpenMaps data for that region.   
3. The data is now downloaded on your laptop, and you can see it in the layers panel on the right!  
4. From the Imagery menu item, select Palestine Open Maps 20k to see the base map. Feel free to switch to satellite imagery from today to compare and contrast the data  

### STEP 3  
**Inspect some data**  

1. Click around the features on the map, play with them 
2. What tags do they have?

### STEP 4  
**Export the data**  

1. In the layers panel to the right, you will see a layer titled "Data layer 1" 
2. Right click > save as, and save the data to a specific location on your computer. Make a note of where you saved this file!  

### STEP 5  
**Open the data in QGIS**  
1. Open QGIS and start a new project
2. Drag and drop the file you just exported (see prior step) into the project.
3. You will get a dialogue box asking you which type of data would you like to import.  
4. Select all the types and click OK.
5. Zoom in, pan around and see what data you have. It'll look a bit ugly, because everything has the same symbology. 

<!-- this next step is a little confusing.... maybe adding some screen clippings to help illustrate? -->
We'll make a map of the road network. Roads are always lines, so uncheck the multiline strings, multipolygons, and points layers in the left hand panel. 

### STEP 6   
**Colour the data**  

1. Right click on the lines layer > Properties > Symbology > Categorized 

<!-- what about values? -->
Value: highway

Click classify (at the bottom), then click apply. Your map will show each type of road in a different colour, randomly selected. You can edit the colour and the style of the line by double clicking on the respective line in its own category and modifying its parameters. 



------

[day 0](../day0.md) | [day 1](../day1.md) | [day 2](../day2.md) | [day 3](../day3.md) | [day 4](../day4.md) | [day 5](../day5.md)  

return to [road map](../road_map.md)
