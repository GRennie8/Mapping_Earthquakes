# Mapping Earthquakes
Creating interactive maps using `Leaflet.js` library, `Javascript`, and `HTML` to retrieve earthquake information from a `GeoJSON` file and plot the results in a visual format.

# Overview

The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. We used the USGS website (https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) to retrieve the geographical coordinates and magnitudes of earthquakes for the last seven days. The data is then added to a map. Since the information is linked to a real-time source, the map will update whenever the user accesses it. Scripts are built using  `JavaScript` and `D3.js` library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. We then used `Leaflet` library to plot the data on a `Mapbox` style map through an API request and made it interactive by adding visualization for different map styles, creating layers to display Tectonic plates, Earthquake magnitude and location information. 

# Results

### Map in Street view showing all earthquakes and tectonic plates

![Screen Shot 2022-08-01 at 5 19 17 PM](https://user-images.githubusercontent.com/104115586/182949396-b2555a65-e385-45a4-b99f-b13f64c432e5.png)

### Map with added 'Major Earthquakes' filter

![Screen Shot 2022-08-04 at 2 49 22 PM](https://user-images.githubusercontent.com/104115586/182949923-90766813-7c7b-4bf5-949e-2c53a9c74d02.png)

### Added third tile layer 'Dark'

![Screen Shot 2022-08-01 at 5 54 00 PM](https://user-images.githubusercontent.com/104115586/182950202-0dd39f6f-879a-40ac-8825-5da4f344a6cc.png)
