---
title: Bellman's principle of optimality
draft: false
katex: true
---

# Bellman's principle of optimality

For a dynamic system with state feedback control
\\[
\dot{\bm{x}} = \bm{f}(\bm{x},\bm{u},τ) \;,\quad \bm{u} = \bm{u}(\bm{x}) \,,\; \bm{x} = \bm{x}(τ)
\\]
we may define a trajectory from state \\( \bm{x}(t_0) = \bm{x}_0 \\) to state \\( \bm{x}(t_1) \\) with a cost (objective function)
\\[
J(\bm{x}_0,t_0) = ∫_{t_0}^{t_1} L(\bm{x},\bm{u},τ) \, dτ
\\]

**the equation should render but the bracket in the lower bounds breaks the render**
\\[
J(\bm{x}_0,t_0) = ∫_t^{t_1} L(\bm{x},\bm{u},τ) \, dτ
\\]
**also some of the commas should not be renderd but modify spacing**