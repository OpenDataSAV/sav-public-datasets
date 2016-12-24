![opendatasav](http://cvlassets.s3.amazonaws.com/23719460.png)
# Open Data SAV
### Savannah, Ga.'s official local brigade of Code for America
[blog](http://opendatasav.github.io) -- meetup group -- [twitter](http://twitter.com/opendatasav) -- [slack channel](http://techsav.slack.com) (#opendatasav)

###### sponsored in part by [techSav](http://techsav.co)


## Initial Assessment: The state of openness of public data in the Savannah MSA.
Prior to seeking public input on the data needs of Savannah-Chatham County residents, which we will plan during our first meetup, it may be helpful for us to compile what Savannah public data already exists and meets standards of accessibility and availability.

This document is a work-in-progress compilation of data from various agencies. To add a new repository or dataset, simply fork this repository and edit your forked copy's `readme.md` text to include a title, brief description and URL to data source and/or API.


Please note that this list is meant as a starting point to identify what data is *publicly available online* already, regardless of the format or accessibility. This includes PDFs, HTML tables, JSON, XML and, preferrably, CSV filetypes. This does not include any data  for which a special request is required or payment for data access is charged.



-

### Existing Datasets/Repositories in Savannah MSA
#### Crime and Safety
##### Weekly and annual reports by crime type, neighborhood and precincts available as PDFs [here](http://scmpd.org/annual-crime-report/)

+ Using [Tabula](http://tabula.technology/), I have scraped the 2015 Annual Part 1 Crime data as a CSV then added to a Google Sheet [here](https://docs.google.com/spreadsheets/d/1ik8Jm6rRQCScTMMIs9m3heag6GRUsQ0hD9oE086IPS0/edit?usp=sharing). 

+ In addition, I was able to find the corresponding geospatial polygon KML  files for each SCMPD-defined neighborhood, along with precinct-level polygons,  from SAGISServices  [here](http://sagisservices.thempc.org/saint/rest/services/OpenData/SCMPD/MapServer)

+ Using CARTO.com currently to wrangle messy KML data and pair up neighborhood polygons with data from all 120 or so neighborhoods.

+ This method is replicable for all crime data from SCMPD if they cannot provide data as CSV or JSON.


### Property Transfers

TODO


### Economy and Development

SEDA has a rich repository of open data available for download [here](http://www.seda.org/Data-Sets).

### Population and Demographics

TODO
### Environment and Climate Change

+ [Savannah Coastal Digital Elevation Model](https://catalog.data.gov/dataset/savannah-georgia-coastal-digital-elevation-model) - Data from NOAA and indexed on [data.gov](http://data.gov) -- High-level elevation models available. Report on sea-level rise [here](http://www.ngdc.noaa.gov/dem/squareCellGrid/getReport/303)


### Utilities, 

### City Government Spending, Salaries and Budgets
--to do--

More to come after Turkey Day.

### Geospatial Boundaries, Precincts, Neighborhoods, etc.

All geospatial data gathered regarding Greater Savannah boundaries and census tracts can be found in `.../Data/Geospatial/` 

Whenever possible, we'll post the geographic data in all three most common formats: SHP (Shapefile), KML and GeoJSON.


### State-Level Open Data Portals (Ga.)

+ Open Georgia: http://www.open.georgia.gov/

-


## Broader Issues 
--

