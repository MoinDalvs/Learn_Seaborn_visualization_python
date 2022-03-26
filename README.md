# Learn_Seaborn_visualization_python
## Seaborn Datasets
### Seaborn Color Palette
### Customizing Seaborn
### Categorical Plot
+ bar plot
+ Horizontal Barplot
### Create count plot with region on the y-axis
###  Boxplot
+ A box plot allows you to compare different variables
+ The box shows the quartiles of the data. 
+ The bar in the middle is the median and the box extends 1 standard deviation from the median
+ The whiskers extend to all the other data aside from the points that are considered to be outliers
### Strip Plot
### Swarm Plot
### Violin Plot
## Input Data: Univariate (1D Series)
### Distribution Plots
+ distribution plot
+ Provides a way to look at a univariate distribution.
+ A univeriate distribution provides a distribution for one variable
+ Kernal Density Estimation with a Histogram is provided
+ kde=False removes the KDE
+ Bins define how many buckets to divide the data up into between intervals
+ For example put all profits between 10 and 20$ in this bucket
###  ecdf Plot
### Rug Plot
### Styling
## Relational Plots
+ Scatter Plot
+ Line Plot
### Matrix Plots
+ Pairplots
+ Pair Plot plots relationships across the entire data frames numerical values
+ With hue you can pass in a categorical column and the charts will be colorized
+ You can use color maps from Matplotlib to define what colors to use
+ sns.pairplot(tips_df, hue='sex', palette='Blues')
### HeatMap
