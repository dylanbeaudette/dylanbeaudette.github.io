---
output:
  html_vignette:
    mathjax: null
    jquery: null
    smart: no
---

USDA-NRCS / NCSS Soil Data Sources
==================================
2016-11-02
<br>
D.E. Beaudette


## USDA-NRCS "Official" Data Sources

[Digital Soil Survey Databases](http://www.nrcs.usda.gov/wps/portal/nrcs/main/soils/survey/geo/):

  * SSURGO (1:24,000 scale) detailed soil survey
  * STATSGO (1:250,000 scale) generalized soil survey
  * MLRA


### Web Soil Survey (WSS)

This is the official source of the soil survey data, interpretations, and SSURGO databases.

[WSS](http://websoilsurvey.sc.egov.usda.gov/App/HomePage.htm)



### Soil Data Access (SDA)

This is a web-service that supports spatial and tabular queries (SSURGO database), written in [T-SQL](https://technet.microsoft.com/en-us/library/bb264565(v=sql.90).aspx).

[SDA](http://sdmdataaccess.nrcs.usda.gov/)


### Official Series Descriptions (OSD)

These pages provide search tools for the OSD pages and associated Soil Classification (SC) database.

  * [OSD Search](https://soilseries.sc.egov.usda.gov/osdname.aspx)
  * [Multiple OSD Search](https://soilseries.sc.egov.usda.gov/osdlist.aspx)
  * [OSD Search via Soil Classification (SC) Database](https://soilseries.sc.egov.usda.gov/osdquery.aspx)


### KSSL Databases

These pages provide search and download facilities for soil characterization data.

  * [Basic Query / Home Page](http://ncsslabdatamart.sc.egov.usda.gov/)
  * [Advanced Query](http://ncsslabdatamart.sc.egov.usda.gov/advquery.aspx)


### SCAN / SNOTEL

Above and below ground sensor data. The [interactive map](http://www.wcc.nrcs.usda.gov/webmap/index.html#elements=&networks=SCAN&states=!&counties=!&hucs=&minElevation=&maxElevation=&elementSelectType=all&activeOnly=true&hucLabels=false&stationLabels=&overlays=&hucOverlays=&mode=stations&openSections=dataElement,parameter,date,elements,location,networks&controlsOpen=true&popup=&base=esriNgwm&lat=45.06&lon=-101.95&zoom=4&dataElement=PREC&parameter=PCTAVG&frequency=DAILY&duration=null&customDuration=&dayPart=E&year=2016&month=6&day=22&monthPart=E) is the simplest way to search for data.

   * [SCAN](http://www.wcc.nrcs.usda.gov/scan/)
   * [SNOTEL](http://www.wcc.nrcs.usda.gov/snow/)
   

### Block Diagrams

This is a collection of block diagrams from historic soil survey documents that have been scanned and indexed.

[Historic Block Diagram Archive](http://www.nrcs.usda.gov/wps/portal/nrcs/detail/soils/survey/geo/?cid=nrcs142p2_054317)
   

### NASIS

[Homepage](http://www.nrcs.usda.gov/wps/portal/nrcs/detail/soils/survey/geo/?cid=nrcs142p2_053552)




## SoilWeb: UCD/NRCS Collaboration

SoilWeb is an interface to the SSURGO, KSSL, SC, Block Diagram, and OSD databases, updated annually.

[SoilWeb Home](https://casoilresource.lawr.ucdavis.edu/soilweb-apps)

### SoilWeb Google Maps

Google Maps interface to SoilWeb, functions on desktop and mobile platforms.

[SoilWeb Gmaps](http://casoilresource.lawr.ucdavis.edu/gmap/)

[Text-Only Interface](http://casoilresource.lawr.ucdavis.edu/soil_web/ssurgo.php)



### SoilWeb Google Earth

Streaming KMZ layer for Google Earth: STATSGO, SSURGO, KSSL, OSD data with links.

[KMZ Link](http://casoilresource.lawr.ucdavis.edu/soil_web/kml/SoilWeb.kmz)


### SoilWeb for Smartphones
These are "native" apps for smartphones and tablets that will function in areas with 1x or 3G data coverage.

  * [iOS](http://itunes.apple.com/us/app/soilweb-for-the-iphone/id354911787?mt=8)
  * [Android](https://play.google.com/store/apps/details?id=casoilresource.apps.soilweb&hl=en)


### Series Extent Explorer (SEE)
Soil series extent mapping and comparison tool, with links to SDE and SoilWeb Gmaps.

[SEE](http://casoilresource.lawr.ucdavis.edu/see/)


### Series Data Explorer (SDE)
This website is accessible via SEE (see above), or can be used by appending a soil series name to the end of the URL. SDE integrates KSSL, SSURGO, block diagrams, OSD, and SC databases.

Examples:

  * [Amador Series](http://casoilresource.lawr.ucdavis.edu/sde/?series=amador)
  * [San Joaquin Series](https://casoilresource.lawr.ucdavis.edu/sde/?series=san%20joaquin)
  * [Pierre Series](https://casoilresource.lawr.ucdavis.edu/sde/?series=pierre)
  * [Cecil Series](https://casoilresource.lawr.ucdavis.edu/sde/?series=cecil)


### SeriesTree
This tool is accessible via SDE (see above), or can be used by appending a soil series name to the end of the URL. SeriesTree builds a hierarchy of all soil series that share a common subgroup level taxa with the series named on the URL. The hierarchy is build from family level criteria.


  * [Amador Series](http://soilmap2-1.lawr.ucdavis.edu/seriesTree/index.php?series=amador)
  * [San Joaquin Series](http://soilmap2-1.lawr.ucdavis.edu/seriesTree/index.php?series=san%20joaquin)
  * [Pierre Series](http://soilmap2-1.lawr.ucdavis.edu/seriesTree/index.php?series=pierre)
  * [Cecil Series](http://soilmap2-1.lawr.ucdavis.edu/seriesTree/index.php?series=cecil)


### OSD Fulltext Search
Search the OSD documents using pattern matching within the entire OSD, or limited to sections of the OSD. See each page below for examples on how to create search patterns.

  * [search entire OSD](http://soilmap2-1.lawr.ucdavis.edu/dylan/soilweb/osd-fulltext/)
  * [search by section](http://soilmap2-1.lawr.ucdavis.edu/dylan/soilweb/osd-fulltext/sections.php)


### CA Soil Properties
Soil properties gridded at 1km resolution, based on SSURGO with holes filled using STATSGO.

[CA Soil Properties](http://casoilresource.lawr.ucdavis.edu/ca-soil-properties/)



## R Interfaces: `soilDB` Package

[Project Homepage](http://ncss-tech.github.io/AQP/)

 1. [`fetchKSSL()`](http://ncss-tech.github.io/AQP/soilDB/KSSL-demo.html): Lab data, [processing details](https://github.com/dylanbeaudette/process-kssl-snapshot).
 2. [`fetchOSD()`](http://ncss-tech.github.io/AQP/sharpshootR/OSD-dendrogram.html): Select data elements parsed from OSD text files.
 3. [`fetchNASIS()`](http://ncss-tech.github.io/AQP/soilDB/fetchNASIS-mini-tutorial.html): Simple interface to NASIS local database.
 4. [`fetchSCAN()`](http://ncss-tech.github.io/AQP/soilDB/fetchSCAN-demo.html): Unified interface to SCAN/SNOTEL data.
 5. [`seriesExtent()`](http://ncss-tech.github.io/AQP/soilDB/series-extent.html): Get series extent data from SoilWeb/SEE.
 6. [`SDA_query()`](http://ncss-tech.github.io/AQP/soilDB/SDA-tutorial.html): Wrapper to SDA web-service.


## PSU Soil Survey Applications

### MLRA Explorer

[MLRA Explorer](http://apps.cei.psu.edu/mlra/)


### Isee

[Isee](http://isee.purdue.edu/)





