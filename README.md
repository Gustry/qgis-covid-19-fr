## Update data

Get data by running with the [provided quick-and-dirty bash script](layers/covid_19_fr/get_data.sh)

```bash
cd layers/covid_19_fr/
chmod +x get_data.sh
./get_data.sh
```

Run it every time you need to upgrade the data. This will 

* download CSV file
* create additionnal CSV and CSVT files
* import data into the `france.gpkg` Geopackage file

## Sources

* French Covid data: https://www.data.gouv.fr/fr/datasets/donnees-hospitalieres-relatives-a-lepidemie-de-covid-19/
* Spatial data: https://github.com/gregoiredavid/france-geojson

## Lizmap Web Client

A Lizmap Web Client configuration file has been added in this repository beside the QGIS project.
Versions:

* QGIS 3.4
* Lizmap Web Client 3.4pre

![](lizmap-covid-19-fr.gif)
