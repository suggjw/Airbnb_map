## Bivariate Map Example of AirBnBs in Buncombe County, NC

This map was developed as an example of bivariate symbolization using point and area level data in the web mapping environment. It depicts AirBnBs in Buncombe County, NC, overlaid with the City of Asheville Zoning Districts. AirBnBs and short term rentals represent roughly 5% of the City of Asheville's housing stock, leading the city to ban the use of short term rentals in residentially zoned districts. Asheville, NC is ranked as one of the leaders in per capita number of short term rental properties. Choropleth symbolization and the chroma.js library are used to visualize the number of AirBnBs per zoning district. Placemarker visualization of each short term rental location is depicted using the Font Awesome icon library and chroma.js library for categorical differences in the rental type. The map shows students how to apply style classes based on these data differences located in the GeoJSON properties. A custom Leaflet control is used to create a legend showing the choropleth sequential color palette and categorical AirBnB types.

## Packages, Stylesheets and Data 
- **Leaflet.js** (for map creation and customization)
- **jQuery** (for handling DOM manipulation and event handling)
- **Leaflet.css, and Google Fonts** (stylesheets for the design of the user interface)
- **FontAwesome** (for custom icons)
- **Chroma.js** (for color conversions and color scales)

**Data Provided by:** 
Two GeoJSON files were acquired as shapefiles and then converted for (1) Buncombe county Airbnbs, which are from [Inside Airbnb](https://insideairbnb.com), and (2) Buncombe county Zoning Districts from City of Asheville [Open Data Portal](https://data-avl.opendata.arcgis.com/).
