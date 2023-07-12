# Jupyter Tutorial for the RSS Radiance Collection

This is a collection of microwave radiometer measurements and useful ancillary data.  The goal of the collection is to make it easier for the community to develop and use algorithms based on microwave radiance measurements in their own research.

The creation of this data collection was funded by the ACCESS-2019 NASA program.  One of the elements of that program was to develop training for machine learning (ML) algorithms.  The product that we produced and is the subject of this tutorial is not a single training dataset, but rather a *toolkit* to facilitate other researchers to easily and accurately develop training datasets for their specific applications.  Because the microwave radiances included are sensitive to both surface and atmospheric conditions, what might be considered a "label" for one researchers project might be considered confounding noise or and input variable for another project.

The example below are just that, an example, of what one could do with the data collection.

### Tutorial Organization
ACCESS_tutorial.ipynb

1. Simple download of single variables, subsetting and plotting.
2. Download of multiple variables
3. Construction of an example ML training dataset
4. Example of using the training dataset to train a simple regression algorithm for to retrieve surface temperature. (We do not expect a simple regression to perform very well) 