---
layout: post
title: "To Give & To Receive: Scientific Learning"
tagline: Single Page
date: 2026-08-12 13:23
categories: [Machine Learning, Giving-Receiving ]
tags: [Supply and Demand, Power Grid]
image: img-04.jpg
---
Over the past decade, the 19th century science-of-counting has been resurrected to provide a combinatorial derivation of conventional Machine Learning that uniquely generalizes statistics to probability theory, allows energy to enter or exit the system, and processes any time-series to return a complete set of scientific (thermodynamic) measurements as deductive Reality.  And now that we have a plausible way to explain and generalize Machine Learning for time-series, we observe that "Machine" and "Artificial Intelligence" are too prominent, because in the science-of-counting computers only do what they have done from the beginning: evaluate built-in functions.  The derivation of the functions is human intelligence, not artificial intelligence. In the science-of-counting "scientific machine learning" is simplified to scientific learning.  

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
\cal{L} &= \cal{L}_S + \cal{L}_D - \lambda_{SD}\,<n_S\,n_D> - \,\sigma_{SD}\,<v_S\,v_D>.
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
The interaction of the two time-series, $$\Lambda(\lambda_{SD})$$, is a function of the interaction coupling, $$\lambda_{SD}$$.  When $$\Lambda(\lambda_{SD} = 0) = 1$$, the function above reduces correctly to the definition of independence in probabilities.  Scientific learning defines the interaction algebraically, as a plane cubic curve (a Tschirnhausen cubic),
{% raw %}
$$
\begin{align}
p^2(n_S n_D)= \Bigg[1-\frac{p(n_S)p(n_D)}{p(n_S n_D)} \Bigg]\;p(n_S)p(n_D) = \Bigg[\frac{\Lambda-1}{\Lambda}\Bigg]\;p(n_S)p(n_D),
\end{align}
$$
{% endraw %}  
that fixes how the various momenta (normalized to also be probabilities) must fit together and change in concert.  See interaction diagram and coupling curve below.

<figure>
  <img src="/images/blog/InteractionSoC.png" alt="Interaction Probabilities" style="max-width: 50%; height: auto; display: block; margin: 0 auto;" />
  <figcaption style="text-align: center; font-size: 0.85rem; opacity: 0.7; margin-top: 8px;">
    Analytical Interactions in the Science of Giving and Receiving
  </figcaption>
</figure>

To demonstrate with forward scattering, we are given the historical time-series $$n_S$$ and $$n_D$$ and calculate the scientific learning measurements $$p(n_S)$$ and $$p(n_D)$$.  Multiply the measurements, $$p(n_S)p(n_D)$$, and identify the point on the x-axis of the coupling curve, map to the corresponding point on the y-axis, $$p(n_S n_D)$$.  The output with interaction is given by the conditional probabilities $$p(n_S\vert n_D)=p(n_S n_D)/p(n_D)$$ and $$p(n_D\vert n_S)=p(n_S n_D)/p(n_S)$$.

Using the following identities,
{% raw %}
$$
\begin{align}
\frac{y}{x} = \frac{p(n_S n_D)}{p(n_S)p(n_D)} = \frac{p(n_S\vert n_D)}{p(n_S)} = \frac{p(n_D\vert n_S)}{p(n_D)},
\end{align}
$$
{% endraw %}
the curve is the same but the axis labels $$x$$ and $$y$$ define a different problem: forward and backward scattering, supply needed for demand, demand needed for supply, respectively. An analysis with live time-series data is being prepared for publication.


**To Give and To Receive**

For a power grid, the desired output in the momentum/probability distribution (pdf) for demand, $$p(n_D\vert n_S)$$, is given, so that the required supply momentum/pdf that would meet the demand can be calculated, from the coupling curve (solution to the cubic equation) and the product rule in probability theory, $$p(n_S) = p(n_S n_D)/p(n_D\vert n_S)$$.





