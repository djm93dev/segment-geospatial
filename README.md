# segment-geospatial

[![image](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/opengeos/segment-geospatial/blob/main/docs/examples/satellite.ipynb)
[![image](https://img.shields.io/badge/Open-Planetary%20Computer-black?style=flat&logo=microsoft)](https://pccompute.westeurope.cloudapp.azure.com/compute/hub/user-redirect/git-pull?repo=https://github.com/opengeos/segment-geospatial&urlpath=lab/tree/segment-geospatial/docs/examples/satellite.ipynb&branch=main)
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/opengeos/segment-geospatial/blob/main/docs/examples/satellite.ipynb)
[![image](https://img.shields.io/pypi/v/segment-geospatial.svg)](https://pypi.python.org/pypi/segment-geospatial)
[![image](https://img.shields.io/conda/vn/conda-forge/segment-geospatial.svg)](https://anaconda.org/conda-forge/segment-geospatial)

**A Python package for segmenting geospatial data with the Segment Anything Model (SAM)**

The **segment-geospatial** package draws its inspiration from [segment-anything-eo](https://github.com/aliaksandr960/segment-anything-eo) repository authored by [Aliaksandr Hancharenka](https://github.com/aliaksandr960). To facilitate the use of the Segment Anything Model (SAM) for geospatial data, I have developed the [segment-anything-py](https://github.com/opengeos/segment-anything) and [segment-geospatial](https://github.com/opengeos/segment-geospatial) Python packages, which are now available on PyPI and conda-forge. My primary objective is to simplify the process of leveraging SAM for geospatial data analysis by enabling users to achieve this with minimal coding effort. I have adapted the source code of segment-geospatial from the [segment-anything-eo](https://github.com/aliaksandr960/segment-anything-eo) repository, and credit for its original version goes to Aliaksandr Hancharenka.

-   Free software: MIT license
-   Documentation: <https://samgeo.gishub.org>

## Features

-   Download map tiles from Tile Map Service (TMS) servers and create GeoTIFF files
-   Segment GeoTIFF files using the Segment Anything Model (SAM)
-   Save segmentation results as common vector formats (GeoPackage, Shapefile, GeoJSON, etc.)
-   Visualize segmentation results on interactive maps

## Examples

-   [Segmenting satellite imagery](https://samgeo.gishub.org/examples/satellite)
-   [Automatically generating object masks](https://samgeo.gishub.org/examples/automatic_mask_generator)
-   [Segmenting satellite imagery with input prompts](https://samgeo.gishub.org/examples/input_prompts)

## Demos

-   Automatic mask generator

![](https://i.imgur.com/I1IhDgz.gif)

-   Interactive segmentation with input prompts

![](https://i.imgur.com/2Nyg9uW.gif)

-   Input prompts from existing files

![](https://i.imgur.com/Cb4ZaKY.gif)

## Tutorials

Video tutorials are available on my [YouTube Channel](https://youtube.com/@giswqs).

[![Alt text](https://img.youtube.com/vi/YHA_-QMB8_U/0.jpg)](https://www.youtube.com/playlist?list=PLAxJ4-o7ZoPcrg5RnZjkB_KY6tv96WO2h)

## Computing Resources

The Segment Anything Model is computationally intensive, and a powerful GPU is recommended to process large datasets. It is recommended to have a GPU with at least 8 GB of GPU memory. You can utilize the free GPU resources provided by Google Colab. Alternatively, you can apply for [AWS Cloud Credit for Research](https://aws.amazon.com/government-education/research-and-technical-computing/cloud-credit-for-research), which offers cloud credits to support academic research. If you are in the Greater China region, apply for the AWS Cloud Credit [here](https://aws.amazon.com/cn/events/educate_cloud/research-credits).

## Acknowledgements

This package was made possible by the following open source projects. Credit goes to the developers of these projects.

-   [segment-anything](https://github.com/facebookresearch/segment-anything)
-   [segment-anything-eo](https://github.com/aliaksandr960/segment-anything-eo)
-   [tms2geotiff](https://github.com/gumblex/tms2geotiff)
