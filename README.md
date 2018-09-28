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

## Access to experts
During the hackathon RVO and NEO will host a strategic session with experts on the topic of herby grasslands. The aim is to identify improvements or indicators to monitor grasslands. During the hackathon there is continuous opportunity to interact with these experts.

We want to direct your special attention to Ruth Howinson, who will present her study: [“Quantifying landscape-level land-use intensity patterns through radar-based remote sensing”.](https://drive.google.com/file/d/1evfuyS0lLzuAEsGI1ZnugLm555w4yrt1/view). Afterwards she will be available for questions from the hackathon participants.


# Rewarding Nature Follow Up Event
Access to datasets is provided via the link in the [FarmHack Rewarding Nature Forum](https://forum.farmhack.nl/t/data-rewarding-nature-follow-up-event/97). 

- RVO Data:
  - 4 years of ANLB data (incl. strips)
  - 4 years of crop parcel data (incl. biological parcels and grass parcels)
  - Farm locations and numbers of animals
  - Photo data
  
- Nectar Index Data: Dataset consists of nectar indexes of about 1500 locations in the Netherlands. Data is collected in road verges by enthusiast nature monitoring volunteers in 2017 en 2018, following a standard protocol. Dataset is owned by FLORON, it is donated for the purposes of this hackathon and subject to conditions stated in the Farmhack Code of Conduct. 

- WEnR-Landelijke Vegetatie Databank: A 'derivative' of the Landelijke Vegetatie Databank dataset containing 22,000 to 30,000 vegetation datapoint from the period 2008-2018. Doesn’t use the complete vegetation recordings (cover by species), but the amount of grasses and herbs per vegetation intake/datapoint.

  Variables such as: Bodemtype (bodemtype), Fysisch Geografische Regio (FGR), oppervlakte proefvlak (opp_proef), verhouding proefvlak  (verhouding), natuurdoeltype (gebruikersvorm,] can be used to make a selection, or to explore the need for regional differentiation).

  Gebruikersvorm 'Agricultural grassland (regular or ANLb)': this group contains both regular agricultural grassland and grasslands for which ANLb management packages have been closed. These two forms of management can make a big difference to herbal richness, but further data differentiation is therefore not possible. Make sure to check the explanation associated with the data. 

- Veluwemeerkust 2017 Data: This is a 'derivative' of the Landelijke Vegetatie Databank dataset. Dataset with grassland phase of the versterker coast north of Harderwijk. Donated for the purposes of this hackathon and subject to conditions stated in the Farmhack Code of Conduct.

- Bij12 Data: Data packages originating from 12 provinces, land managers, ministries. Consisting of pdf's of vegetatieopnames, turbo-files, GIS files (polygon and point files), map images. Will be become Centrale Vegetatiebank managed by Bij12.The Centrale Vegetatiebank is being filled in as we speak and not available at this time.

- NDFF Data: Working on structural access to data. Overview of data avaliable on website, ordered by protocol: https://www.ndff.nl/overdendff/validatie/protocollen/overzicht-protocollen/




