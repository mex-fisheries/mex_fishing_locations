# A Geospatial Dataset of Landing Sites in Mexico

## Data sources:

- Ramírez Rodríguez, M., López Ferreira, C., & Hernández Herrera, A. (2004).  Atlas de localidades pesqueras de Baja California, Baja California Sur y Sonora. México Instituto Politécnico Nacional, Centro Interdisciplinario de Ciencias Marinas, Comisión Nacional de Acuacultura y Pesca

## Data set construction

- Step 1: Manually extract sitekey tables from [PDF](link/to/atlas) into [Excel](data/raw/atlas_locations_raw.xlsx), with one sheet per "group"
- Step 2: ...
- Step 3: Build a geopackage of locations
- Step 4: [Combine](code/sitekey_cleaning.html) geopackage of locations with sitekey info.

## Output data description

### [sites_key.gpkg](dat/processed/sites_key.gpkg)

A geopackage (vector) data set with X rows and Y columns:

- `Column 1`:  (Type numeric / character / geometry) Description
- `Column 2`:  (Type numeric / character / geometry) Description
- `Column 3`:  (Type numeric / character / geometry) Description
- `Column 4`:  (Type numeric / character / geometry) Description .....

## How to access these data

