<br>

helminthiases.github.io

<br>

### Notes

These statements/commands are for the steps page

```shell

# github.com/helminthiases/infections
python src/main.py

# github.com/helminthiases/spatial
# depends on infections
source(file = 'R/main.R')

# github.com/helminthiases/modelling
# depends on spatial
source(file = 'R/main.R')

# github.com/helminthiases/preliminary
# depends on infections & spatial
python src/main.py

# github.com/helminthiases/association
# depends on preliminary
source(file = 'R/main.R')

```

<br>
<br>

### References

Expanded Special Project for the Elimination of Neglected Tropical Diseases
* [ESPEN](https://espen.afro.who.int/)
* [ESPEN Cartography Database](https://espen.afro.who.int/tools-resources/cartography-database)
* [ESPEN API](https://admin.espen.afro.who.int/docs/api)
* [ESPEN API Documentation](https://espen.stoplight.io)

Elevation
* [Open Topology & SRTM](https://www.opentopodata.org/datasets/srtm/)
* [SRTM](https://lpdaac.usgs.gov/products/srtmgl1v003/),
* [USGS Elevation](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-shuttle-radar-topography-mission-srtm-1?qt-science_center_objects=0#qt-science_center_objects)

Administrative Boundaries
* [Global Administrative Areas (GADM)](https://gadm.org)
  * The co&ouml;rdinate reference system details of a GADM map are visible at the bottom
    of [a country page](https://gadm.org/download_country.html), after selecting a country.  It is ``EPSG:4326``.
  * [Global Colaboration Engine](http://globe.umbc.edu)
  * [GADM & GLOBE](http://globe.umbc.edu/documentation-overview/global-administrative-areas-gadm/)
  * [Variable Explorer](http://globe.umbc.edu/app/#/analysis/global-variables)
  
Soil
* [iSDA Soil](https://www.isda-africa.com/isdasoil/)
  * [iSDA Soil Launch](https://envirometrix.nl/isdasoil-open-soil-data-for-africa/)
  
Generic
* [DIVA GIS Spatial Data](https://www.diva-gis.org/Data)
* [National Oceanic & Atmospheric Administration (NOAA)](https://www.ncdc.noaa.gov/cdo-web/datasets)
* [WorldClim](https://www.worldclim.org/data/index.html)
* [Map projections](https://www.usgs.gov/publications/map-projections)

<br>
<br>
<br>
<br>

<br>
<br>
<br>
<br>
