+++
title = "Parallel Streaming Wasserstein Barycenters"
date = 2017-12-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Matthew Staib", "**Sebastian Claici**", "Justin Solomon", "Stefanie Jegelka"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Advances in Neural Information Processing Systems*"
publication_short = "In *NIPS*"

# Abstract and optional shortened version.
abstract = "Efficiently aggregating data from different sources is a challenging problem, particularly when samples from each source are distributed differently. These differences can be inherent to the inference task or present for other reasons: sensors in a sensor network may be placed far apart, affecting their individual measurements. Conversely, it is computationally advantageous to split Bayesian inference tasks across subsets of data, but data need not be identically distributed across subsets. One principled way to fuse probability distributions is via the lens of optimal transport: the Wasserstein barycenter is a single distribution that summarizes a collection of input measures while respecting their geometry. However, computing the barycenter scales poorly and requires discretization of all input distributions and the barycenter itself. Improving on this situation, we present a scalable, communication-efficient, parallel algorithm for computing the Wasserstein barycenter of arbitrary distributions. Our algorithm can operate directly on continuous input distributions and is optimized for streaming data. Our method is even robust to nonstationary input distributions and produces a barycenter estimate that tracks the input measures over time. The algorithm is semi-discrete, needing to discretize only the barycenter estimate. To the best of our knowledge, we also provide the first bounds on the quality of the approximate barycenter as the discretization becomes finer. Finally, we demonstrate the practical effectiveness of our method, both in tracking moving distributions on a sphere, as well as in a large-scale Bayesian inference task."
abstract_short = "We present a scalable, communication-efficient, parallel algorithm for computing the Wasserstein barycenter of arbitrary distributions."

# Featured image thumbnail (optional)
image_preview = "staib2017barycenters.jpg"

# Is this a selected publication? (true/false)
selected = true

# Links (optional).
url_pdf = "pdf/staib2017barycenters.pdf"
url_code = "https://github.com/mstaib/stochastic-barycenter-code"

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "exampl# e.jpg"`.
[header]
image = "staib2017barycenters.jpg"
+++