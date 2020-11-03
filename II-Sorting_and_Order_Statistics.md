---
title: Sorting and Order Statistics
permalink: /II-sorting
---
# II - Sorting

## Heapsort

## Quicksort

## Practical Sorting Algorithms

- Lammich [[IJCAR20]](https://link.springer.com/chapter/10.1007%2F978-3-030-51054-1_18) verified a high-level assembly-languar (LLVM) implementation of two sorting algorithms: introsort (a combination of quicksort, heapsort and insertion sort) from the GNU c++ library (libstdc++) and pdqsort, an extension of introsort from the Boost C++ Libraries. The verified implementations perform on par with the originals.

- The sorting algorithm TimSort (combining mergesort and insertion sort) is the default implementation for generic arrays and collections in the Java stan-
dard library. De Gouw et al. [[CAV15]](https://link.springer.com/chapter/10.1007%2F978-3-319-21690-4_16) first discovered a bug that can lead to an
ArrayIndexOutOfBoundsException and suggested corrections. Then De Gouw et al. [[JAR19]](https://link.springer.com/article/10.1007/s10817-017-9426-4) verified termination and exception freedom (but not full functional
correctness) of the actual corrected code using KeY.

## Sorting in Linear Time

## Medians and Order Statistics




