---
layout: default 
title: Riemannian Curvature Tensor 
part: 1 
chapter: 4
---

<h2><a href="https://ricciflow.org/part-1-foundations">Part 1</a></h2>

### <a href="https://ricciflow.org/part-1-foundations/riemannian-metric">Chapter 4</a> Definition: Riemannian Curvature Tensor

**Definition** Once a manifold is equipped with a connection, we can measure its curvature. The Riemannian curvature tensor (or Riemann tensor), 
denoted R, is the central tool used to quantify the curvature of a Riemannian manifold. It measures the extent to which the metric locally deviates 
from being flat.For any smooth vector fields X, Y, and Z, the curvature tensor R(X,Y)Z is a vector field defined by the failure of the second 
covariant derivatives to commute:

$$
R(X, Y)Z = \nabla_X \nabla_Y Z - \nabla_Y \nabla_X Z - \nabla_{[X,Y]} Z
$$

#### Geometric Intuition

The curvature tensor reveals the effect of the manifold's curvature on its geometry. Its most famous interpretation is that it measures 
the failure of a vector to return to its original state after being **parallel transported** around an infinitesimal closed loop (a parallelogram).

On a flat manifold (like a Euclidean plane), a vector transported around a closed loop will point in the same direction it started. On a curved manifold 
(like a sphere), it will be rotated. The curvature tensor quantifies this rotation.

A manifold is **flat** if and only if its Riemann curvature tensor is everywhere zero.

#### Curvature in Local Coordinates

In a local coordinate system, the components of the Riemann tensor, denoted $R^k\_{lij}$, can be expressed entirely in terms of the Christoffel 
symbols ($\\Gamma^k\_{ij}$) of the Levi-Civita connection:

$$
R^k\_{lij} = \\frac{\\partial \\Gamma^k\_{mj}}{\\partial x^l} - \\frac{\\partial \\Gamma^k\_{ml}}{\\partial x^j} + \\Gamma^p\_{mj} 
\\Gamma^k\_{pl} - \\Gamma^p\_{ml} \\Gamma^k\_{pj}
$$

(Note: Some texts use different index conventions and signs, but this is a standard formulation).

This formula makes it clear that the curvature is determined entirely by the metric tensor $g$ and its derivatives, 
since the Christoffel symbols themselves are derived from $g$.
