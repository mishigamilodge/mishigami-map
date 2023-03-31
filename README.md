# Mishigami Lodge Map

This is a QGIS project for the official area and chapter map for Mishigami Lodge, Order of the Arrow, BSA.

## Usage

To open/edit this project, download the entire project to your local computer, then open the **.qgs** file using QGIS, which can be obtained from https://www.qgis.org/

If the window looks blank after opening it, pick "Zoom Full" from the "View" menu to re-center the map.

The printable version of the map is under Project > Layouts > Basic Chapter Map.

Layer data from this map is exported to GeoJSON format for use by the interactive version of the map found at https://mishigami.org/chapters/ , with the source data placed at https://github.com/mishigamilodge/mishigami-wp-customizations/tree/staging/map-resources/layers

To export a layer to GeoJSON for the online map:

1. Have a copy of the **michigami-wp-customizations** project from Github already checked out
2. Right-click on the layer in the layer list and choose Export > Save Features As...
3. Set the Format to GeoJSON
4. Click the **...** button to the right of the filename, and go choose the existing .geojson file you are replacing.
5. Uncheck the box for "Add saved file to map" at the bottom.
6. Click OK.
7. Confirm permission to overwrite the existing file.
8. Commit your changes.

If you have any questions please contact David Miller.

## Licensing

Unless otherwise noted, all data in this project is Copyright (C) 2021-2023 Mishigami Lodge, All Rights Reserved.

* The Mishigami Blue Mastodon logo is a trademark of Mishigami Lodge, Order of the Arrow, BSA.
* The Order of the Arrow Trademark image (the red arrowhead) is a trademark of the Order of the Arrow, BSA. Usage of this logo is restricted to the purposes outlined in the Order of the Arrow Branding Guide found at https://oa-bsa.org/resources/branding .
* The GIS Data for the following layers has separate ownership:
  * MCC Districts is ©Michigan Crossroads Council, BSA
  * MI LP School Districts and MI LP Counties are both ©State of Michigan and the original source data can be found at https://gis-mdot.opendata.arcgis.com/search?tags=boundaries
