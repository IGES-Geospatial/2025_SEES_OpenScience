# 2025 SEES Open Science

## Project overview
Here is a top-level description of the project and its purpose: A sample repository for demonstrating Zenodo usage for SEES2025. (Your overview will need to be more detailed)

## Description of repository files
There are 3 notebooks in the notebooks directory:
* notebooks/GLOBE_API_DownloadData.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IGES-Geospatial/2025_SEES_OpenScience/blob/main/notebooks/GLOBE_API_DownloadData.ipynb)  
    * Queries the GLOBE API for JSON Land Cover data and saves it as a csv in the input_data directory
* notebooks/GLOBE_DownloadImages.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IGES-Geospatial/2025_SEES_OpenScience/blob/main/notebooks/GLOBE_DownloadImages.ipynb)  
    * Uses the csv generated above to download thumbnails of the "downward" photos captured by the SEES2025 team and saves the thumbnails to input_data/downloaded_photos
* notebooks/Process_Images.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IGES-Geospatial/2025_SEES_OpenScience/blob/main/notebooks/Process_Images.ipynb)  
    * Averages the images stored in input_data/downloaded_photos and saves as an image in output_data 

## Steps to reproduce results
    1. Run GLOBE_API_DownloadData.ipynb 
    2. Run GLOBE_DownloadImages.ipynb
    3. Process_Images.ipynb

## Citations and Acknowledgments
Citation:
Global Learning and Observations to Benefit the Environment (GLOBE) Program, 2025-07-12, https://www.globe.gov/globe-data.

Acknowledgments:
These data were obtained from NASA and the GLOBE Program and are freely available for use in research, publications and commercial applications.

