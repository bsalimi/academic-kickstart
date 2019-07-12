+++
title = "Interventional Fairness: Causal Database Repair for Algorithmic Fairness"
date = 2019-09-05T14:33:03-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Babak Salimi, Luke Rodriguez, Bill Howe, Dan Suciu"]

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
publication = "Proceedings of the 2019 International Conference on Management of Data"
publication_short = "ACM SIGMOD"

# Abstract and optional shortened version.
abstract = "Fairness is increasingly recognized as a critical component of machine learning systems. However,it is the underlying data on which these systems are trained that often reflect discrimination, sug-gesting a database repair problem. Existing treatments of fairness rely on statistical correlations thatcan be fooled by statistical anomalies, such as Simpson’s paradox.  Proposals for causality-baseddefinitions of fairness can correctly model some of these situations, but they require specification ofthe underlying causal models. In this paper, we formalize the situation as a database repair problem,proving sufficient conditions for fair classifiers in terms of admissible variables as opposed to acomplete causal model. We show that these conditions correctly capture subtle fairness violations.We then use these conditions as the basis for database repair algorithms that provide provable fairnessguarantees about classifiers trained on their training labels. We evaluate our algorithms on real data,demonstrating improvement over the state of the art on multiple fairness metrics proposed in theliterature while retaining high utility."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = ["capuchin"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://dl.acm.org/citation.cfm?id=3319901"
url_preprint = "https://arxiv.org/abs/1902.08283"
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
