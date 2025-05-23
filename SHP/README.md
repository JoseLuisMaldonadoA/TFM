# SHP Files Folder

This folder contains a set of shapefiles of a single "*Geographic Information System*" layer exported from *QGIS*, along with the attribute data of this layer in a *CSV* file.

## Included Files

- `.shp` — Main file containing the geometry of the features.
- `.dbf` — Attribute data in tabular format (dBase format).
- `.shx` — Index file linking the *.shp* and *.dbf* files.
- `.prj` — Projection file specifying the coordinate reference system.
- `.cpg` — Character encoding used in the *.dbf* file.
- `.csv` — A CSV export of the attribute table for easy viewing and analysis outside of QGIS.

## Notes

- Exported from QGIS version 3.34.7-Prizren.
- The data links the postcodes from Spain with the average incomes of the inhabitants from each Spanish postal region, which has been put together to use it in the data preprocesing of this project.
- The CSV file is provided for convenience (this data is used in R) and does not include geometry data.
