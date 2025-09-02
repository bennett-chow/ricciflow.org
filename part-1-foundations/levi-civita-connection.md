---
layout: default
title: Levi-Civita connection
part: 1
chapter: 3
---

<h2><a href="https://ricciflow.org/part-1-foundations">Part 1</a></h2>

### <a href="https://ricciflow.org/part-1-foundations/levi-civita-connection">Chapter 3</a> Definition: Levi-Civita connection

**Definition** On a Riemannian manifold $(M, g)$, the **Levi-Civita connection** is the unique affine connection, denoted by $\nabla$, that satisfies two fundamental properties: it is **torsion-free** and it is **compatible with the metric** $g$.

Let $X$, $Y$, and $Z$ be smooth vector fields on $M$. The two defining properties are detailed below.

#### Torsion-Free (Symmetry)

A connection is torsion-free if the order of the lower arguments does not introduce a torsion term. This property relates the connection to the Lie bracket of vector fields.

$$
    \nabla_X Y - \nabla_Y X = [X, Y]
$$

#### Metric Compatibility

A connection is compatible with the metric $g$ if the metric tensor is covariantly constant ($\nabla g = 0$). This ensures that lengths and angles are preserved under parallel transport. The condition is expressed via the product rule:

$$
    X(g(Y, Z)) = g(\nabla_X Y, Z) + g(Y, \nabla_X Z)
$$

#### The Koszul Formula

The existence and uniqueness of the Levi-Civita connection are guaranteed by the Fundamental Theorem of Riemannian Geometry. This theorem also provides an explicit formula for the connection, known as the **Koszul formula**, which defines $\nabla_X Y$ by its inner product with an arbitrary vector field $Z$.

$$
    2g(\nabla_X Y, Z) = X(g(Y, Z)) + Y(g(Z, X)) - Z(g(X, Y)) - g(X, [Y, Z]) - g(Y, [X, Z]) + g(Z, [X, Y])
$$

