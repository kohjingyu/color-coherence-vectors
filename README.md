# Image Classification with Color Coherence Vectors

In this assignment for 51.504 Graduate Machine Learning, I attempt image classification on a very limited dataset of CIFAR-10 images using color coherence vectors.

For more information about CCV, please reference the [original paper](https://www.cs.cornell.edu/~rdz/Papers/PZM-MM96.pdf) by Pass et. al.

## Files

**ccv.ipynb** contains a Jupyter notebook documenting my implementation of CCV, and some results on a very small subset of CIFAR-10. I use different methods for this, including: logistic regression for binary classification, k-Nearest Neighobrs, and multi class logistic regression.

**report.pdf** is a writeup of some of my findings and my answers for the class assignment.

## Implementation

This implementation of CCV makes use of the numpy histogram function for color discretization. This could also be done using a k-Means clustering approach.

In order to determine coherence of a particular color, I implemented a naive function for finding fully connected subgraphs of the same pixel colors. This implementation is quite inefficient and there are definitely better ways to implement it.

## Acknowledgements

Thank you to the authors of CCV for presenting a comprehensive description of the algorithm.

