* An accelerometer in a mobile phone is a sensor that detects changes in velocity and orientation, allowing the device to understand the users movement and position.
* The movement patterns of a person who is drunk differ from those of a sober individual, and these patterns can be analyzed using ML algorithms applied to accelerometer data from a person's smartphone to determine their level of sobriety.
* A dataset consisting of a person's accelerometer and blood alcohol level readings sampled continiously can be used to build a ML classifer.
* The data points are divided into 60 second windows and higher order features are derived by calculating the mean, median, variance, minimum, maximum, RMS, skew, kurtosis and FFT variance in each time window. This process is implemented in "Data cleansing and feature extraction.ipynb" notebook and the cleaned data is stored in "clean_data.csv".
* A random forest classifier was trained and it was able to predict drunkenness with 83% accuracy.

# Dataset
Bar Crawl: Detecting Heavy Drinking. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C5TK6G.
