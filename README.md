**Flood Analysis: Inundation detection plugin for QGIS**

This is a QGIS plugin to predict whether the regions with given height, water levels and river channel depths will flood or not.

Usage:

- Download the plugin from this link: <https://github.com/prashanttb/Inundation-detection-plugin-for-QGIS/archive/refs/heads/main.zip>
- Download the dummy QGIS project data file from this link: <https://drive.google.com/file/d/1y8CsJjyiz5zqYEx20LfH2OjequItc601/view?usp=sharing>
- Open this downloaded project file in QGIS.
- Plugin Installation:
  - In the toolbar click on Plugin, then select **Manage and Install Plugins** from the dropdown.

![](img/Aspose.Words.9aec7793-a6fd-4655-bf0f-df5a2c165947.001.png)

- A window will appear. Click on **Install from Zip** option from the side tab. Then browse the plugin zip file in your system by clicking on the 3 dots and click **Install Plugin** button.

![](img/Aspose.Words.9aec7793-a6fd-4655-bf0f-df5a2c165947.002.png)

- The plugin will be installed. You can open the plugin by clicking on the vector option on the toolbar and selecting **Flood Analysis.** 

![](img/Aspose.Words.9aec7793-a6fd-4655-bf0f-df5a2c165947.003.png)

- You will see a window like this

![](img/Aspose.Words.9aec7793-a6fd-4655-bf0f-df5a2c165947.004.png)

Input:

![](img/Aspose.Words.9aec7793-a6fd-4655-bf0f-df5a2c165947.005.png)

In the above figure,

Layer 1: Water Levels(black dots)

Attributes: Id, level(meters), name

Layer 2: Gutter Depths(Green dots)

Attributes: id, depth(meters), name

Layer 3: Gutter Line(Pink colored)

Attributes: id, name

Layer 4: Floor Area Polygons(Olive green color)

Attributes: id, height(meters), name

Output:

In the output, a resultant layer appears, which gives the area polygons which will be flooded.

![](img/Aspose.Words.9aec7793-a6fd-4655-bf0f-df5a2c165947.006.png)

The brown polygons are the ones which will be flooded. 
