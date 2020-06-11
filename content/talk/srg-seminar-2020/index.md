+++
title = "Latency-driven Performance in Data Centres"
date = 2020-06-11T13:32:42+03:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2020-06-04T15:00:00+00:00
time_end = 2020-06-04T15:00:00+00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Diana Andreea Popescu"]

# Abstract and optional shortened version.
abstract = "Data centre-based cloud computing has revolutionised the way businesses use computing infrastructure. Instead of building their own data centres, companies rent computing resources and deploy their applications on cloud hardware. Providing customers with well-defined application performance guarantees is of paramount importance to ensure transparency and to build a lasting collaboration between users and cloud operators. A user’s application performance is subject to the constraints of the resources it has been allocated and to the impact of the network conditions in the data centre. Firstly, I show how to use the Precision Time Protocol (PTP), through an open-source software implementation PTPd, to measure network conditions. I propose PTPmesh, which uses PTPd, as a cloud network monitoring tool for tenants. Furthermore, I conduct a measurement study using PTPmesh in different cloud providers, finding that network latency variability in data centres is still common. Normal latency values in data centres are in the order of tens or hundreds of microseconds, while unexpected events, such as network congestion or packet loss, can lead to latency spikes in the order of milliseconds. Secondly, I show that network latency matters for certain distributed applications even in small amounts of tens or hundreds of microseconds, significantly reducing their performance. Given the network latency variability observed in data centres, applications’ performance is determined by their placement within the data centre. Thirdly, I propose latency-driven, application performance-aware, cluster scheduling as a way to provide performance guarantees to applications. I introduce NoMora, a cluster scheduling architecture that leverages the predictions of application performance dependent upon network latency combined with dynamic network latency measurements taken between pairs of hosts in data centres to place applications, showing that NoMora improves application performance by choosing better placements than other scheduling policies."
abstract_short = ""

# Name of event and optional event URL.
event = "Computer Laboratory Systems Research Group Seminar"
event_url = "https://talks.cam.ac.uk/talk/index/143965"

# Location of event.
location = "Computer Laboratory, University of Cambridge"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Network Latency", "Application Performance", "Cloud Computing", "Cluster Scheduling", "Network Measurement", "Precision Time Protocol"]

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = "https://www.cl.cam.ac.uk/research/srg/netos/seminars/videos/2020-06-04-15-06-47.mp4"
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
