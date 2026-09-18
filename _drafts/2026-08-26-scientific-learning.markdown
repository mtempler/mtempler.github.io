---
layout: post
title: "To Give & To Receive: Cooperation"
tagline: Single Page
date: 2026-08-12 13:23
categories: [Machine Learning, Giving-Receiving ]
tags: [Supply and Demand, Power Grid]
image: img-04.jpg
---
In a previous blog we examined the science-of-counting in units of measure, and applied it to the design of the power grid.  The key realization is self-confidence in counted measures.  Our self-confidence in counting can be expressed mathematically as constraints on science (Lagrange multipliers).  Everything thereafter is deductive, exact, and free from bias, and is used to produce rigorous and familiar scientific measurements of time-series (time-stamps and counted values, to give energy, momentum, exact probability distributions, and so on).

The first thing to note when you look at measurements, is that scientific measurements on time-series rarely behave statistically, and that energy routinely enters and exits the system (is not mechanical).  A scientist would welcome the development, because it means years of interesting work and a pivot toward reality and better understanding.  The initial reaction from  industry would likely be horror, understandably, because the install base is suddenly anachronistic.  However, it is only a course correction where scientific learning rigorously and uniquely generalizes statistics and statistical mechanics.  Many years of interesting work for many people that should be planned and well-considered, because it will involved the talents and expertise of many to realize.

We focus on the electrical power grid precisely because it is a multi-faceted operational environment, requires coordination to operate, and is known to be cautious.  But most importantly, the risk is reduced significantly for power grids, because the conventional grid is already built on a simplified science-of-counting (average strain vanishes at statistcs).  The engineering assumption is valid when the generated power is known and stable, however, renewables make the assumption invalid.   

With strain zero-ed out, humanity strayed from the deductive path.  Human invention was needed to make the system work.  It was soon discovered that AC voltage regulation required the re-introduction of energy storage, in the form of imaginary values for reactivity in capacitors and inductors.  In this blog we look at how reactivity emerges naturally from the full science-of-counting, instead of the half-theory.

**Reactivity** 

The functions that define the relationship between energy, momentum and velocity, E=pv, are deduced in the science-of-counting. To manage supply and demand the same analysis is deductively extended to interactions as well.  A high-level picture of the interaction science is presented in the previous blog.

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

To demonstrate with forward scattering, we are given the historical time-series $$A=n_S$$ and $$B=n_D$$ and calculate the scientific learning measurements $$p(n_S)$$ and $$p(n_D)$$.  Multiply the measurements, $$p(n_S)p(n_D)$$, and identify the point on the x-axis of the coupling curve, map to the corresponding point on the y-axis, $$p(n_S n_D)$$.  The output with interaction is given by the conditional probabilities $$p(n_S\vert n_D)=p(n_S n_D)/p(n_D)$$ and $$p(n_D\vert n_S)=p(n_S n_D)/p(n_S)$$.

Using the following identities,
{% raw %}
$$
\begin{align}
\frac{y}{x} = \frac{p(n_S n_D)}{p(n_S)p(n_D)} = \frac{p(n_S\vert n_D)}{p(n_S)} = \frac{p(n_D\vert n_S)}{p(n_D)},
\end{align}
$$
{% endraw %}
the curve is the same but the axis labels $$x$$ and $$y$$ define a different load problems: forward and backward scattering, supply needed for demand, demand needed for supply, respectively. 


**To Give and To Receive** 

The introduction of reward or barter breaks the deductive structure of scientific learning, which we have worked hard to preserve. The moment we introduce currency, models are introduced, in this case, exchange rate models that convert money to displacement energy.  Expect every business process to have its own changing exchange rate: spend for displacement energy.  Exchange rate models imply some degree of control through spend, from which we will manage supply and demand scientifically.

Giving should meet both physical and spiritual needs, including instruction, counsel, comfort and forgiveness.  For St. Thomas Aquinas, giving and receiving are not merely economic or social acts.  They are moral, spiritual and relational realities that mirror the very life of God. 



