---
title: PRML-ch1-Introduction
author: xyq
date: '2021-06-16'
slug: prml-ch1-introduction
categories:
  - PRML
tags:
  - PRML
disable_comments: yes
---
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>

take-home message：

`$x^j$` denotes x raised to the power of j

## 0. 数学符号的约定

Vectors are denoted by lower case bold Roman letters such as
`$x$`, and all vectors are assumed to be column vectors. A superscript T denotes the
transpose of a matrix or vector, so that `$x^T$` will be a row vector. Uppercase bold
roman letters, such as `$\mathbf{M}$`, denote matrices. The notation `$(w_1, . . . , w_M)$` denotes a
row vector with M elements, while the corresponding column vector is written as `$w = (w_1, . . . , w_M)^T$`

If we have N values `$x_1, . . . , x_N$` of a D-dimensional vector `$x = (x_1, . . . , x_D)^T$`,
we can combine the observations into a data matrix `$\mathbf{X}$` in which the n-th row of `$\mathbf{X}$`
corresponds to the row vector `$x^T_n$`. Thus the n, i element of `$\mathbf{X}$` corresponds to the
ith element of the nth observation `x_n`. 

For the case of one-dimensional variables we
shall denote such a matrix by `$\mathsf{x}$`, which is a column vector whose nth element is `$x_n$`.
Note that `$\mathsf{x}$` (which has dimensionality N) uses a different typeface to distinguish it
from x (which has dimensionality D).

## 1. Introduction

term 收集

|1 |2 |3 |4 |
|:---|:---|:---|:---|
|training set|training set|training set|training set|

- training set
- target vector 
- test set
- generalization
- feature extraction
- supervised learning
- classification
- regression
- unsupervised learning
- clustering
- density estimation
- visualization
- reinforcement learning
  - A general feature of re- inforcement learning is the trade-off between exploration, in which the system tries out new kinds of actions to see how effective they are, and exploitation, in which the system makes use of actions that are known to yield a high reward.
- credit assignment
- M is the order of the polynomial
- linear models
- error function
- model comparison or model selection
- over-fitting
- maximum likelihood


## 1.1. Example: Polynomial Curve Fitting

as M increases, the magnitude of the coefficients typically gets larger.

for a given model complexity, the over-fitting problem become less severe as the size of the data set increases.

the number of data points should be no less than some multiple (say 5 or 10) of the number of adaptive parameters in the model.

By adopting a Bayesian approach, the over-fitting problem can be avoided. We shall see that there is no difficulty from a Bayesian perspective in employing models for which the number of parameters greatly exceeds the number of data points. Indeed, in a Bayesian model the effective number of parameters adapts automatically to the size of the data set.




