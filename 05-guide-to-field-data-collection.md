# Guide to Field Data Collection

In our previous chapters, we've outlined the basics of data collection, building your survey, and some best practices. This chapter contains our recommendations for gathering data once you're out in the field.

* [Identifying Parameters and Range](#parameters-and-range) - Define the scope of your data collection
* [Plotting Course](#plotting-course) - Optimize your field crew deployments
* [Using Basemaps](#basemaps) - Provide context and reference for your team
* [Exporting the Data](#exporting) - Get your data out in various formats
* [Integration with Other Platforms](#integration) - Load your data into other programs and services

### Identifying Parameters and Range <a id="parameters-and-range"></a>

As outlined in [Data Collection 101](https://fulcrumapp.gitbooks.io/fulcrum-guide-to-data-collection/content/02-data-collection-101.html#Survey-Design), your survey design will dictate the details and scope of what you will collect. It is important to conform to the standards set forth in your survey design to ensure consistency of the data collected by you and others on your team. Going outside the identified parameters and range can skew your data and potentially compromise the results of your final analysis.

### Plotting Course <a id="plotting-course"></a>

Before you depart for your data collection mission, it may seem obvious that you know 'where' you're going to do your work, but there is more to it than that. Having a plan before you start gathering data in the field is an essential first step. A few things you'll want to take into consideration are: how many hours in the day it will be possible to collect data, the spatial relationship between collection sites, and how long it takes to complete your survey at each location. Does it makes more sense to travel to the furthest location first - and work backwards? If you have multiple sites to visit, there will be an optimal route you can take rather than doing so in a random order.

Other logistics to include in your planning:
* Do you have any needed permission, codes, or keys for access to sites on private property?
* Will you need personal protection from the elements, pests, animals, etc?
* What is your plan in the case of an emergency or injury?
* (If traveling by vehicle) Is your vehicle properly maintained, capable, and with adequate fuel?

### Using Basemaps <a id="basemaps"></a>

A core component of Fulcrum as a field data collection tool is the included set of basemaps. Fulcrum mobile users are provided map reference information from Google when they are within a (Internet) connected environment. The Streets, Aerial/Satellite, Hybrid, and Terrain basemaps are available to choose from, as well as the ability to choose 'None'.

There are situations where you will want to collect data in a disconnected environment and you require map reference information to complete your task. Not only does Fulcrum have the functionality to collect data offline but it also allows you to use interactive offline maps. There are examples on the website for using both the [vector](http://www.fulcrumapp.com/guides/mapping-and-gis/offline-map-creation-tilemill/) and [raster](http://www.fulcrumapp.com/blog/working-with-geotiffs-for-offline-maps/) GIS data types in your offline map creation.

Another basemap layer type which is available to the mobile user is [Tile XYZ](http://www.fulcrumapp.com/help/adding-tilexyz-layers/). If you seek access to layers hosted in a Tile XYZ tiling scheme, they can be added as a reference layer within Fulcrum.

### Exporting the Data <a id="exporting"></a>

Not only does Fulcrum make it easy to import and collect data but it also has robust options for exporting your data. All Fulcrum plans support exporting data in these 9 [different formats](http://www.fulcrumapp.com/help/data-formats-for-export/): CSV, Microsoft Excel, KML (Google Earth), Esri Shapefile, GeoJSON, Esri File Geodatabase, SQLite, SpatiaLite, PostGIS. Along with these formats are various [export options](http://www.fulcrumapp.com/help/export-options/) to control exactly what you need to export, including: filtering by geographic area or the date the record was created or updated and whether to export multiple apps and/or projects’ data at once.

### Integration with Other Platforms <a id="integration"></a>

After you've built your survey, deployed it, and collected some data in the field - you will likely be ready to visualize, analyze, or process that data. One of the benefits of conducting field data collection with the Fulcrum platform is that your data is entered into a system that's capable of powerful integrations with other services and platforms. Here are a few examples of how you can leverage Fulcrum's extensibility:

* Data Shares
* Fulcrum API
* Data Events
* Zapier
