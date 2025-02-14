# Data Repository for the PlantHub QueryBuilder

In this repository, you can find all information to reproduce the knowledge graph built for the PlantHub QueryBuilder. 

Contained in this repository are:

- (1) All datasets used to build the graph. 
- (2) All [Ontotext Refine](https://www.ontotext.com/products/ontotext-refine/) projects and editing histories to reproduce the final datasets.
- (3) All SQL exports to create a database from the datasets.
- (4) All [R2RML](https://github.com/chrdebru/r2rml) mappings to create an RDF graph from the database.

# How to use

For a more detailed description of the workflow, please refer to the publication "Semantic technologies for interdisciplinary research: A case study on improving data synthesis and integration in the biodiversity domain" at BTW2025.

Visitors of this repository can reproduce and use the contained data and mappings in a variety of ways. The simplest way of arriving at a finished RDF graph is by loading the SQL exports into a database and consequently executing the R2RML mappings on that database. This results in a .ttl file that can be uploaded to a triplestore of your choice.

The SQL statements are exported from Ontotext Refine projects containing the datasets uploaded to this repository. We publish the finished datasets and also provide the project files that take the raw data to their processed state, such that all operations on the data can be viewed. We also publish the operation histories exported from the project files.

# Data

The data shared in this repository contains 100K entries from [TRY](https://www.try-db.org/TryWeb/Home.php), the plant trait database, and the first 100K entries from the [naturgucker.de dataset hosted on GBIF](https://www.gbif.org/dataset/6ac3f774-d9fb-4796-b3e9-92bf6c81c084) (https://doi.org/10.15468/dl.e6ry9b).

In an update, we include a further subset of the naturgucker.de dataset, that contains plant occurrences in Germany from 01.01.2024-07.02.2025 (https://doi.org/10.15468/dl.x5cexq).

We enrich these datasets with additional information from [Wikidata](https://query.wikidata.org/), the [GBIF API](https://techdocs.gbif.org/en/openapi/v1/species), the [IUCN API](https://apiv3.iucnredlist.org/api/v3/docs), and the [OpenElevationAPI](https://open-elevation.com/).

# License

All sources are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en)
