
[![DOI](https://sandbox.zenodo.org/badge/598627946.svg)](https://sandbox.zenodo.org/doi/10.5072/zenodo.72712)

# Hydrological drought connectedness (HDC)
'HDC' is a GitHub repository that contains instructions to reproduce results from the "Spatially Compounding Drought Events in Brazil" which is under review in the Water Resources Research journal.

## Code reference
Gesualdo, G. C. & Benso, M. Hydrological drought connectedness (HDC). 2024. Zenodo. https://doi.org/10.5072/zenodo.72713

## Data references
### Input data
|       Dataset       |               Repository Link                |               DOI                |
|:-------------------:|:--------------------------------------------:|:--------------------------------:|
|  Original dataset - CABra             | [Link](https://zenodo.org/records/7612350)         | [https://doi.org/10.5281/zenodo.7612350 ](https://doi.org/10.5281/zenodo.7612350)|
|  Modify input data            |   [Link](https://sandbox.zenodo.org/records/73481)       | https://doi.org/10.5072/zenodo.73481|

### Output data
The output from hydrological drought extraction and connectedness are stored in the data repository linked below.

|       Dataset       |                                Repository Link                                |                   DOI                   |
|:-------------------:|:-----------------------------------------------------------------------------:|:---------------------------------------:|
|Hydrological drought extraction    |  [Link](https://sandbox.zenodo.org/doi/10.5072/zenodo.72712)| [https://doi.org/10.5072/zenodo.72712](https://doi.org/10.5072/zenodo.72712)|
|Hydrological drought connectedness | [link](https://sandbox.zenodo.org/doi/10.5072/zenodo.72712) | [https://doi.org/10.5072/zenodo.72712](https://doi.org/10.5072/zenodo.72712) |


## Reproduce my experiment
Clone this repository to get access to the notebooks used for Hydrological Drought Extraction and Connectedness. You'll also need to download the input files in [link](https://sandbox.zenodo.org/records/73481). Once you have the input dataset downloaded you can use the following notebooks to reproduce the analysis. For the Hydrological Drought Extraction, you should adjust the function variables <em>moving_window</em> in number of days, <em>thresh_value</em> in flow percentile and <em>min_dur</em>, the drought minimal duration in days.  

|                Script Name                 |                                Description                                 |
|:------------------------------------------:|:--------------------------------------------------------------------------:|
|Hydrological_drought_extraction.ipynb | Runs the hydrological drought extraction for each catchment                |
|Hydrological_drought_connectedness.ipynb    | Compute the hydrological drought connectedness                             |
