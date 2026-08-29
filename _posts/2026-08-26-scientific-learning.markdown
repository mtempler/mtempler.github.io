---
layout: post
title: "To Give & To Receive: Scientific Learning"
tagline: Single Page
date: 2026-08-12 13:23
categories: [AI]
tags: [Supply and Demand, Power Grid]
image: img-04.jpg
---

Over the past decade, the 19th century science-of-counting has been resurrected to provide a combinatorial derivation for conventional Machine Learning that uniquely generalizes statistics to probability theory, allows energy to enter or exit the system, and processes any time-series to return a complete set of scientific (thermodynamic) measurements as deductive Reality.  And now that we have a plausible way to explain and generalize Machine Learning for time-series, we observe that "Machine" and "Artificial Intelligence" are too prominent in this case, because in the science-of-counting computers only do what they have always done: evaluate built-in functions.  The derivation of the functions indicate human intelligence, not artificial intelligence. In the science-of-counting "scientific machine learning" is simplified to scientific learning.  

Conventional machine learning is effective in static, closed world applications, but cannot accommodate changing environments, where energy can enter or exit, or, where strain stores energy for later release.  Energy allowed to enter or exit also allows emotional energy to enter and exit, as a principle and obvious source of human energy that can both affect dynamics and anticipate a need.  Scientific learning is the science-of-counting evaluated on time-series that permits energy flow and energy storage, and reduces to statistics when there is no energy entering or exiting the system.

What a gift is the human mind (intuition, intellect and emotions) that is capable to understand deductive Reality.

By examining problems that share the same overall mathematical structure as Scientific Learning, the power grid is seen to have a historical connection and is structurally the same shape.  The key difference is that our current grid makes an engineering assumption/simplification that the average strains are zero, which is only possible at statistical equilibrium (when it is just as likely to go up as to go down).  The traditional power grid could ignore strain, because power generation was under controlled. But given renewable energy sources, the next generation of power grid must recognize and manage power grid strains along with the supply and demand.  

When applied to a need, say, electrical power, **Scientific Learning** becomes the **Science of Giving and Receiving**.  With both the supply and demand time-series, the power grid realizes the Science of Giving and Receiving.  The science of giving and receiving is used to re-architect the power grid for non-equilibrium operation to support variable energy sources.  The power grid of the future is a re-engineering problem that is not solved by government policy alone.

**Supply and Demand Interactions** 

The functions that define the relationship between energy, momentum and velocity, E=pv, are deduced in the science-of-counting. To manage supply and demand the same analysis is deductively extended to interactions as well.  A high-level picture of the interaction science is presented here.

Given a time-series for power demand (in MWh), $$n_D$$, there are natural coordinates (an eigenbasis) in scientific learning that define the Expected Demand and its associated Expected Strain. Similarly, given a time-series for power supply (in MWh), $$n_S$$, the Expected Supply and its associated Expect Strain are defined.  The Lagrangian below enforces supply and demand measurements as constraints, $$\cal{L}_S$$ and $$\cal{L}_D$$, and furthermore adds the constraints for interaction measurements, the $$\lambda_{SD}$$ and the $$\sigma_{SD}$$ terms below.
{% raw %}
$$
\begin{align}
\cal{L} &= \cal{L}_S + \cal{L}_D - \lambda_{SD}\,<n_S\,n_D> - \sigma_{SD}\,<v_S\,v_D>.
\end{align}
$$
{% endraw %}  
If the supply and demand time-series are independent, that is, there is no interaction between the two, then the time-series would report that the couplings $$\lambda_{SD}$$ and $$\sigma_{SD}$$ are both equal to zero, and that $$p(n_S n_D) = p(n_S)p(n_D)$$. In truth, of course, supply and demand are highly coupled and interact non-trivially, so that 
{% raw %}
$$
\begin{align}
p(n_S n_D)=\Lambda(\lambda_{SD})\;p(n_S)p(n_D),
\end{align}
$$
{% endraw %}  
The interaction of the two time-series, $$\Lambda(\lambda_{SD})$$, is a function of the interaction coupling, $$\lambda_{SD}$$.  When $$\Lambda(\lambda_{SD} = 0) = 1$$ the function above reduces correctly to the definition of probabilistic independence.  The interaction defines a plane curve (a Tschirnhausen cubic) that demonstrates how the various momenta (normalized to also be probabilities) must fit together and change in concert.

![Curve relating joint probability to the product of independent probabilities](C:/Users/mtemp/Desktop/Decision Machine/Software/Browser/fides-et-ratio/images/blog/PlaneCurve.png)

<figure>
  <img src="C:/Users/mtemp/Desktop/Decision Machine/Software/Browser/fides-et-ratio/images/blog/PlaneCurve.png" alt="Interaction Probabilities" style="max-width: 100%; height: auto;" />
  <figcaption style="text-align: center; font-size: 0.85rem; opacity: 0.7; margin-top: 8px;">
    The coupling curve: $$p(n_A n_B)$$ vs. $$p(n_A)p(n_B)$$, following $$y^2 = x(1 - x/y)$$.
  </figcaption>
</figure>


