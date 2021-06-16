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

数学符号的约定

Vectors are denoted by lower case bold Roman letters such as
`$x$`, and all vectors are assumed to be column vectors. A superscript T denotes the
transpose of a matrix or vector, so that `$x^T$` will be a row vector. Uppercase bold
roman letters, such as `$\mathbf{M}$`, denote matrices. The notation `$(w_1, . . . , w_M)$` denotes a
row vector with M elements, while the corresponding column vector is written as `$w = (w_1, . . . , w_M)^T$`

If we have N values `$x_1, . . . , x_N$` of a D-dimensional vector `$x = (x_1, . . . , x_D)^T$`,
we can combine the observations into a data matrix `$\mathbf{X}$` in which the n-th row of `$\mathbf{X}$`
corresponds to the row vector `$x^T$` n. Thus the n, i element of `$\mathbf{X}$` corresponds to the
ith element of the nth observation `x_n`. 

For the case of one-dimensional variables we
shall denote such a matrix by `$\mathsf{x}$`, which is a column vector whose nth element is `$x_n$`.
Note that `$\mathsf{x}$` (which has dimensionality N) uses a different typeface to distinguish it
from x (which has dimensionality D).





