# Workshop: Integrating Data from OGC API into your Applications 🍣

This workshop shows different ways of consuming data from [OGC API - Features](https://features.developer.ogc.org/) services. After completing this workshop, you should be able to integrate OGC API - Features into your workflows.

## Requirements

* Basic knowledge of python/ jupyter notebooks is required for some parts of the workshop.
* Basic knowledge of frontend web development (e.g.: HTML + JavaScript) is required for some parts of the workshop.
* Some knowledge about REST architecture is recommended (e.g.: http verbs, status codes), although not required.

No previous knowledge of GIS or OGC Standards is required for this workshop.

Before starting the workshop, make sure that you have access to a computer with the following installed:

* ✅ QGIS: you can follow the [instructions on the official website](https://qgis.org/resources/installation-guide/) to install it.
* ✅ Jupyter notebook: You can follow [these](https://jupyter.org/install) instructions to install it with pip.

## Introduction

In this workshop, we are going to connect to this deployment of [pygeoapi](https://pygeoapi.io/) provided by [GLODAL](https://glodal-inc.com/en-US/) (thank you!🙏💚) 

https://pygeoapi.glodal-inc.net/

https://pygeoapi.glodal-inc.net/openapi?f=html

* Present API
* Present datasets

## QGIS

* Intro QGIS

1. Add a context map (QuickMapServices) and zoom to Japan.

![Zoom to Japan](img/0_zoomjapan.png)

2. `Add WFS/OGC API - Features Layer...` from the Layer menu (or browser panel).

![Add WFS layer](img/1_addlayer.png)

3. Instantiate a new server connection. Set connection details, using the landing page url and limiting the maximum number of features (500) and paging (100), for performance reasons.

![Connect to server](img/2_serverconnection.png)

3. Add the [dam collection](https://pygeoapi.glodal-inc.net/collections/W01): `ダム（W01-05-g`.

![Add collection](img/3_addcollection.png)

4. Explore the collection in the QGIS map view.

![View Layer](img/5_stylelayer.png)

## Python/ OWSLib

TODO

## JavaScript/ LeafLet

TODO
