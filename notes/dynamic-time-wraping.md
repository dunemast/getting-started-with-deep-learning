# Dynamic Time Wraping (DTW)

## Introduction

Dynamic time wraping is often use to measure the similarity between the two time series. It gives us a robust dissimilarity score where a lower number means that the series are similar. Often used in comparing the speech or stock data.

- The time series can be of different lengths.

- It can compare the similarity between the two series with the help of one-to-many or many-to-one mapping between the points.

- Can be used for pattern matching or anomaly detection.

## Restriction and Rules

In general, DTW is a method that calculates an optimal match between two given sequences (e.g. time series) with certain restriction and rules:
[1]

- Every index from the first sequence must be matched with one or more indices from the other sequence, and vice versa
- The first index from the first sequence must be matched with the first index from the other sequence (but it does not have to be its only match)
- The last index from the first sequence must be matched with the last index from the other sequence (but it does not have to be its only match)
- The mapping of the indices from the first sequence to indices from the other sequence must be monotonically increasing, and vice versa, i.e. if $j > i$ are indices from the first sequence, then there must not be two indices $l > k$ in the other sequence, such that index i is matched with index l and index j is matched with index k, and vice versa.

[1] Dynamic time wraping, [https://en.wikipedia.org/wiki/Dynamic_time_warping](https://en.wikipedia.org/wiki/Dynamic_time_warping)

## Visual comparision with Euclidian distance

![dtw-vs-euclidian](https://upload.wikimedia.org/wikipedia/commons/6/69/Euclidean_vs_DTW.jpg)


## Implementations

 - `DTW python`, [https://pypi.org/project/dtw-python/](https://pypi.org/project/dtw-python/)

 - `DTW julia`, [https://github.com/baggepinnen/DynamicAxisWarping.jl](https://github.com/baggepinnen/DynamicAxisWarping.jl)
