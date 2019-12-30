---
title: Multi-Omics Network inference
summary: A novel Bayesian nonparametric regression approach for high-dimensionality multi-modal data integration.
tags:
- Machine Learning
- Genomics
date: "2019-01-01"

# Optional external URL for project (replaces project detail page).
external_link: ""

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Dynamic alterations in gene expression programs during cell differentiation are regulated by the interplay of ubiquitous and tissue-specific transcription factors, and the epigenetic regulatory machinery. A mechanistic understanding can be postulated based on time-course multi-omics genome-wide measurements.

We developed a novel Bayesian nonparametric regression approach called **M**ulti-**O**mics **NET**work inference (MONET) for high-dimensionality multi-modal data integration to quantify the temporally dependent forces driving development and investigate by perturbation effects. Sparsity-inducing priors regularise the TF-gene interaction network and a Dirichlet process prior to regulate the number of participating TFs. This gives rise to a Bayesian nonparametric model where the number of TFs are learnt from data and not specified a priori. Statistical inference is performed in a Bayesian setting using an implementation of Hamiltonian Monte Carlo (HMC)-derived No-U Turn Sampler (NUTS) in STAN.

We show that MONET is able to extract accurate time-dependent TF-gene interaction networks and assess the importance of each TF for the different stages in haematopoietic development. Our model allows us to make predictions on the importance of specific TF over time and under different perturbation settings. Based on this we can create hypotheses for intervention to improve efficiency or halt development.


*Researchers:*

- [Anas Rana](/authors/rana/)




