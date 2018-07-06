# hubway-explore: exploring data from Hubway (now Blue Bikes) bike-share system

A collection of Jupyter notebooks I've written to study the Boston area bike-share system.

## Notebook guide:

- [hubway_logdata_24h](hubway_logdata_24h.ipynb): scrape bike data from Hubway website for 24 hours and save to CSV
- [hubway_plotbikedata_24h](hubway_plotbikedata_24h.ipynb): analyze 24 hours of bike data scraped from Hubway website
- [hubway_plotstations](hubway_plotstations.ipynb): plot location of stations on top of a shapefile of the Boston metro area, and analyze by station size and letter code
- [hubway_census_stations](hubway_census_stations.ipynb): plot locations of stations relative to population and income data from the US Census.

## Packages used:

- NumPy
- pandas
- matplotlib (including Basemap)
- Shapely
