---
layout: default
title: The Inverse Metric
part: 1
chapter: 1
---

<h2><a href="https://ricciflow.org/part-1-foundations">Part 1</a></h2>

### <a href="https://ricciflow.org/part-1-foundations/inverse-metric">Chapter 2</a> The Inverse Metric

For every Riemannian metric $g$, which is represented in local coordinates by the matrix of components $[g_{ij}]$, there exists an **inverse metric**. The components of the inverse metric are denoted with upper indices, $g^{ij}$, and are defined as the entries of the matrix inverse of $[g_{ij}]$.

$$
[g^{ij}] = [g_{ij}]^{-1}
$$

As a tensor
$$
g^{-1} = g^{ij} \frac{\partial}{\partial x^i} \otimes \frac{\partial}{\partial x^j}
$$
is a well-defined symmetric $(2,0)$-tensor.

---
## Key Property

The fundamental relationship between the metric and its inverse is captured by the following equation, where $\delta_i^j$ is the Kronecker delta (the components of the identity matrix):

$$
g_{ik}g^{kj} = \delta_i^j
$$

This is the formal statement that the two matrices are inverses of each other.

---
## Application: Raising Indices

The primary algebraic use of the inverse metric is to "raise indices," which provides a canonical way to convert a covector (a $(0,1)$-tensor) into a vector (a $(1,0)$-tensor).

If you have a covector with components $V_j$, you can obtain the components of the corresponding vector $V^i$ using the inverse metric:

$$
V^i = g^{ij}V_j
$$

This operation is fundamental for defining many concepts in geometric analysis, such as the gradient of a function.
