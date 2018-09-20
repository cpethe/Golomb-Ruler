# Golomb-Ruler

## Problem Statement:

A Golomb Ruler of order M and length L consists of M marks placed at unit intervals (i.e. integer positions)
along an imaginary ruler such that the differences in spacing between every pair of marks are all distinct, i.e. no
two pairs of marks are the same distance apart. The number of marks on the ruler is its order, and the largest
distance between two of its marks is its length.
For example the four marks placed at 0, 1, 4 and 6 constitutes a Golomb ruler of order 4 and length 6.
Implement a CSP solution to verify whether or not a Golomb ruler of a fixed length L for M marks exists.
If a solution exists for length L find an optimal length ruler, that is one for which no shorter length ruler exists for
M marks.

## Two solutions have been implemented:

1. Plain Backtracking (BT)
2. Backtracking + Forward Checking (FC)
