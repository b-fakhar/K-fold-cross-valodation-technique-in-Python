# ODS Medical Inc. - Programming Assignment

### Objective
- Write K-fold cross valodation technique in Python.

#### Conditions
- Every element from the sample should be used exactly once in testing sets.
- Every element from the sample should be used at least once in training sets.
- The sizes of the pairs of testing sets may differ by no more than 1.

#### Inputs
- An array of integers indices, which contains the indices of elements in data sample.
- An integer K which, refers to the number of folds.

#### Output
- An array that contains the arrays of folds.

#### Assumptions
- N is an integer within the range [2, ..., 100]
- K is an integer within the range [2, ..., N]
- Each element of array indices is an integer within the range [0, ..., 100,000]
- The elements of indices are all distinct.
