# QGIS common errors and issues <!-- omit from toc -->

Here we are collecting common QGIS errors and issues as general QGIS training support.

# Table of content <!-- omit from toc -->

- [Different QGIS versions](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#different-qgis-versions)
- [QGIS on Mac doesn't open](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#qgis-on-mac-doesnt-open)
- [A layer is not displayed in QGIS](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#a-layer-is-not-displayed-in-qgis)
- [A layer window has disappeared in QGIS](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#a-layer-window-has-disappeared-in-qgis)
- [Layers that should actually be in the same position are not on top of each other](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#layers-that-should-actually-be-in-the-same-position-are-not-on-top-of-each-other)
- [Layer file disappeared from the layer window](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#layer-file-disappeared-from-the-layer-window)
- [Missing processing tools in the panels tool and incomplete vector tab](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#missing-processing-tools-in-the-panels-tool-and-incomplete-vector-tab)
- [Missing toolbox](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#missing-toolbox)
- [The North arrow is not syncing with the corresponding map](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#the-north-arrow-is-not-syncing-with-the-corresponding-map)
- [Invalid Geometry](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#invalid-geometry)
- [Coordinate systems: What do all these terms mean?](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#coordinate-systems-what-do-all-these-terms-mean)
- [Coordinate systems: How do I redefine a dataset's coordinate system?](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#coordinate-systems-how-do-i-redefine-a-datasets-coordinate-system)
- [Coordinate systems: Why is Mercator ever used if it's so distorted?](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#coordinate-systems-why-is-mercator-ever-used-if-its-so-distorted)
- [Coordinate systems: My dataset is not located where it should be!](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#coordinate-systems-my-dataset-is-not-located-where-it-should-be)
- [Coordinate systems: What coordinate system should my dataset be in?](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#coordinate-systems-what-coordinate-system-should-my-dataset-be-in)
- [My dataset is slightly offset from where it should be!](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#my-dataset-is-slightly-offset-from-where-it-should-be)
- [Wrong data results or missing data](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#wrong-data-results-or-missing-data)
- [File Management Issues](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#file-management-issues)
- [Specific QGIS problems](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#specific-qgis-problems)
  - [Basic settings \> Deactivating the automatic projection selection](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#basic-settings--deactivating-the-automatic-projection-selection)
  - [Saving regularly](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#saving-regularly)
  - [GRASS applications](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#grass-applications)
  - [SAGA with Linux](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#saga-with-linux)
  - [Umlauts, special characters, spaces in file paths](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#umlauts-special-characters-spaces-in-file-paths)
- [QGIS Help Access Links](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#qgis-help-access-links)
    - [QGIS tutorials and tips:](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#qgis-tutorials-and-tips)
    - [QGIS community/forums:](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#qgis-communityforums)
    - [QGIS YouTube channels:](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#qgis-youtube-channels)
    - [ChatGPT](https://giscience.github.io/gis-training-resource-center/content/Wiki/en_qgis_common_errors_and_Issues.html#chatgpt)



## Different QGIS versions 
The Wiki and in particular the videos in it are only a snapshot in time. QGIS itself, as well as the installable extensions, are constantly being developed and improved. Therefore there may be differences between the various versions in the appearance of the user interface or, in rare cases, even in the function. Consequently, there may be differences between the Wiki and the QGIS installed on your PC. Nonetheless this cahpter focusses on common errors and issues, hopefully for many (upcoming) versions.

## QGIS on Mac doesn't open
When opening QGIS for the first time on Mac you may get this error message:

```{figure} /fig/qgis_on_mac.png
---
width: 55%
name: qgis_on_mac.png
align: center
name: Error when opening QGIS on Mac for the first time
---
Error when opening QGIS on Mac for the first time. 
```

To solve this, press the control button on your keyboard and right-click open.
    
If this problem persists, you can change the settings on your device. Go in the `Settings` > `Security & Privacy` and scroll down, click `Open Anyway`

```{figure} /fig/opening_qgis_mac.png
---
width: 55%
name: opening_qgis_mac.png
align: center
name: Change settings to open QGIS on Mac
---
Change settings to open QGIS on Mac.
```


## A layer is not displayed in QGIS 

 __Solution:__ 
  1. Right click on the corresponding layer. 
  2. Activate the `Zoom to Layer` function in the pop-up window. 

```{figure} /fig/en_layer_display.png
---
width: 55%
name: en_layer_display.png
align: center
name: Zoom to layer if layer is not displayed
---
Zoom to layer if layer is not displayed.
```


## A layer window has disappeared in QGIS

__Solution:__
 1. Open in the main tab `View`. 
 2. In the pop-up window select `Panels`. 
 3. In the sub-window hook the case `Layers`.   

```{figure} /fig/en_closed_layer_view.png
---
width: 75%
name: en_closed_layer_view.png
align: center
name: Layer window disappeared
---
Layer window disappeared.
```

## Layers that should actually be in the same position are not on top of each other

__Solution:__

These sort of problems are usually due to a) *mismatching crs in layers and project*, or b) an *incorrect reprojection*. 

 a) 
 1. Check the layer properties (right-click on the corresponding layer).
 2. Select in the pop-up window `Properties`.
 3. In the next pop-up-window select `Information` and check which projection is defined under the entry `Coordinate Reference System (CRS)`. 
 4. And additionally check if the same projection is set in the status bar at the bottom right.
 5. Correct any discrepancies by reprojecting the layers or changing the setting of the crs project. 

b) 

**Reprojecting:**  
When having two layers with different crs, then select one of the layers as the input layer having, f. e. the crs EPSG:32632 - WGS 84 and select EPSG:4326 - WGS 84 as the target crs. Start the algorithm and you will receive a new layer, identical to the input layer, but with a different crs. 

It is displayed in the workspace in the same place as the other layers, as QGIS reprojects it at runtime. However, its actual coordinates are different. 


```{figure} /fig/en_qgis_layer_with_different_KBS.png
---
width: 75%
name: en_qgis_layer_with_different_KBS.png
align: center
name: Layer with different crs
---
Layer with different crs.
```

You can check this using the `Add Geometry Attributes` < `Geometry Tools` algorithm. The coordinates are different from the coordinates in the other two attribute tables of the other layers.

Instead do this:

1. Select the `Vector`tab.

2. Activate in the pop-up menue `Data Management Tools`.

3. And in the following pop-up menue `Reproject Layer`.


```{figure} /fig/en_qgis_reproject_vector_layer01.png
---
width: 75%
name: en_qgis_reproject_vector_layer01.png
align: center
name: Reproject Layer in QGIS
---
Reproject Layer in QGIS.
```


```{figure} /fig/en_qgis_reprojected_layer.png
---
width: 75%
name: en_qgis_reprojected_layer.png
align: center
name: Tool to reproject layer in QGIS
---
Tool to reproject Layer in QGIS.
```

Always save your reprojected layers by the `Export` and `Save as` functions because they are only temporarily saved and will disappear after closing the project.

```{figure} /fig/en_qgis_reprojection_export.png
---
width: 75%
name: en_qgis_reprojection_export.png
align: center
name: Export reprojected layer
---
Export reprojected layer.
```

Similar procedure for raster layers ...

1. Select the `Raster` tab.

2. Activate in the pop-up menu `Projections`.

3. And in the following pop-up menu `Warp (Reproject)`


```{figure} /fig/en_qgis_reproject_raster_layers01.png
---
width: 75%
name: en_qgis_reproject_raster_layers01.png
align: center
name: Reproject raster layer in QGIS
---
Reproject raster layer in QGIS.
```
```{attention} 
 Errors often occur if the crs is set and no reprojection tool has been used. If you suspect that your reprojection has gone wrong, delete all affected layers from QGIS, reload the data and then reproject and export them. 
```

## Layer file disappeared from the layer window

If a layer file is no longer displayed or active in the layer window after reopening a QGIS project, it was only a temporary layer. Temporary layers have a symbol on the right of their name, as so:
 ![](/fig/en_qgis_temporary_Layer.png)

__Solution:__

Next time, save it: 
1. Click on the tab `Layer` and on `Save as` in the pop-up window.

```{figure} /fig/en_qgis_save_layer01.png
---
width: 65%
name: en_qgis_save_layer01.png
align: center
name: Save layer
---
Save layer.
```


2. Put in a _file name_ and click on the `three points` ![](/fig/Three_points.png) to save the file on the chosen directory place.
3. Select the corresponding CRS.
4. Click `ok`.

```{figure} /fig/en_qgis_save_layer02.png
---
width: 85%
name: en_qgis_save_layer02.png
align: center
name: Save layer in directory
---
Save layer in your directory.
```



## Missing processing tools in the panels tool and incomplete vector tab

 __Solution:__
  
  1. Activate the `Processing Tools` by going to `Plugins` >
  `Manage and install Plugins`.
  2. Select `All`. 
  3. Rehook the `Processing` function in the corresponding list.
  
```{figure} /fig/en_missing_processing_tools.png
---
width: 85%
name: en_missing_processing_tools.png
align: center
name: Reinstall processing tool
---
Reinstall processing tool.
```
See also: Geographic Information Systems
https://gis.stackexchange.com/questions/202111/missing-processing-tools-in-vector-menu-of-qgis


## Missing toolbox
  __Solution:__

  1. To reactivate the `Toolbox` ![](/fig/mAction.png) click on the `View Tab`.
  2. Select in the pop-up window `Panels`. 
  3. Set in the following pop-up window a hook for the `Processing Toolbox`.  

```{figure} /fig/en_missing_toolbox.png
---
width: 75%
name: en_missing_toolbox.png
align: center
name: Reactivate toolbox
---
Reactivate toolbox.
```

## The North arrow is not syncing with the corresponding map
__Solution:__

There are two places where you have to define with which map the north arrow should sync with.

 In the `Layout Tab` (of the print layout) for the map image under `General Settings` make sure that the reference map has the right map selected. 


```{figure} /fig/en_qgis_correct_referenciation_to_map.png
---
width: 85%
name: en_qgis_correct_referenciation_to_map.png
align: center
name: Reactivate toolbox
---
Correct referenciation to map.
```

See also: Geographic Information Systems
https://gis.stackexchange.com/questions/265095/north-arrow-not-syncing-with-map-qgis-2-18#:~:text=1%20Answer&text=2-,There%20are%20TWO%20places%20where%20you%20have%20to%20tell%20it,and%20tell%20it%20which%20map
 
## Invalid Geometry

If the error message `Invalid Geometries` appears, it may be that vector files have "slipped" during the processing or downloading process (e.g. the lines of polygons no longer fit together exactly).

__Solution:__

These errors in the geometries can be corrected by running `Fix Geometries`. Search for it in the Processing Toolbox.

## Coordinate systems: What do all these terms mean?

Geospatial datasets consist of three basic data:

+ Attributes: the meanings or labels of a data point.

+ Coordinates: numbers describing the data point's position in space.

+ Coordinate (reference) system: metadata describing the space itself: origin, axes, units, etc.

For example:

+ Attributes: "The White House" or "1600 Pennsylvania Avenue"

+ Coordinates: (-77.0367, 38.8976)

+ Coordinate (reference) system: WGS84 longitude,latitude



```{Tip}
For further detailed information about coordinate systems have also a look at: https://ihatecoordinatesystems.com/#correct-crs
```

## Coordinate systems: How do I redefine a dataset's coordinate system?

Redefining means the metadata about the coordinate system is modified but the coordinates are not. This contrasts with reprojections and transformations, which modify both the coordinate system and the coordinates.

__Solutions:__

+ In QGIS, for vector datasets, use the `Assign Projection` tool in the `Vector General` toolset, not the `Reproject Layer` tool. See also: https://docs.qgis.org/3.28/en/docs/user_manual/processing_algs/gdal/rasterprojections.html#assign-projection 


+ In QGIS, for raster datasets, use the `Assign Projection` tool in the `GDAL` toolset, not the `Warp (Reproject)` tool. See also: https://docs.qgis.org/3.28/en/docs/user_manual/processing_algs/gdal/rasterprojections.html#assign-projection 


+ From the command line, for vector datasets, use `ogr2ogr` with the `-a_srs` parameter, not the `-t_srs` parameter. See also:
https://gdal.org/programs/ogr2ogr.html#cmdoption-ogr2ogr-a_srs 


+ From the command line, for raster datasets, use `gdal_edit` with the `-a_srs` parameter. See also: https://gdal.org/programs/gdal_edit.html#cmdoption-a_srs.py 

## Coordinate systems: Why is Mercator ever used if it's so distorted?

Mercator is the only conformal cylindrical map projection. Cylindrical map projections mean the whole earth fits into a rectangle, which is very convenient for data processing algorithms that are used to working with rectangular images. Conformal means that angles and shapes are always preserved: north is always up, squares are always square, etc.. Using a non-conformal projection would make things look stretched, squashed, and/or rotated when zooming in.


```{figure} /fig/qgis_mercator.jpg
---
width: 75%
name: qgis_mercator.jpg
align: center
name: Mercator projection
---
Mercator projection.
```

Mercator does enlarge areas farther from the equator, but at least this distortion is the same horizontally and vertically. And it's trivial to calculate a scale factor to correct measurements (See also: https://en.wikipedia.org/wiki/Mercator_projection#Scale_factor).  
The only time the distortion is problematic, is when viewing a global-scale map with a range of different scale factors, but most maps are not global-scale and there are plenty of better projections to use for this case.

## Coordinate systems: My dataset is not located where it should be!
Your dataset probably has the wrong coordinate system. This is the more general case of the previous problem. This can happen if the coordinate system is missing altogether, in which case GIS software often assumes that it is the same coordinate system as a previously loaded dataset, or the coordinate system set in the "project" or "map document".

__Solution:__

 Redefine the coordinate system, redefine i.e. change the coordinate system but not the coordinates, to the correct coordinate system. 

1. Open your `Project`: Open the QGIS project where you want to redefine the coordinate system.

2. Access `Project Properties`: Go to the `Project menu` at the top of the QGIS window and select `Properties`. Alternatively, you can press `Ctrl + Shift + P` as a shortcut.

3. Coordinate System Tab: In the `Project Properties` window, select the `Coordinate System  tab.

4. Change Coordinate System: Here, you can select a new coordinate system for your project. You can search for a specific coordinate system using the search bar, or you can browse through the list of available coordinate systems.

Apply Changes: Once you've selected the desired coordinate system, click `OK` to apply the changes. QGIS will reproject the layers in your project to match the new coordinate system.

```{figure} /fig/en_qgis_redefining_CRS01.png
---
width: 80%
name: en_qgis_redefining_CRS01
align: center
name: Redefining CRS
---
Redefining CRS.
```

5. Check and Adjust Layers: After redefining the coordinate system, it's essential to check your layers to ensure they align correctly. Some layers may require manual adjustments or reprojection if they don't align as expected.
And have also a final look at the right bottom of the QGIS window where the actual CRS is indicated.

```{figure} /fig/en_qgis_redefining_CRS02.png
---
width: 80%
name: en_qgis_redefining_CRS02
align: center
name: Check redefining CRS
---
Check redefining CRS.
```

## Coordinate systems: What coordinate system should my dataset be in?

A data point's attributes gives context to where on the earth it is located. Most GIS software will display the minimum and maximum coordinates in the layer's properties as "extent" or "bounding box". 

__Solutions:__

If the attributes indicate the approximate longitude,latitude where the coordinates should be located, try doing a reverse lookup. This iterates over every well-defined coordinate system, unprojects the X,Y coordinates to WGS84, and measures the error to the known longitude,latitude. Errors less than a few hundred meters denote a reasonable projection, though this isn't precise enough to determine the GCS. 
You can run this sample code yourself, or use this form:


<form>
    <table style="padding: 0.5em;width:100%;font-size:90%;">
        <colgroup>
            <col span="1" style="width: 18%;">
            <col span="1" style="width: 20%;">
            <col span="1" style="width: 18%;">
            <col span="1" style="width: 20%;">
            <col span="1" style="width: 20%;">
        </colgroup>
        <tbody>
            <tr>
                <td style="text-align:right;"><label for="lookup_lng">Longitude:</label></td>
                <td><input style="width:90%;" type="number" step="any" id="lookup_lng"
                        name="lookup_lng"></td>
                <td style="text-align:right;"><label for="lookup_lat">Latitude:</label></td>
                <td><input style="width:90%;" type="number" step="any" id="lookup_lat"
                        name="lookup_lat"><br></td>
                <td></td>
            </tr>
            <tr>
                <td style="text-align:right;"><label for="lookup_x">X-coordinate:</label></td>
                <td><input style="width:90%;" type="number" step="any" id="lookup_x" name="lookup_x">
                </td>
                <td style="text-align:right;"><label for="lookup_y">Y-coordinate:</label></td>
                <td><input style="width:90%;" type="number" step="any" id="lookup_y" name="lookup_y">
                </td>
                <td><input style="width:70%;" id="projectionLookupButton" type="submit" value="Submit">
                </td>
            </tr>
        </tbody>
    </table>
</form>
<p id="projectionLoookupLoading" style="display:none;text-align:center;">
    <span id="projectionLoookupLoadingText" class="bold italic"></span>
</p>
<table id="projectionLookupResults" style="display:none;padding:0.5em;font-size:80%;">
    <tr>
        <td><span class="bold">Code</span></td>
        <td><span class="bold">Name</span></td>
        <td style="text-align:right;"><span class="bold">Error (meters)</span></td>
    </tr>
</table>

<br>



+ If the coordinates have X-values between -180 and 180, and Y-values between -90 and 90, then you probably want to redefine to a longitude,latitude geographic coordinate system (GCS) like WGS84.

+ If the coordinates have large absolute values, try redefining to a local coordinate system like UTM, Gauss-Krüger, State Plane, or a national grid. Also consider trying neighboring zones, e.g. if UTM Zone 19N is wrong, try UTM Zone 18N.

+ If the attributes suggest the dataset is in the USA, then there might a problem converting to/from Freedom Units. Try multiplying/dividing a data point's coordinates by 3.28084 to convert feet to meters/meters to feet and see if that places it in the proper location.

+ If the minimum X/Y coordinates are both zero and the maxmimum X/Y coordinates are both positive, then the dataset may have been exported from non-geospatial software like Photoshop or Illustrator or Inkscape. This is especially likely if the dataset is flipped vertically since those editors typically have the Y-axis increasing going down. You will need to manually georeference the dataset to use it, which changes both the coordinates and the coordinate system.

See also the following [__Wiki_Page__]
(../Wiki/en_qgis_projections_wiki.md)
`Projections`.


## My dataset is slightly offset from where it should be!

Your dataset probably has the wrong longitude/latitude geographic coordinate system (GCS). Different GCSs define slightly different sizes/shapes of the Earth (their ellipsoids) and different positionings on the Earth (their datums). As a result, the same longitude/latitude coordinates in two different GCSs can appear offset, although typically within tens of meters of each other. This can happen even if you are using a projected coordinate system (PCS) whose units are not degrees of longitude/latitude since PCSs have a GCS embedded within them.

```{figure} /fig/qgis_wrong-gcs.png
---
width: 75%
name: qgis_wrong-gcs.png
align: center
name: Offset because of wrong GCS
---
Offset because of wrong GCS. Source: ???
```

__Solution__:

 Redefine the coordinate system, i.e. change the coordinate system but not the coordinates, to one of the following:

* Try redefining to the WGS84 GCS.
* If your dataset was collected with GPS, try redefining to WGS84.
* If your dataset was collected with GLONASS, try redefining to PZ-90.
* If your dataset was collected with Galileo, try redefining to ITRF.
* If your dataset is in the USA, try redefining to NAD27, NAD83, or WGS84.
* If your dataset is in Europe, try redefining to ED50, ETRS89, or WGS84.
*If your dataset is in Australia, try redefining to GDA94 or GDA2020.
*If your dataset is in China and/or collected with BeiDou, good luck. :weary:

## Wrong data results or missing data

When you get wrong data results or missing data, please check your file names. You should not use file names with capitals, special characters or empty spaces. Always use underscores between the words for the file name.

## File Management Issues

There may be different reasons, f.e. reopening your QGIS project, not all files will be displayed correctly because some got lost or were stored on different places. In any case, there is a solution: a clear folder structure.

__Solution:__

Recommended standard folder structure:

```{figure} /fig/Standard_project_folder_structure.drawio.svg
---
width: 75%
name: Standard_project_folder_structure.drawio.svg
align: center
name: Standard folder structure
---
Standard folder structure. Source: ???
```

How it might look like on your pc:

```{figure} /fig/en_qgis_folder_structure_pc.png
---
width: 75%
name: en_qgis_folder_structure_pc.png
align: center
name: Standard folder structure on your PC
---
Standard folder structure on your PC.
```
The standard folder structure has two principal advantages:
1. By sharing the whole project folder, we can be certain that the project will run without problems on a different computer.
2. The folder structure supports the proper organization of geodata and supports the stable function of a QGIS project. 

The folder structure template can be downloaded [__here__](https://github.com/GIScience/gis-training-resource-center/blob/main/fig/GIS_Project_folder_template.zip).


```{Tip}
The layer data used in the project are not saved in the project file. Instead, the project file only contains the file paths where the layer data were located at the time the project was last saved on the PC. If the location of this layer data is subsequently changed, the error message "handle unavailable layers" will appear when the project is opened again.
Good data organisation with a fixed and well thought-out folder structure prevents such problems.
```

See also the following [__Wiki_Page__]: 

(https://github.com/GIScience/gis-training-resource-center/blob/main/content/Wiki/en_qgis_projects_folder_structure_wiki.md) for `How to create a new QGIS project` and `How to open an existing QGIS project`.

## Specific QGIS problems 
### Basic settings > Deactivating the automatic projection selection
After installing QGIS, some basic settings should be changed to avoid possible sources of error.
If a layer file does not have a projection, a projection must be defined for it when it is imported into QGIS. By deactivating the automatic projection selection, this projection can be defined manually. This prevents layers from accidentally being in the wrong projection.

1. Select the `Settings` tab.
2. Then activate in the nagivation menu `Options`.
3. In the pop-up window select `CRS Handling`. 
4. Under `CRS for projects` activate `Use CRS from first layer added`. 
5. And under `CRS for layers` activate `Prompt for CRS`.

```{figure} /fig/en_qgis_CRS_settings.png
---
width: 95%
name: en_qgis_CRS_settings.png
align: center
name: Change crs settings in QGIS
---
Change crs settings in QGIS.
```

### Saving regularly
Unfortunately, GIS programs are notorious for freezing or crashing completely. Although there is a trend towards fewer complications with better hardware, even a "gaming PC" costing several thousand dollars is not completely safe.
More complex tasks with longer calculation times may still cause problems. Regular saving is therefore recommended.

See also the following [__Wiki_Page__]:

(https://github.com/GIScience/gis-training-resource-center//content/Wiki/en_qgis_interface_wiki.html#save-open-qgis-projects) `Save and open QGIS Projects.` 

### GRASS applications

QGIS also allows the use of tools from external GIS software, such as GRASS GIS. GRASS does not have to be downloaded separately, but is automatically installed when QGIS is installed. GRASS tools are identified by their icon. 

```{attention} 
Please note that the GRASS software is not started when the standard QGIS application is started. Consequently, an error message may appear when using GRASS tools. This can be remedied by opening the QGIS with GRASS application (found via the computer's search function) instead of the standard application.
```

### SAGA with Linux

SAGA is another external GIS software. SAGA tools are identified by their icon. When using Windows or MacOS as the operating system, SAGA is automatically implemented when QGIS is installed. With Linux, however, SAGA is not installed automatically and must be installed manually. Experience has shown that this installation is not always easy and can cause problems. Alternatively, you can either use a Windows or MacOS virtual box or refrain from using SAGA tools (you will then have to search for alternative tools yourself).

### Umlauts, special characters, spaces in file paths

If the file path contains umlauts (ä,ö,ü), special characters (!,?, ., etc.) or spaces, this can lead to problems when these files are processed by QGIS. It is therefore recommended that you avoid these characters in your file paths (write out umlauts, replace spaces with _).

```{attention} 
Temporary files are user-specific (if several people use one PC, each person has their own temporary files). The file path therefore contains your user name. If this contains problematic characters, it may therefore be advisable to change it.
```

## QGIS Help Access Links

Here you will find further help access links or QGIS community/forum links to address specific issues:

#### QGIS tutorials and tips:
+ Collection of QGIS tutorials and tips: https://www.qgistutorials.com/en/

+ QGIS training manual: https://docs.qgis.org/3.28/en/docs/training_manual/index.html

+ QGIS user guide: https://docs.qgis.org/3.28/en/docs/user_manual/index.html

+ QGIS server guide/manual: https://docs.qgis.org/3.28/en/docs/server_manual/index.html

+ QGIS plugin user manual: https://docs.qgis.org/3.28/en/docs/user_manual/plugins/plugins.html

+ QGIS workshop and video tutorials (Harvard University): https://gis.harvard.edu/qgis-workshop-and-video-tutorials-0 

+ QGIS tutorial (CartONG): https://cartong.pages.gitlab.cartong.org/learning-corner/en/6_tutorials/6_3_gis/6_3_1_qgis

#### QGIS community/forums:
+ Geographic Information Systems: https://gis.stackexchange.com/?tags=qgis

+ QGIS user groups: https://www.qgis.org/en/site/forusers/usergroups.html#qgis-usergroups

#### QGIS YouTube channels: 
+ The best YouTube channels in QGIS and open source gis tools: https://hatarilabs.com/ih-en/the-best-youtube-channels-in-qgis-and-open-source-gis-tools-in-any-language 
+ Absolute beginners guide to QGIS: https://www.youtube.com/watch?v=NHolzMgaqwE
+ QGIS complete tutorial for beginners: https://www.youtube.com/watch?v=d15Xl4OphDk
+ QGIS for beginners: https://www.youtube.com/watch?v=Eg4_duqH5Q4
+ Introduction to QGIS: https://www.youtube.com/watch?v=kxJI5FAGjzQ

#### ChatGPT
+ And don't forget ChatGPT https://chat.openai.com/
It is quick!