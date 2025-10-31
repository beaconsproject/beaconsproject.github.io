<center><img src="pics/bp_banner.png" alt="BEACONs Project"></center>
<hr>
(Updated 2025-10-31)

### Welcome to the BEACONs GitHub page!

The [BEACONs Project](https://beaconsproject.ualberta.ca/) was founded at the University of Alberta in recognition for a new approach to conservation planning in North America's boreal region. We are building a credible scientific framework for comprehensive land & water stewardship through the development and application of leading-edge conservation science that includes consideration of both conservation areas and lands & waters managed for other values. The premise of our research is that the ultimate goal is to identify human activities that are compatible with the maintenance of biological diversity and integrity of ecological systems. The conceptual scientific framework guiding our research is the Conservation Matrix Model.

Within these pages, we provide information on tools and methods that we use for large-scale land and water planning in the boreal region of North America, including:

- R/Shiny Apps 
- R Functions
- Software
- Methods
- Publications
 <br>
 
## Shiny Apps

| Geopackage Creator | Disturbance Explorer | Hydrology Explorer |
| :---: | :---: | :---: |
|<a href="https://beaconsproject.shinyapps.io/geopackage_creator/" target="_blank"><img align="center" src="pics/geopackage_creator.png" width="250"></a> | <a href="https://beaconsproject.shinyapps.io/disturbance_explorer/" target="_blank"><img align="center" src="pics/disturbance_explorer.png" width="250"></a> | <a href="https://beaconsproject.shinyapps.io/hydrology_explorer_v3/" target="_blank"><img align="center" src="pics/hydrology_explorer.png" width="250"></a> |

| Disturbance Validation | Wolverine Survey Design |
| :---: | :---: | 
| <a href="https://beaconsproject.shinyapps.io/disturbance_validation/" target="_blank"><img align="center" src="pics/disturbance_validation.png" width="250"></a> | <a href="https://beaconsproject.shinyapps.io/wolverines/" target="_blank"><img align="center" src="pics/wolverines_survey.png" width="250"></a> |
<br>

We have additional Shiny Apps under-development: 
- **KBA or Conservation Area Explorer**: This app designs new conservation areas and evaluates and designs conservation area networks based on new and/or existing conservation areas. Functions include evaluation of intactness, size, hydrologic connectivity, upstream areas, and representation.
- **Movement Mapper** and **Movement Explorer**: These apps use animal location data to identify areas of annual & seasonal use and migration pathways. 
<br>

## R Functions

We will soon release a suite of R Tools that includes the following function categories: 
- **Builder** functions generate the inputs used by Builder (see below - Software). 
- **Hydrology** functions calculate the Dendritic Connectivity Index ([Cote et al. 2009](https://link.springer.com/article/10.1007/s10980-008-9283-y)) for an area of interest (AOI) and identify areas upstream and downstream of an AOI (e.g., conservation area, mine site, etc.) using the BEACONs catchment dataset(s).
- **Representation** functions support assessment of representation based on targets and dissimilarity metrics (i.e., Bray-Curtis and Kolmogorov-Smirnoff).
- **Spatial** functions support tasks such as data preparation, spatial overlay, geometric processing, and summarization of spatial attributes.
<br>

## Software

**Builder** is a user-friendly software application developed in C# .NET framework that assembles catchments using hydrology-based rules to identify conservation areas based on hydrologic connectivity, intactness, and size. If this software is of interest, please email beacons[at]ualberta.ca.
<br><br>

## QGIS Plugins

We will soon release a QGIS plugin and tutorial for creating a catchment dataset with stream flow attributes that work with BEACONs' Builder software and Shiny Apps (e.g., Hydrology Explorer).
<br><br>

## Methods

| Disturbance Mapping |
| :---: |
| <a href="https://github.com/beaconsproject/disturbance_mapping"><img align="center" src="pics/disturbance_mapping.png" width="250"></a> | 
<br>

## Completed Projects

- [Candidate Benchmark Networks for the Northwest Boreal Region](https://github.com/beaconsproject/nwb)
- [SFI conservation value assessment tool](https://borealbirds.ca/conservation-value-assessment-tool/)
<br>

## Publications (supporting material)

- [Insect paper](https://github.com/beaconsproject/insect-mdr-simulation)
- [Intactness paper](https://github.com/prvernier/intactness)
<br>

## Presentations

Wolverines app (Jan 2023)

- [Powerpoint presentation](https://drive.google.com/file/d/15REnFhUNNPtEkyuAeVzRciYvhtz50ZDP/view)
- [App demo](https://www.youtube.com/watch?v=fgQ3PaJIXsg)

BC PARF Forum 2022 (Dec 2022)

- [Regional Disturbance Mapping in SE Yukon and Applications to Conservation Planning](https://cpcil.ca/bcparf-2022-concurrent-conservation-case-studies/)
- [Applications of Disturbance Mapping to Conservation Planning](https://cpcil.ca/bcparf-2022-concurrent-conservation-case-studies/)
