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


### Categorical Plotting

#### Bar, Count, Violin, Strip, Swarm, Box

- bar plot
bar plot is a technique where the histogram bar is plotted on the basis of the category adn the height of the bar is the frequency of the category.

- count plot
count plot is also a similar technique to bar plot which display the histogram plot on the graph as per the frequency of the particular category.

- violin plot
violin plot is a technique where the datapoints are draw on the graph by categorical and kdeplot (both way) format. As the more dense or concentrated area considered as trend nature.

- strip plot
strip plot is a technique where the datapoints are plotted like scatter but they tend to overlap each other.

- swarm plot
swarm plot is a similar technique like stripplot and the main difference that differentiate both of them is that the datapoints in swarm plot does not overlap each other.

- box plot
box plot is a technique to statistically summerize about the dataset by identifing the median, IQR, skewnees, outliers of the datapoints, where as the violin plot is more detailed version of it!.


### Matrix Plotting

### Heatmaps, cluster map, pair grid, facet grid, regression plots

- heatmaps
heatmap is a technique where we visualize the datapoints by converting them into numerical value and then use the color intensity to represents the values. Its key parameters are- annot, cmap

- cluster map
cluster map is a type of heatmap that perform hierarchical clustering, where the pattern reveals based on the similarity.

- pair grid
pair grid is a pair plot type technique that goes beyond the pairplot and provide the more customization to the analyst.

- facet grid
facet grid is a technique that know for the low level customization, and use multiple subset of the same dataset to find the relationship between these variables.

- regression plots
regression plot is a technique where we plot the datapoints on to the graph and check if the datapoints and find relationship between two continuous variablesis on the best fit line or not.
