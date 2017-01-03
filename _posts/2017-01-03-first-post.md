---
layout: post
title: First post!
---

Hello all! Welcome to my blog / personal rambling materials. Here I am hoping to write about my transition from academia (and physics in particular) into business (and data science in particular), and any other topics that I may find interesting, confusing or fun. In this first post, I thought maybe I should explain the name choice. 

Suppose that we have a function f of a single variable t, which describes the motion of a ball. For a ball, the function satisfies the Newton's second law with zero force (if we don't touch it), $F = ma = 0$. The solutions to this equation are famously straight lines. Let's consider two particular solutions, $f_1(t) = 0$ and  $f_2(t) = t$. The first solution is stationary and the second solution moves at velocity of 1. We can construct a composite function by joining them together at $$t=0$$, which can be written as
$$ f(t) = \begin{cases} 0 & t \leq 0 \\\\ t & t > 0 \end{cases} $$

Although the individual pieces of the composite function do satisfy the underlying equation, the composite itself does not. We have introduced a kink to the curve at $t=0$ by joining them together. Differentiating f twice yields the Dirac delta function $\delta(t)$, and it is not zero when $t=0$. In general, the composite of two solutions is not a solution any more, but the question then arises: can we construct a composite solution that *DOES* solve the original equation as well?

In the case of Newton's second law with zero force, the answer is no. The composite of two straight lines is a straight line only if the two are indentical solutions. But there are plenty of equations of motion that are more complicated than the one we considered above. For example, we could allow the force term to be non-zero, in which case our composite function does solve the equation, as long as $$F(t) = m \delta(t)$$. The two solutions can be joined, if we exert a force impulse at $$t=0$$. Give the ball a kick and it starts moving.

In general relativity, a similar situation arises if one replaces the ball with a spacetime and Newton's second law with the Einstein field equations. Two spacetimes can be joined on a junction surface (a 3-dimensional hypersurface, really), and the composite spacetime can still satisfy the Einstein equations if certain conditions are met. It turns out that in general relativity, it is easier to construct complicated solutions by combining several simpler ones, rather than solving the difficult Einstein equations for the complex solution. That is why junction surfaces and conditions played a large role in my [PhD thesis](http://urn.fi/URN:ISBN:978-951-51-1262-0) where I studied light propagation in spacetimes that are composites of a bunch of simpler solutions. I studied both, the kinds of composites where the two solutions can be combined automatically, and the kinds where you need a "kick" to join the two, just like with the ball trajectory example. In this case, the "kick" is a infinitesimally thin shell of energy.

