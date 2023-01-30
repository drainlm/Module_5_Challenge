# READ ME: Pymaceuticals - Capomulin 

This code uses data gathered from a Pymaceuticals, Inc. mouse tumor study stored in two csv files (Mouse_metadata and Study_results) to perform statistical analysis and generate summary statistics and data visualizations (bar graph, pie chart, box plot, line graph, scatter plot, and linear regression).

MatPlotLib, pandas, and scipy.stats are used throughout. Both csv files are combined into one dataset and duplicates are removed. The mean, median, variance, standard deviation, and standard error of the mean for the tumor volume are collected and placed into a summary statistics table using the groupby method and then the aggregation method.

A bar chart for the total number of timepoints for all mice tested for each drug regimen is created using pandas and then using pyplot. A pie chart is then created showing the distribution of female vs male mice using pandas and then pyplot.

Another dataframe is created for the final tumor volume of each mouse across four treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin). The data is looped through to calculate the quartiles and IQR and an upper and lower bound is used to determine outliers. A box plot is then created for the final tumor volume distribution for each treatment.

A line graph is created to plot the tumor volume vs time point for a mouse treated with Capomulin. A scatter plot is generated for the average tumor volume vs mouse weight for Capomulin regimen, as well as a linear regression model. The correlation coefficient for this is also calculated.
