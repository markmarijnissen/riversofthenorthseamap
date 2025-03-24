# Rivers of the North Sea - Map

- [Download images here](https://github.com/markmarijnissen/riversofthenorthseamap/tree/main/images) 

![Rivers of the North Sea](<./images/Rivers of the North Sea.png>)

A map of the Rivers of the North Sea Bioregion. This repository contains source files to edit the map, as well as [images](https://github.com/markmarijnissen/riversofthenorthseamap/tree/main/images) you can use directly. Connect with us at the [Design School for Regenerating Earth](https://design-school-for-regenerating-earth.mn.co/) to co-create on this map.

## How to edit this map

You need to know how to use [QGIS](https://qgis.org/). If you want to share your map, you need to use Git to clone this repository (e.g. make a copy) and submit a Pull Request (e.g. send your copy back to me)

1. [Clone this repository ](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)(or download a *.zip file).
2. Open the project in QGIS and edit the map.
4. To share your map, [submit a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

## Data Sources

- Google Labels (from Google Maps) (`https://mt1.google.com/vt/lyrs=h&x={x}&y={y}&z={z}`).
- [Rivers in Europe (Derived from HydroSHEDS)](https://data.apps.fao.org/catalog/dataset/e0243940-e5d9-487c-8102-45180cf1a99f/resource/59557e5b-c852-4974-8576-8d954587b102)
- Rivers: [Catchment Characterisation and Modelling (CCM)](https://joint-research-centre.ec.europa.eu/scientific-tools-databases/catchment-characterisation-and-modelling-ccm_en)
    - W2008 dataset for the Nordic Rivers
- [HydroBasins](https://www.hydrosheds.org/products/hydrobasins).
    - Level 6 provide the black lines.
    - Level 5 provides the color of the rivers.
    - A combination of levels is used to define the borders of the bioregion.
- [Bioregions 2023](https://services5.arcgis.com/eWfoLt45Pxgl2X6V/ArcGIS/rest/services/Bioregions_2023/FeatureServer) from [OneEarth](https://www.oneearth.org/bioregions-2023/) provides a subtle colored background. (Currently hidden)
- [ESRI Satellite (ArcGIS)](https://server.arcgisonline.com/ArcGIS/rest/services/World_Imagery/MapServer/).

## License

Creative Commons: Attribution, Share Alike, Non Commercial ([CC BY-SA-NC 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/deed))

> To Do: Check compatability with CC BY-SA-NC 4.0 license with map data licenses.
