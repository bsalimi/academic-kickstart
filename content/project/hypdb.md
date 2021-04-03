+++
title = "HypDB"
date = 2018-09-05T21:35:48-07:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["OLAP", "Decision Support Systems", "Causal Inference", "Simpson's Paradox"]

# Project summary to display on homepage.
summary = "A system to detect, explain, and resolve bias in decision-support OLAP queries"

# Optional image to display on homepage.
image_preview = "hypdb.jpg"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

HypDB is the first system to detect, explain, and resolve bias in decision-support OLAP queries. We show that biased queries can be perplexing and lead to statistical anomalies, such as Simpson’s paradox. We propose a novel technique to find explanations for the bias, thereby assisting the analyst in interpreting the results. We develop an automated method for rewriting the query into an unbiased query that correctly performs the hypothesis test that the analyst had in mind. The rewritten queries compute causal effect or the effect of hypothetical interventions. At the core of our framework lies the ability to find confounding variables. We show that HypDB can be used to detect algorithmic unfairness post factum.