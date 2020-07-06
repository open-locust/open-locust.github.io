# Primary Datasets

### Soil Type

* [FAO Harmonized World Soil Database](http://www.fao.org/soils-portal/soil-survey/soil-maps-and-databases/harmonized-world-soil-database-v12/en/)

* [ISRIC updated 250m dataset](https://data.isric.org/geonetwork/srv/eng/catalog.search#/home)

* [LandPKS soil characteristics data](http://portal.landpotential.org/#/landpksmap)
Feed the Future has collected plot-level data on soil characteristics for several of our population-based household surveys using LandPKS, including in Kenya, Ghana, and Mali; these data have also been collected extensively in Ethiopia and worldwide. Contact: Jeff Herrick at USDA is the lead on LandPKS


### Soil Moisture

#### SERVIR Products
Here is a breakdown of what soil moisture products SERVIR is currently providing, where and what format they are in. There are two domains available for current model simulations, in East Africa and Southwest Asia (Data provided by FEWSNET), however, forecasted data are only available in East Africa. The data we are providing is volumetric soil moisture in the top 10 cm of the ground surface (i.e. percent of the soil that has water, so the max will usually be no greater that 50% (0.5)). The data is produced from the NOAH land surface model within  NASA’s Land Information System (LIS) framework that uses satellite based inputs (see references below). From the desert locusts experts that we have talked with, locust have 2 main requirements for successful breeding: that the volumetric soil moisture be in a specific range (~0.15 – 0.25) and that soil type be pretty sandy (we’ve found sand percentages between ~55-75% for locust observations).

We are sharing the data in two different ways:
TIFF file download. This is served through the URL:

* [SERVIR Locust Datasets](https://gis1.servirglobal.net/data/locusts)
* [Thredds Server Locusts Catalog](https://thredds.servirglobal.net/thredds/catalog/Locusts/catalog.html)
* [WMS/OpenDAP access](https://thredds.servirglobal.net/thredds/catalog/Locusts/catalog.html)

Or a quick preview of the latest data, this link displays the latest 15 day forecast (using the [THREDDS server](https://terria.servirglobal.net/#share=g-15e754f6fa9c54b05540a158c3511b37):

##### Data citations:

*Soil moisture modeled data provided by SERVIR and SPoRT, FEWSNET and GSFC using NASA Land Information System (Kumar et al., 2006; McNally et al., 2017, Case et al., 2016*

* Kumar, Sujay V., Christa D. Peters-Lidard, Yudong Tian, Paul R. Houser, James Geiger, S. Olden, L. Lighty et al. [Land information system: An interoperable framework for high resolution land surface modeling.](https://www.sciencedirect.com/science/article/abs/pii/S1364815205001283) Environmental modelling & software 21, no. 10 (2006): 1402-1415.

* McNally, Amy, Kristi Arsenault, Sujay Kumar, Shraddhanand Shukla, Pete Peterson, Shugong Wang, Chris Funk, Christa D. Peters-Lidard, and James P. Verdin. [A land data assimilation system for sub-Saharan Africa food and water security applications](https://www.nature.com/articles/sdata201712) Scientific data 4, no. 1 (2017): 1-19.

* Case, J., Mungai, J., Sakwa, V., Zavodsky, B.T., Srikishen, J., Limaye, A.S., Blankenship, C.B., 2016: [Transitioning Enhanced Land Surface Initialization and Model Verification Capabilities to the Kenya Meteorological Service.](https://ams.confex.com/ams/96Annual/webprogram/Manuscript/Paper287796/Case_etal_2016-AMSannual-LambSymp_talk2.4_extAbs_FINAL.pdf) American Meteorological Society Fall Meeting, New Orleans.

#### Soil Moisture Active Passive (SMAP)
SMAP data is [available here](https://nsidc.org/data/smap/smap-data.html)

10 KM FLDAS soil moisture (monthly latency) on GEE <https://developers.google.com/earth-engine/datasets/catalog/NASA_FLDAS_NOAH01_C_GL_M_V001>

#### Landuse/landcover:
* [Annual MODIS Land Cover (1km - 2018 latest)](https://lpdaac.usgs.gov/products/mcd12q1v006/)
* [Sentinel-2 (30m - 2016)](http://2016africalandcover20m.esrin.esa.int/)
* [USGS Croplands (30m - 2015)](https://croplands.org/app/map?lat=0&lng=0&zoom=2)
* [Kenya crop type map (30m - 2015)](http://opendata.rcmrd.org/datasets/kenya-crop-mask-2015)
* [Eastern Africa Land cover maps (1990 - 2015)](http://opendata.rcmrd.org/search?q=land%20cover)
* [Vegetation:MODIS, Landsat NDIV, EVI](https://search.earthdata.nasa.gov/search)
* [IRI Greenness](https://iridl.ldeo.columbia.edu/maproom/Food_Security/Locusts/Regional/greenness.html)

#### WindSpeed (and other met variables):
* [Windy (GFS, ECMWF)](https://www.windy.com)
* [HYSPLIT Model](https://locusts.arl.noaa.gov:8443/)
* [Global Data Assimilation System](https://www.ncdc.noaa.gov/data-access/model-data/model-datasets/global-data-assimilation-system-gdas)

#### Rainfall
* [IRI  daily, decadal, monthly](http://iridl.ldeo.columbia.edu/maproom/Food_Security/Locusts/index.html)

#### Locust location data
* [Locust Hub](https://locust-hub-hqfao.hub.arcgis.com/)

#### Data Aggregators
Plant Village <https://pennstate.maps.arcgis.com/apps/opsdashboard/index.html#/121dd23b5e264e25a685b57f40042899>

**Modeling frameworks:**
SERVIR West Africa
<https://chaponda.users.earthengine.app/view/locustrisk>

ICIPE

PlantVillage
