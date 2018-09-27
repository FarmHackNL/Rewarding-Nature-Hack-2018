# FarmHack

[FarmHack](https://www.farmhack.nl) mobiliseert coders, creatieven en domeinexperts op vraagstukken van de boer.

# Rewarding Nature Hackathon

The Rewarding Nature hackathon takes place during the CAPIGI conference. With a mix of  coders, developers, data scientists, agronomists and other experts we have 28 hours to develop relevant solutions for farmers to help them innovate on biodiversity issues. *More specifically we are deep diving the issue of herby grasslands.*

## Data
- [AgroDataCube](http://agrodatacube.wur.nl) provides RESTful APIs for a large number of Dutch open agri data such as Agrarisch Agricultural Parcels (2012 - 2017), daily weather (1950 - 2018) as well as a height map of The Netherlands (AHN). The following data (among many others, See the docs for the full endpoint list and supported (spatial) operations) is available for each parcel (in Dutch):
  - AHN2 statistische informatie: count, sum, mean, stddev, min, max.
  - NDVI tijdserie (gemiddelde NDVI waarde per perceel, ongeveer 50 waarden per jaar), 2013 – 2017.
  - Bodemtypes 1:50.000, bepaald uit intersect van perceel met de Bodemkaart 1:50.000 uit 2014.
  - Info over de 50 KNMI meteostations, incl. Locatie.
  - Administratieve grenzen van provincies, gemeente, postcodegebieden uit 2015.
  - Volledige lijst met gewascodes (van de gewasregistratie).
  - Volledige lijst met bodemtypes en bodemcodes (van de bodemkaart 1:50.000).
- [SentinelHub](https://sentinel-hub.com/) is a cloud based GIS platform for distribution, management and analysis of satellite data. It provides developer-friendly access to remote sensing data from Sentinel-1, Sentinel-2, Landsat, Modis and other satellites.  Apply for a trial account to get access to the data. You can interact with the Hub in a number of ways
  - [Web Mapping Service](http://www.sentinel-hub.com/apps/wms/wms-integration-guide)
  - Python through the [`sentinelhub` package](https://medium.com/sentinel-hub/upgrading-the-sentinelhub-python-package-2665f9c10df). Check out this [Jupyter notebook](https://medium.com/sentinel-hub/lets-have-a-look-first-32ff13afce99) for a quick introduction and [this Medium post](https://medium.com/sentinel-hub/sentinel-hub-cloud-detector-s2cloudless-a67d263d3025) that shows how to remove clouds by employing machine learning. 
  - [QGIS](https://medium.com/sentinel-hub/control-sentinel-hub-from-within-qgis-2a83eb7f13db)
- [satellietdataportaal.nl](https://satellietdataportaal.nl/): satellite data for The Netherlands (Sentinels, Landsat, RapidEye, Planet Dove, TripleSat)
- Information on several validated plots via RVO and a farmer collective
- Natuurmonumenten: vegetatiekaarten
- Satellietbeeld.nl: Hackathon partner NEO, specialist in geo information and earth observation, will prepare a selection of the images from satellietbeeld.nl for Noord Holland and Utrecht. 

-Follow Up Event

## Access to experts
During the hackathon RVO and NEO will host a strategic session with experts on the topic of herby grasslands. The aim is to identify improvements or indicators to monitor grasslands. During the hackathon there is continuous opportunity to interact with these experts.

We want to direct your special attention to Ruth Howinson, who will present her study: [“Quantifying landscape-level land-use intensity patterns through radar-based remote sensing”.](https://drive.google.com/file/d/1evfuyS0lLzuAEsGI1ZnugLm555w4yrt1/view). Afterwards she will be available for questions from the hackathon participants.

