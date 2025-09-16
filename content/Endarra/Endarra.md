players:
	[Aedric](Aedric.md)
	[Ken](Ken.md)
	[Lobis](Lobis.md)
	[Theric](Theric.md)
	[Mustel](Mustel.md)

Map of Endarra:
```leaflet  
id: Endarra ### Must be unique with no spaces  
image: Endarra.jpg ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [2533, 2533]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 500px ### Size of the leaflet embed in px on your screen  
width: 100% ### Size of the leaflet embed in your note  
lat: 1266.5px ### To center the map, make this half of the map height.  
long: 1266.5px ### To center the map, make this half of the map width.  
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: true  
darkmode: false ### markermarker: default,642,706,Session 1,,,

```