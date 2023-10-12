# How to make a heat map? Kernel-Density-Function project

As a fan of football I tend to see heat maps all the time, specifically about the players position on the field. What about the penalties? Where do they aim the most to score when in front of the goal 11 meters away? The goal of the analysis is to see to which side of the goal line players shoot the most.
For this we would think to use a density distribution function to know with a certain probability where the players shoot but here we do not have a defined density function. We simply do not know how the distribution of the location of where the players shoot is.
I used the Kernel Density Function to be able to create a heat map to know where the players tend to shoot the most when taking a penalty in the italian league. I gathered data from the Serie A of Italian football of the season 2020/2021 to answer this question.

Generally we use parametric statistics when analyzing data. These use strong assumptions about the distribution of the population from which the sample was drawn (just like assuming it has a normal distribution) but sometimes we have no clue on what a good parametric model could be used in each case.
Nonparametric statistics are not based on such assumptions, which means that the data collected from a sample does not follow a specific distribution. Here we try to be as general as possible by estimating its unknown density function. 
Densities are easy to visualize and interpret, making them ideal tools for exploring continuous random variable data. They provide immediate graphical information on the shape of the data. One of the most popular density estimators is the Kernel Density Estimator (KDE). 

The KDE is calculated by weighting the distances of all data points. If we see more points in one location, the estimate is higher giving the probability of seeing a point at that location.
Histograms are also a very used density estimator, but we need to specify an origin x0 while for the KDE that is not needed.
