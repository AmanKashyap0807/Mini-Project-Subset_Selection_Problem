
# Subset Selection Problem


## Problem Description

Find all the subsets from a set of numbers whose sum is zero.
Constraint: Subset size must be 5  
Set={-12, -3, -6, 7, 2, -2, 6, 3, 9, -7, -5, -8, 1, 11, -9, -4}

Find all the subsets from a set of numbers whose sum is zero.
Constraint: Subset size must be 3 to 6 only  
Set={-12, -3, -6, 7, 2, -2, 6, 3, 9, -7, -5, -8, 1, 11, -9, -4}

## Approch

![App Screenshot](https://user-images.githubusercontent.com/7460892/173567150-e42f9d90-456e-4732-b30c-5820dd8bd55f.png)


## Technology used

- Python
- random library
- set




## Detailed Solution Description

We have used python's random library for generating different samples of certain size then by using sum operator calculated its sum and when its equal to 0 then add it to result. iterating these step 1000 times in loop provide us all possible subset with element sum equal to 0.

