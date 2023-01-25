# Solving TSP with Self-Organizing Maps

This study aims to explore the performance of Self-Organizing Maps algorithm in solving Traveling Salesman Problem by implementing it with two different neigborhood functions:

1. Gaussian Kernel
2. Elastic Band

The algorithms have been run on the data set that includes the coordinates of Turkish provinces. The seventh trial (M = 3n, 100 iterations) yields the optimal solution for TSP with Turkish provinces.

**Note:** The code chunk "run" runs excessively slow. Thus, you can load pre-calculated variables and data frames from "Enivronment - Solving TSP with Self Organizing Maps.RData". Just place the RData file in your working directory and run the following code to skip that part:

``` r
load("Environment - Solving TSP with Self Organizing Maps.RData")
```

Feel free to make suggestions on performance :-)
