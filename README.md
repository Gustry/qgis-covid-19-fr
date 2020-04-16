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
