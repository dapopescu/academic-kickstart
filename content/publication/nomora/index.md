+++
title = "No Delay: Latency-Driven, Application Performance-Aware, Cluster Scheduling"
date = 2020-06-11T13:01:16+03:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Diana Andreea Popescu, Andrew W. Moore"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "arXiv:1903.07114"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Given the network latency variability observed in data centers, applications' performance is also determined by their placement within the data centre. We present NoMora, a cluster scheduling architecture whose core is represented by a latency-driven, application performance-aware, cluster scheduling policy. The policy places the tasks of an application taking into account the expected performance based on the measured network latency between pairs of hosts in the data center. Furthermore, if a tenant's application experiences increased network latency, and thus lower application performance, their application may be migrated to a better placement. Preliminary results show that our policy improves the overall average application performance by up to 13.4% and by up to 42% if preemption is enabled, and improves the task placement latency by a factor of 1.79x and the median algorithm runtime by 1.16x compared to a random policy on the Google cluster workload. This demonstrates that application performance can be improved by exploiting the relationship between network latency and application performance, and the current network conditions in a data center, while preserving the demands of low-latency cluster scheduling."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["nomora"]

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Network Latency", "Cloud Computing", "Cluster Scheduling", "Application Performance", "Network measurement"]

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1903.07114.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
