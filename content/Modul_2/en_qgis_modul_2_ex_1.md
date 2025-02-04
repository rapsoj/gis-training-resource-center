# Exercise: The world

__🔙[Back to Homepage](/content/intro.md)__

## Aim of the exercise

This exercise will help you to get to know the interface of QGIS a bit better. Furthermore, you will load your first data in QGIS and gain some hands-on experience with the layer concept.

## Relevant Wiki Articles

* [QGIS Interface](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_interface_wiki.html)
* [Types of Geodata](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_geodata_types_wiki.html)
* [Geodata Import in QGIS](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_import_geodata_wiki.html)
* [Layer Concept](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_layer_concept_wiki.html)

## Data sources

Download the data folder [here](https://nexus.heigit.org/repository/gis-training-resource-center/Modul_2/Modul2_Exercise1_The_World/Modul2_Exercise1_The_World.zip) and save it on your PC. Unzip the .zip file!
The folder is called “Modul_2_Exercise1_The_World" and contains the whole [standard folder structure](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_projects_folder_structure_wiki.html#standard-folder-structure) with all data in the input folder and the additional documentation in the documentation folder.

- [World Countries (Generalized)](https://hub.arcgis.com/datasets/2b93b06dc0dc4e809d3c8db5cb96ba69_0/explore) (Polygon/Shapefile)
- [Significant Earthquake Dataset](https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.ngdc.mgg.hazards:G012153) (CSV)
- [Global Power Plant Dataset](https://datasets.wri.org/dataset/globalpowerplantdatabase) (Points/GeoPackage)

## Task

1. Open QGIS and create a [new project](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_projects_folder_structure_wiki.html#step-by-step-setting-up-a-new-qgis-project-from-scratch) by clicking on `Project` -> `New`
2. Once the project is created save the project in the “project” folder of the “Ex_The_world”.  To do that click on `Project` -> `Save as` and navigate to the folder. Name the project “Ex_The_World”.
3. Load the shape file "World_countries__generalized" in your project by drag and drop ([Wiki Video](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_import_geodata_wiki.html#open-vector-data-via-drag-and-drop)]). Or click on `Layer`-> `Add Layer`-> `Add Vector Layer`. Click on the three points ![](/fig/Three_points.png) and navigate to "World_countries__generalized". Select the file and click `Open`. Back in QGIS click `Add` ([Wiki Video](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_import_geodata_wiki.html#open-vector-data-via-layer-tab)).
``` {Attention}
With both methods, you need to select the file with the ending __.shp__ ! 
```
4. Load the GeoPackage file "global_power_plant_database_nuclear.gpkg" in the QGIS project. You can use one of the methods above. Either drag and drop ([Wiki Video](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_import_geodata_wiki.html#open-vector-data-via-drag-and-drop)]) the file or click on `Layer`-> `Add Layer`-> `Add Vector Layer`. Click on the three points ![](/fig/Three_points.png) and navigate to "global_power_plant_database_nuclear.gpkg". Select the file and click `Open`. Back in QGIS click `Add`([Wiki Video](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_import_geodata_wiki.html#open-vector-data-via-layer-tab)).
```{Note}
GeoPackage file can contain multiple files and even whole QGIS projects. When you load such a file in QGIS a window will appear in which you have to select the files you want to load in your QGIS project.
```
5. Now we want to load the file “Significant_earthquake_data.txt” into QGIS. Since this is vector data in text format we need to follow a certain process ([Wiki Video](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_import_geodata_wiki.html#open-csv-data-in-qgis)).
    * Click on `Layer`-> `Add Layer`-> `Add Delimited text Layer`. Click on the three points ![](/fig/Three_points.png) and navigate to "Significant_earthquake_data.txt". Select the file and click `Open`.
    * In the window "Data Source manager| Delimited Text" in QGIS open the dropdown menu `File Format` and check `Custom delimiter` and `Tab`
    * Open the dropdown menu `Geometry definition`. Make sure the option `Point coordinates` is checked. Furthermore, select for `X field` “LONGITUDE” and for `Y field` “LATITUDE”.
    * Select the coordinate reference system (CRS) "EPSG:4326-WGS 84".
    * Click `Add`
    ```{Note}
    When loading vector data in text format like .csv or .txt in QGIS, these data has to have latitude and longitude columns. 
    * `X field` =“LONGITUDE” 
    * `Y field` = “LATITUDE”.
    ```
```{figure} /fig/en_ex_The_world_add_text_layer_import.png
---
width: 600px
name: 
align: center
---
```
6. Arrange the three layers in a practical order. Remember the  [Layer Concept](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_layer_concept_wiki.html).
7. Interact with the map and explore the data sets. Use the zoom tool and move the map.
8. Save your project by clicking on the ![](/fig/mActionFileSave.png) or use the hotkey combination `Ctrl` + `S`
```{Tip}
If you see `*` before the name of your project on the top left corner of QGIS this means there are unsaved changes in your project. Save your progress!
```
9. Your results should look something like this: 
```{figure} /fig/en_ex_The_world_result.png
---
width: 600px
name: 
align: center
---
```









