# Ljubljana street trees
## Inventory of public street and park trees in Ljubljana, Slovenia.

The public company SNAGA in Ljubljana runs an inventory of trees in public domain for management purposes and they generously provided the baseline data for the analysis that went into the i-Tree Eco model (Tree species, tree DBH) as well as the geographical coordinates of tree locations.

CVS file contains the exported results from [i-Tree Eco v6](www.itreetools.org) model for ecosystem services as developed by USDA Forestry Service i-Tree team. Each tree has unique ID in the TREEID column. The i-Tree Manual for documentation of methodology is also published in this repository. To breifly explan how the model works: it takes user-provided tree data and local weather data (from USDA weather/air pollution database) to estimate: carbon storage, carbon sequestration, air pollution removal, water uptake. 

The shapefile inside the rar-file was exported from ESRI ArcGIS Pro, the files contain the location of trees as well as the results of the model parsed for individual tree.
