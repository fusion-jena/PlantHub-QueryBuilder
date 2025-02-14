# PlantHub-QueryBuilder

In this repository, you can find all information to reproduce the knowledge graph built for the PlantHub QueryBuilder. 

Contained in this repository are:
(1) All datasets used to build the graph. 
(2) All Ontotext Refine projects and editing histories to reproduce the final datasets.
(3) All SQL exports to create a database from the datasets.
(4) All R2RML mappings to create an RDF graph from the database.

# Data

The data shared in this repository contains 100K entries from TRY, the plant trait database, and the first 100K entries from the naturgucker.de dataset hosted on GBIF (https://doi.org/10.15468/dl.e6ry9b).

In an update, we include a further subset of the naturgucker.de dataset, that contains plant occurrences in Germany from 01.01.2024-07.02.2025 (https://doi.org/10.15468/dl.x5cexq).

We enrich these datasets with additional information from Wikidata, the GBIF API, the IUCN API, and the OpenElevationAPI.

# License

All sources are licensed under CC BY 4.0
