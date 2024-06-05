---
title: 'Spatial modeling with R-INLA: A review'
authors:
- Haakon Bakka
- Håvard Rue
- Geir Arne Fuglstad
- Andrea Riebler
- David Bolin
- Janine Illian
- Elias Krainski
- Daniel Simpson
- Finn Lindgren
date: '2018-01-01'
publishDate: '2024-06-05T21:10:24.347330Z'
publication_types:
- article-journal
publication: '*Wiley Interdisciplinary Reviews: Computational Statistics*'
doi: 10.1002/wics.1443
abstract: 'Coming up with Bayesian models for spatial data is easy, but performing
  inference with them can be challenging. Writing fast inference code for a complex
  spatial model with realistically-sized datasets from scratch is time-consuming,
  and if changes are made to the model, there is little guarantee that the code performs
  well. The key advantages of R-INLA are the ease with which complex models can be
  created and modified, without the need to write complex code, and the speed at which
  inference can be done even for spatial problems with hundreds of thousands of observations.
  R-INLA handles latent Gaussian models, where fixed effects, structured and unstructured
  Gaussian random effects are combined linearly in a linear predictor, and the elements
  of the linear predictor are observed through one or more likelihoods. The structured
  random effects can be both standard areal model such as the Besag and the BYM models,
  and geostatistical models from a subset of the Matérn Gaussian random fields. In
  this review, we discuss the large success of spatial modeling with R-INLA and the
  types of spatial models that can be fitted, we give an overview of recent developments
  for areal models, and we give an overview of the stochastic partial differential
  equation (SPDE) approach and some of the ways it can be extended beyond the assumptions
  of isotropy and separability. In particular, we describe how slight changes to the
  SPDE approach leads to straight-forward approaches for nonstationary spatial models
  and nonseparable space–time models. This article is categorized under: Statistical
  and Graphical Methods of Data Analysis > Bayesian Methods and Theory Statistical
  Models > Bayesian Models Data: Types and Structure > Massive Data.'
tags:
- Gaussian Markov random fields
- Laplace approximations
- approximate Bayesian inference
- sparse matrices
- spatial statistics
- stochastic partial differential equations
---
