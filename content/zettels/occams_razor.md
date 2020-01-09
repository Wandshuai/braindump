+++
title = "Occam's Razor"
author = ["Jethro Kuan"]
lastmod = 2020-01-03T09:43:17+08:00
draft = false
math = true
+++

Occam's razor is the principle that states a preference for simpler
models. This is not just a philosophical choice: Bayesian
probabilistic inference automatically embodies this principle,
quantitatively. To see this, we evaluate 2 alternative theories
\\(\mathcal{H}\_1\\) and \\(\mathcal{H}\_2\\), in light of observing data
\\(\mathcal{D}\\).

\begin{equation}
  \frac{P(\mathcal{H}\_1|\mathcal{D})}{P(\mathcal{H}\_2|\mathcal{D})} =
  \frac{P(\mathcal{H}\_1)}{P(\mathcal{H}\_2)} \frac{P(\mathcal{D}|\mathcal{H}\_1)}{P(\mathcal{D}|\mathcal{H}\_2)}
\end{equation}

The ratio \\(\frac{P(\mathcal{H}\_1)}{P(\mathcal{H}\_2)}\\) denotes how much
our initial beliefs favoured \\(\mathcal{H}\_1\\) over \\(\mathcal{H}\_2\\). The
second ratio expresses how well relatively the observed data
\\(\mathcal{D}\\) were predicted by the 2 hypotheses.

Simple models make precise computations, while complex models spread
their predictive probabilities more thinly over their larger
hypothesis space. In the case where the data are compatible with both
theories, the simpler \\(\mathcal{H}\_1\\) would turn out to be more
probable than the more complex \\(\mathcal{H}\_2\\). Hence the second term
automatically embodies the Occam's razor.


## Related {#related}

-   [§two\_levels\_of\_inference]({{< relref "two_levels_of_inference" >}})