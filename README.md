# Exercise 1: Fix Average Moon Gravity

![Screenshot_1](https://github.com/yashdesai01/FixAverageMoonGravity/assets/25559641/dbe119b1-cfcf-44ca-aba9-2d38314be180)

# Exercise 2: Alternative Solution

## Proposed Solution
Pre-fetch and cache all moon data with their gravity values once at the start, and use this cached data to calculate the average moon gravity for each planet.

## Benefit
Reduces the number of API calls during execution, improving performance and reducing latency.

## Drawback
Increases initial load time and memory usage due to caching all moon data at the start, which may not be efficient for very large datasets.
