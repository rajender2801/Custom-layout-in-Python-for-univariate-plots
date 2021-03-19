Using this snippet, one can have custom layout (desired number of subplots in row-column format) in Python.

### For e.g. if there are 10 features of the dataframe which the user would like to plot as histograms, then the command

add_plots(df, 2, 2, "Histogram distribution") 

### will create 3 figure windows in total and each window contains subplots of 4,4,2 in each window.

### If the user executes

add_plots(df, 2, 3, "Histogram distribution")

### it will create 2 figure windows in total and each window contains subplots of 6,4 in each window.

The inputs the user has to provide are 4
1. The data frame whose data is to be plotted
2. Column-wise number of subplots
3. Row-wise number of subplots
4. Which type of plot (Histogram/Boxplot/Scatterplot)
