# 🚀 (partial) log, issues and To dos
## 18 Dec 2022
## changes
- I have not made a swipe map. Instead, my map shows the informal settlement layer intersected with data from the land ownership dataset. 
- I added a local search based on settlement name
- increased transparency and added background sattelite view layer

## things to do
- change language in legend, footer and popups
- reorder legend items
- add timeslider and ata for several years
- find out what year the satellite map is from
- check for mobile usability
- data download button


## 09 dec 2022
### MAP 1- land ownership
Hosted on - https://sanjana-krish.github.io/land-in-mumbai/ <br>
Map shows qualitative colouring based on OWNERSHIP category <br>
Functionality- can change language with drop down and onChange (has issues that need to be fixed-- change legend language, adding tags and styling within the getElementById-- should be able to figure this out) <br><br>

Issues
- large file size, takes 5-10 seconds to load (maybe more?). I reduced the total size from ~650MB to ~55MB. It is still very large. I used the dissolve function with OWNERSHIP and HOLDER_NAME (because I think that data is important to have). I haven't done the conversion to TopoJSON on mapshaper. I need to think about how to reduce it...
- I want to add a location search option to the maps so that a user can type the location and zoom into the address they are interested in. I found two option. 
  - https://github.com/Esri/esri-leaflet-geocoder - This link shows one method using ARGGIS Developer. I tried making the account but wasnt able to  generate the API due to some account restriction. I haven't explored this properly though. 
  - https://docs.mapbox.com/help/tutorials/local-search-geocoding-api/ - mapbox also seems to have an option of a more localised search. I haven't tried this. I need to check it it can search the whole of Mumbai

### MAP 2- Slum 2016
Can be found in modules/settlement2016.html <br>
Data is in modules/module_data/slum_2016.geojson <br>
I fixed geometries and reduced the geojson size and retained important features. <br> 
I increased the transparency on the geojson layer to see the background when searching <br>
I need to replace the base layer with a satellite view for this map. <br>

### Combining the maps- next steps
I want to show both the layers together with map swipe/ leaflet side-by-side. <br>
I tried several different codes online, but most did not work. I have retained the most simple one I found. <br>
It can be found in modules/mapSwipe.html. It was taken from this link- https://docs.mapbox.com/mapbox-gl-js/example/mapbox-gl-compare/
<br>
To combine the two maps I have, I found two options online. 
- https://ovrdc.github.io/gis-tutorials/mapbox/swipe-map/ uses mapbox map swipe
- https://gis.stackexchange.com/questions/345096/leaflet-compare-two-side-by-side-geojson-layers uses leaflet to combine them
I haven't tried these two and I don't know how and to what extent the before and after map containers can be modified

My original idea was to have a swipe between three maps, but it seems too complicated and perhaps it isn't needed. 
I have not tried yet how to combine the two maps and don't know if it will work. 
