---
title: Interpretable Deep Learning for dimensionality reduction
summary: Embedding functional ANOVA decompositions within deep learning frameworks.
tags:
- Deep Learning
- Explainable Algorithms
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

Neural network models for dimensionality reduction, such as Variational AutoEncoders (VAEs), can identify latent low-dimensional structures embedded within high-dimensional data. These low-dimensional representations can provide some insight into patterns within datasets but their interpretation relies on how these map back on the original feature set. However the latter requires interpreting what the decoder network has learnt which makes it challenging. 

In this paper, we focus on understanding the sources of variation in Conditional VAEs. Our goal is to *decompose* the feature-level variation in high-dimensional data through disentanglement of additive and interactions effects of latent variables z and fixed inputs c. We propose to achieve this through the Neural Decomposition - an adaptation of the well-known concept of variance decomposition from classical statistics to deep learning models. We show that *identifiable* Neural Decomposition relies on training models subject to constraints on the marginal properties of the neural networks whilst naive implementations will lead to non-identifiable models.

We demonstrate the utility of our Neural Decomposition on a series of simulated examples as well as real gene expression data. For the latter, we show that it can provide a *scalable* approach to attribute biological variation in terms of the non-linear effects of latent variables, fixed inputs, and interactions between them. 


