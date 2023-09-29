# Kernel-Density-Function-Project

Generally we use parametric statistics when analyzing data. These use strong assumptions about the distribution of the population from which the sample was drawn (just like assuming it has a normal distribution) but sometimes we have no clue on what a good parametric model could be used in each case.
Nonparametric statistics are not based on such assumptions, which means that the data collected from a sample does not follow a specific distribution. Here we try to be as general as possible by estimating its unknown density function. 
Densities are easy to visualize and interpret, making them ideal tools for exploring continuous random variable data. They provide immediate graphical information on the shape of the data. One of the most popular density estimators is the Kernel Density Estimator (KDE). 
The KDE is calculated by weighting the distances of all data points. If we see more points in one location, the estimate is higher giving the probability of seeing a point at that location.
Histograms are also a very used density estimator, but we need to specify an origin x0 while for the KDE that is not needed.
