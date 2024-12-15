# Seaborn basics

seaborn is a python library used to visualize the data on graphs. It's build on top of matplotlib with many extended features to visualize the complex queries.

## Types
there are 3 types of data we can solve using seaborn
- Distributional 
- Categorical
- Matrix

## Distributional Plotting
distribtuion plotting is done because to find the trend of the datapoints of the dataset by using its various techniques likes - [skewness, (mean, median, mode), ...] etc.


### Hist, Joint, KDE, Pair, Rug

- histplot
histplot is a technique to plot the histogram using rectangular bars, where the height of bar represents the frequency of each bar. It key parameters are- bins and kde

- jointplot
jointplot is a technique to compare the 2 dataframes of same dataset on x and y axis, on both scatterplot and marginal histograms. Its key parameters are- kind, hue, palette.

- kdeplot
kdeplot is a technique which draw the smooth curve that represents the distribution on the basis of datapoints, which tells us that where the data is more concentrated. Its key parameters are- shade, kernel, color.

- pairplot
pairplot is a technique where we visualize the comparision between each individual column of the dataset with each other in form of scatter plot and for the same column we get the histogram plot. That help us to identify the relation between 2 columns faster than any other method.

- rugplot
rugplot is a technique where we visualize the datapoints on graph using sticks, and where ever the most points are situated the the trends goes that side.


