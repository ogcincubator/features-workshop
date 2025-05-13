# QGIS

*[QGIS](https://qgis.org/) is a geographic information system (GIS) software that is free and open-source. QGIS supports Windows, macOS, and Linux. It supports viewing, editing, printing, and analysis of geospatial data in a range of data formats* (Wikipedia).

1. Add a context map (QuickMapServices) and zoom to Japan.

![Zoom to Japan](img/0_zoomjapan.png)

2. `Add WFS/OGC API - Features Layer...` from the Layer menu (or browser panel).

![Add WFS layer](img/1_addlayer.png)

3. Instantiate a new server connection. *Set connection details, using the landing page url and limiting the maximum number of features (500) and paging (100), for performance reasons!*

![Connect to server](img/2_serverconnection.png)

3. Add the [dam collection](https://pygeoapi.glodal-inc.net/collections/W01): `ダム（W01-05-g`.

![Add collection](img/3_addcollection.png)

4. If you want, you can change the style by right-clicking on the layer to bring up the context menu and then selecting `properties`:

![View Layer](img/6_loadlayer.png)

5. Go to the `symbology` tab and choose `categorized` on the drop-down menu; on `value`, select the field that you want to use for the color ramp, and then click `classify`.

![Symbol](img/7_symbol.png)

6. Go to the `labels` tab and choose `single labels` on the drop-down menu; on `value`, select the field that you want to use for the labels, and enable the options `Draw text label` and `Color buffer's fill`; click `ok` to close the dialogue.

![Label](img/8_label.png)

![View styled](img/9_viewlayer.png)

You can find more information on how-to style layers in QGIS on [this](https://docs.qgis.org/3.40/en/docs/user_manual/working_with_vector/vector_properties.html#index-1) and [this](https://docs.qgis.org/3.40/en/docs/training_manual/vector_classification/label_tool.html) pages of the official documentation. 