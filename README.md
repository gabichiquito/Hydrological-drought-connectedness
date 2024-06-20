
[![DOI](https://sandbox.zenodo.org/badge/598627946.svg)](https://sandbox.zenodo.org/doi/10.5072/zenodo.72712)

# Hydrological drought connectedness (HDC)
'HDC' is a GitHub repository that contains instructions to reproduce results from the "Spatially Compounding Drought Events in Brazil" which is under review in the Water Resources Research journal.

## Code reference
Gesualdo, G. C. Hydrological drought connectedness (HDC). 2024. Zenodo. https://doi.org/10.5072/zenodo.72713

## Data references
### Input data
|       Dataset       |               Repository Link                |               DOI                |
|:-------------------:|:--------------------------------------------:|:--------------------------------:|
|   Cabra             | https://data.msdlive.org/records/43sy2-n8y47 | https://doi.org/10.57931/1989373 |

### Output data
The output from hydrological drought extraction and connectedness are stored in the data repository linked below. The post-processed files (resulting from the analysis scripts itemized below) are stored in the /data directory in this meta-repository.

|       Dataset       |                                Repository Link                                |                   DOI                   |
|:-------------------:|:-----------------------------------------------------------------------------:|:---------------------------------------:|
|Hydrological drought extraction    |  Link| https://doi.org/|
|Hydrological drought connectedness | link | https://doi.org |


## Reproduce my experiment
Clone this repository to get access to the notebooks used for Hydrological Drought Extraction and Connectedness. You'll also need to download the input files in <Put the path here>. Once you have the input dataset downloaded you can use the following notebooks to reproduce the analysis. For the Hydrological Drought Extraction, you should adjust the <put the name>. 

|                Script Name                 |                                Description                                 |
|:------------------------------------------:|:--------------------------------------------------------------------------:|
|Hydrological_drought_extraction.ipynb | Runs the hydrological drought extraction for each catchment                |
|Hydrological_drought_connectedness.ipynb    | Compute the hydrological drought connectedness                             |
