# LandCoverClassification_Dataset
# EthiopiaLandCoverClassification

This repository contains a comprehensive dataset for Land Use and Land Cover (LULC) classification across Ethiopia, designed for researchers and practitioners in remote sensing and environmental studies. The dataset includes annotated satellite images and corresponding masks, categorized into multiple land cover classes.

## Dataset Overview

- **Classes:** 8 Land Cover Types
  - Forest
  - Grassland
  - Agricultural Land
  - Road
  - Water Bodies
  - Shrubland
  - Built-up
  - Others

- **Image Format:** JPEG
- **Mask Format:** PNG
- **Resolution:** 1 meter, 10 meters, 30 meters
- **Number of Samples:** [Total Number of Samples]

## Data Sources

The data utilized in this study were collected from various regions throughout Ethiopia, incorporating satellite imagery with a range of resolutions to suit different analytical needs:
- **High-Resolution Images:** Sourced from the Terraincognita app, providing aerial photographs and satellite images with a resolution of 1 meter \cite{Terraincognita}.
- **Multi-Spectral Data:** Integrated from Landsat 8 and Landsat 9, offering imagery at a spatial resolution of 30 meters \cite{landsat}.
- **Sentinel 2 Imagery:** Delivering images with a 10-meter resolution across multiple bands \cite{sentinel}.

Each selected image was carefully chosen to accommodate different zoom levels, ensuring alignment with the specific resolution requirements necessary for satellite image analysis across Ethiopia's diverse landscapes.

## Data Structure

The dataset is organized as follows:

EthiopiaLandCoverClassification/ ├── images/ │ ├── image1.jpg│ ├── image2.jpg│ └── ... └── masks/ ├── mask1.png├── mask2.png└── ...
## Usage
Downloading the Dataset
To download the dataset, clone the repository:
https://github.com/Elelanfik/LandCoverClassification_Dataset
## Citation
If you use this dataset in your research, please cite the following paper:
