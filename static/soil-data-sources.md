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

  * SSURGO
  * STATSGO
  * MLRA


### Web Soil Survey (WSS)

[WSS](http://websoilsurvey.sc.egov.usda.gov/App/HomePage.htm)



### Soil Data Access (SDA)

[SDA](http://sdmdataaccess.nrcs.usda.gov/)


### Official Series Descriptions (OSD)

  * [OSD Search](https://soilseries.sc.egov.usda.gov/osdname.aspx)
  * [Multiple OSD Search](https://soilseries.sc.egov.usda.gov/osdlist.aspx)
  * [OSD Search via Soil Classification (SC) Database](https://soilseries.sc.egov.usda.gov/osdquery.aspx)


### KSSL Databases

  * [Basic Query / Home Page](http://ncsslabdatamart.sc.egov.usda.gov/)
  * [Advanced Query](http://ncsslabdatamart.sc.egov.usda.gov/advquery.aspx)


### SCAN / SNOTEL

   * [SCAN](http://www.wcc.nrcs.usda.gov/scan/)
   * [SNOTEL](http://www.wcc.nrcs.usda.gov/snow/)
   

### Block Diagrams

[Historic Block Diagram Archive](http://www.nrcs.usda.gov/wps/portal/nrcs/detail/soils/survey/geo/?cid=nrcs142p2_054317)
   

### NASIS

[Homepage](http://www.nrcs.usda.gov/wps/portal/nrcs/detail/soils/survey/geo/?cid=nrcs142p2_053552)




## SoilWeb: UCD/NRCS Collaboration

[SoilWeb Home](https://casoilresource.lawr.ucdavis.edu/soilweb-apps)

### SoilWeb Google Maps

[SoilWeb Gmaps](http://casoilresource.lawr.ucdavis.edu/gmap/)

[Text-Only Interface](http://casoilresource.lawr.ucdavis.edu/soil_web/ssurgo.php)

### SoilWeb Google Earth

[KMZ Link](http://casoilresource.lawr.ucdavis.edu/soil_web/kml/SoilWeb.kmz)

### SoilWeb for Smartphones

  * [iOS](http://itunes.apple.com/us/app/soilweb-for-the-iphone/id354911787?mt=8)
  * [Android](https://play.google.com/store/apps/details?id=casoilresource.apps.soilweb&hl=en)


### Series Extent Explorer (SEE)

[SEE](http://casoilresource.lawr.ucdavis.edu/see/)


### Series Data Explorer (SDE)

  * [Amador Series](http://casoilresource.lawr.ucdavis.edu/sde/?series=amador)
  * [San Joaquin Series](https://casoilresource.lawr.ucdavis.edu/sde/?series=san%20joaquin)
  * [Pierre](https://casoilresource.lawr.ucdavis.edu/sde/?series=pierre)
  * [cecil](https://casoilresource.lawr.ucdavis.edu/sde/?series=cecil)


### OSD Fulltext Search

  * [search entire OSD](http://soilmap2-1.lawr.ucdavis.edu/dylan/soilweb/osd-fulltext/)
  * [search by section](http://soilmap2-1.lawr.ucdavis.edu/dylan/soilweb/osd-fulltext/sections.php)


### CA Soil Properties

[CA Soil Properties](http://casoilresource.lawr.ucdavis.edu/ca-soil-properties/)



## R Interfaces: `soilDB` Package

[Project Homepage](http://ncss-tech.github.io/AQP/)

 1. [`fetchKSSL()`](http://ncss-tech.github.io/AQP/soilDB/KSSL-demo.html): Lab data, [processing details](https://github.com/dylanbeaudette/process-kssl-snapshot).
 2. [`fetchOSD()`](http://ncss-tech.github.io/AQP/sharpshootR/OSD-dendrogram.html): Select data elements parsed from OSD text files.
 3. [`fetchNASIS()`](http://ncss-tech.github.io/AQP/soilDB/fetchNASIS-mini-tutorial.html): Simple interface to NASIS local database.
 4. [`fetchSCAN()`](http://ncss-tech.github.io/AQP/soilDB/fetchSCAN-demo.html): Unified interface to SCAN/SNOTEL data.
 5. [`seriesExtent()`](http://ncss-tech.github.io/AQP/soilDB/series-extent.html): Get series extent data from SoilWeb/SEE.
 6. [`SDA_query()`](http://ncss-tech.github.io/AQP/soilDB/SDA-tutorial.html): Wrapper to SDA web-service.


