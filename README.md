
[![DOI](https://sandbox.zenodo.org/badge/DOI/10.5072/zenodo.78438.svg)](https://handle.stage.datacite.org/10.5072/zenodo.78438)

# Hydrological drought connectedness (HDC)
'HDC' is a GitHub repository that contains instructions to reproduce results from the "Spatially Compounding Drought Events in Brazil" which is under review in the Water Resources Research journal.

## Code reference
Gesualdo, G. C. & Benso, M. Hydrological drought connectedness (HDC). 2024. Zenodo. https://doi.org/10.5072/zenodo.72713

## Data references
### Input data
|       Dataset       |               Repository Link                |               DOI                |
|:-------------------:|:--------------------------------------------:|:--------------------------------:|
|  Original dataset - CABra             | [Link](https://zenodo.org/records/7612350)         | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7612350.svg)](https://doi.org/10.5281/zenodo.7612350)|
|  Modify input data            |   [Link](https://sandbox.zenodo.org/records/78423)       | [![DOI](https://sandbox.zenodo.org/badge/DOI/10.5072/zenodo.78423.svg)](https://handle.stage.datacite.org/10.5072/zenodo.78423)|

### Output data
The output from hydrological drought extraction and connectedness are stored in the data repository linked below.

|       Dataset       |                                Repository Link                                |                   DOI                   |
|:-------------------:|:-----------------------------------------------------------------------------:|:---------------------------------------:|
|Hydrological drought extraction    |  [Link](https://sandbox.zenodo.org/records/78423)|[![DOI](https://sandbox.zenodo.org/badge/DOI/10.5072/zenodo.78423.svg)](https://handle.stage.datacite.org/10.5072/zenodo.78423)|
|Hydrological drought connectedness | [Link](https://sandbox.zenodo.org/records/78423)|[![DOI](https://sandbox.zenodo.org/badge/DOI/10.5072/zenodo.78423.svg)](https://handle.stage.datacite.org/10.5072/zenodo.78423)|


## Reproduce our experiment
Clone this repository to get access to the notebooks used for Hydrological Drought Extraction and Connectedness. You'll also need to download the input files in [link](https://sandbox.zenodo.org/records/78423). Once you have the input dataset downloaded you can use the following notebooks to reproduce the analysis. For the Hydrological Drought Extraction, you should adjust the function variables <em>moving_window</em> in number of days, <em>thresh_value</em> in flow percentile and <em>min_dur</em>, the drought minimal duration in days.  

|                Script Name                 |                                Description                                 |
|:------------------------------------------:|:--------------------------------------------------------------------------:|
|Hydrological_drought_extraction.ipynb | Runs the hydrological drought extraction for each catchment                |
|Hydrological_drought_connectedness.ipynb    | Compute the hydrological drought connectedness                             |

## Reproduce our figures
To reproduce the figures from our publication, use the following notebooks. Download the necessary input files from [link](https://sandbox.zenodo.org/records/78423)

| Figure Name |                Script Name                 |                                  Description                                   | 
|:--------------:|:------------------------------------------:|:------------------------------------------------------------------------------:|
| Heatmap of Spearman's correlation  |PLOT_drought_spearmans_heatmap.ipynb | Reproduce the Heatmap of Spearman's correlation between drought characteristics and different catchment attributes|
| Spatial distribution of drought characteristics  |PLOT_Hydrological_drought_characteristics.ipynb | Reproduce the maps for spatial distribution for each drought characteristics|
| Drought co-occurrence network  | PLOT_Hydrological_drought_co-occurrence_Network.ipynb | Reproduce the map of the co-occurrence network. The lines represent drought connectedness between catchments, and the catchment nodes are colored according to the mean number of connected events a catchment experiences per year|
| Drought similarity clusters  | PLOT_Hydrological_drought_cluster.ipynb | Reproduce the map of drought similarity cluster, based on the hierarchical clustering|
| Catchment attribute variability  |PLOT_Hydrological_drought_cluster_attributes.ipynb | Reproduce the boxplot of drought and catchment attribute variability across drought similarity clusters|



