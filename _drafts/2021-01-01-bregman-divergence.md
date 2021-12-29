---
layout: post
title: "Fun with Bregman Divergence"
description: "Definition, Experiments and Code."
tags: [information geometry]
---

## Definition

Let  <math>F: \Omega \to \mathbb{R} </math> be a continuously-differentiable, strictly [[convex function]] defined on a closed [[convex set]] <math>\Omega</math>.

The Bregman distance associated with ''F'' for points <math>p, q \in \Omega</math> is the difference between the value of ''F'' at point ''p'' and the value of the first-order [[Taylor expansion]] of ''F'' around point ''q'' evaluated at point ''p'':
:<math>D_F(p, q) = F(p)-F(q)-\langle \nabla F(q), p-q\rangle. </math>

