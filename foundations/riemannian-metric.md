---
layout: default
title: Riemannian Metric
---

## Definition: Riemannian Metric

A **Riemannian metric** on a smooth manifold $M$ is a family of inner products
$g_p : T_pM \times T_pM \to \mathbb{R}$, one for each point $p \in M$, that varies smoothly from point to point. 
That is, $g_p$ is bilinear, symmetric, and positive-definite.
By smoothly varying, we mean that for any two smooth vector fields $X$ and $Y$ on $M$, the function $p \mapsto g_p(X_p, Y_p)$ is a smooth function.

The pair $(M, g)$ is called a **Riemannian manifold**.

---

### Local Coordinates

In a local coordinate chart $(U, x^i)$, the metric is expressed as a symmetric $(0,2)$-tensor:

$$
g = g_{ij} dx^i \otimes dx^j
$$

The components $g_{ij} = g(\frac{\partial}{\partial x^i},\frac{\partial}{\partial x^j}) $ form a symmetric, positive-definite matrix at each point. This matrix allows us to compute the inner product of two tangent vectors $v = v^i \frac{\partial}{\partial x^i}$ and $w = w^j \frac{\partial}{\partial x^j}$ as:

$$
g(v, w) = g_{ij}v^i w^j
$$

(Note: The Einstein summation convention is used here.)

---

### Example: The Euclidean Metric

The simplest example of a Riemannian metric is the standard Euclidean metric on $\mathbb{R}^n$. In the standard coordinates $(x^1, \dots, x^n)$, the metric tensor is given by the Kronecker delta, $\delta_{ij}$.

The matrix of components is the identity matrix:

$$
[g_{ij}] = 
\begin{pmatrix}
1 & 0 & \cdots & 0 \\
0 & 1 & \cdots & 0 \\
\vdots & \vdots & \ddots & \vdots \\
0 & 0 & \cdots & 1
\end{pmatrix}
$$
