**A comprehensive Python framework for processing ISRO IIRS (Indian Institute of Remote Sensing) satellite data using both traditional remote sensing techniques and machine learning approaches.**

The workflow includes the following key components:

**1.Data Loading and Management**

* Support for different IIRS sensors (LISS-3, LISS-4, AWiFS)
* Automated detection of available imagery


**2.Preprocessing Pipeline**

* Radiometric calibration
* Atmospheric correction using Dark Object Subtraction
* Cloud masking


**3.Spectral Analysis**

* Calculation of multiple vegetation indices (NDVI, EVI, SAVI)
* Moisture and burn indices (NDMI, NBR) for applicable sensors


**4.Machine Learning Integration**

* Image segmentation using K-means clustering
* Land cover classification with Random Forest
* Support for both supervised and unsupervised classification


**5.Change Detection**

* Analysis of temporal changes between image pairs
* Quantification and visualization of vegetation changes


**6.Visualization and Export**

* Generation of RGB composites
* Visualization of indices and classification maps
* Export of results as GeoTIFF files
