# qgis handson

### Loading data from data source manager

Different type of data sources used: Vector Shape files, GeoPacakge files and Spatiallite db file loaded from training dataset.

- Install QGIS on ubuntu 22.04
- Download training data from qgis training manual
- Create a new project in QGIS
- Load a basic shape file - protected areas
- Load river shape file. Observe layers tab showing all loaded shapes in a stack view
- Load Geopackage file - gpkg file format. Load roads from this dataset.
- Load sqlite data source - and load landuse data to layers.
- Save the project inside solutions directory.

This is how the layers look like when loaded properly:

![Layers001](./layers001.png)

#### Use of symbology

Symbology allows you change the visual representaiton of your layers. For example: changing the color fill, adding border etc.

The following image shows how you can do symbology on different layers to acheive something like this, where roads are marked bold, landuse base color is changed to green, buildings are marked red. Also buildings layer has scale dependent layer rendering. 

![Symbology](./symbology.png)