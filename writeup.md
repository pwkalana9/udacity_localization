# Self Driving Car Localization

## Passing criteria
Drive the simulated car with LIDAR scanning while localizing with maximum 1.2 m error (with respect to the ground truth) at least 170 m.

## ICP Approach
Passed results were achieved when iterations = 30, leaf size = 1, max correspondance distance = 2.0.

![ICP result](resources/icp_iterations_30_leaf_size_1_passed.png)

## NDT Approach
Passed results were achieved when iterations = 100, leaf size = 1, resolution = 5.

![NDT result](resources/ndt_iterations_100_leaf_size_1_resolution_5_passed.png)

