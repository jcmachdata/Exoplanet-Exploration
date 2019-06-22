# Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

Machine learning models were created to classify candidate exoplanets from the raw dataset.

- - -
### Results

* A KNN classifier was tried, but it only yielded an accuracy of 66.1%

* Much better success was found using SVM. Initially, various combinations of X values were tried, but the highest accuracy achieved was 61.4%.

* Next, all available X values were tried, including the error values. With a linear kernal, we obtained a testing accuracy of 88.8%. Other kernals were attempted but none of them could beat the linear model.
