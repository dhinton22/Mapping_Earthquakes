# Mapping_Earthquakes

# Overview of Project

Basil and Sadhana like how I created my earthquake map with two different maps and the earthquake overlay. Now, Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map.

Deliverable 1: Add Tectonic Plate Data
Deliverable 2: Add Major Earthquake Data
Deliverable 3: Add an Additional Map
Deliverable 4: A written report on the Mapping Earthquakes analysis


# Tech-Overview
In this module, I used the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from a URL. Each earthquake is visually represented by a circle and color, where a higher magnitude has a larger diameter and is darker in color. In addition, each earthquake has a popup marker that, when clicked, shows the magnitude of the earthquake and the location of the earthquake.


# Add Tectonic Plate Data:

Using my knowledge of JavaScript, Leaflet.js, and geoJSON data, I add tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data.

![image](https://user-images.githubusercontent.com/103547108/180626327-eb1dad54-a5be-4b91-931a-cccfc80687e5.png)

      The tectonic plate data is added as a second layer group.
      The tectonic plate data is added to the overlay object.
      The d3.json() callback is working and does the following:
      The tectonic plate data is passed to the geoJSON() layer
      The geoJSON() layer adds color and width to the tectonic plate lines
      The tectonic layer group variable is added to the map
      The earthquake data and tectonic plate data displayed on the map when the page loads.
      
      
# Add Major Earthquake Data:

Using my knowledge of JavaScript, Leaflet.js, and geoJSON data, I added major earthquake data to the map using d3.json(), and a color and set the radius of the circle based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().

![image](https://user-images.githubusercontent.com/103547108/180626407-35ceea48-77fa-4b19-902b-366886f557e2.png)


      The major earthquake data is added as a third layer group.
      The major earthquake data is added to the overlay object.
      The d3.json() callback is working and does the following:
      Sets the color and diameter of each earthquake.
      The major earthquake data is passed to the geoJSON() layer.
      The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake
      The major earthquake layer group variable is added to the map
      All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off.
