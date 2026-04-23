# Fractal-of-SRW_Raw-Data

Raw numerical data for the fractal analysis of clusters formed by two-dimensional simple random walks (SRW). This dataset supports the findings on the scaling behavior of cluster mass, hull perimeter, and chemical distance.

## Overview

A two-dimensional simple random walk generates a cluster of visited sites. The cluster exhibits non-trivial fractal geometry. We investigate three fundamental geometric properties and their scaling relations with system size $L$.

## Scaling Relations

### Cluster Mass
The total number of occupied sites (mass) in the cluster scales as

$$M = \frac{L^2}{1 + \ln L}\left[\frac{\pi}{2} - \left(\frac{\pi}{2}\ln L\right)^{-2}\right]$$

### Hull Perimeter
The perimeter (hull) of the cluster follows

$$\mathcal{L}_h \sim L^{4/3}$$

where $\mathcal{L}_h$ denotes the hull length and $L$ is the system size.

### Chemical Distance
The chemical distance — the shortest path length spanning the cluster from a seed $s_0$— scales as

$$S \sim L (\ln L)^{1/4}$$

## Data Files

| File | Symbol | Description |
|------|--------|-------------|
| `mass_M.dat` | $M$ | Cluster mass as a function of system size $L$ |
| `hull_L.dat` | $\mathcal{L}_h$ | Hull perimeter length as a function of system size $L$ |
| `chemical_S.dat` | $S$ | Chemical distance as a function of system size $L$ |

Each file contains columns: system size $L$, mean value, and statistical error.
