---
title: "Graph-based Virtual Sensing from Sparse and Partial Multivariate Observation"
authors:
    - Giovanni De Felice
    - Andrea Cini
    - Daniele Zambon
    - Vladimir Gusev
    - Cesare Alippi
abstract: "Virtual sensing techniques allow for inferring signals at new unmonitored locations by exploiting available spatio-temporal measurements coming from physical sensors at different locations. However, as the sensor coverage becomes sparse due to costs or other constraints, physical proximity cannot be used to support interpolation.  In this paper, we overcome this challenge by leveraging dependencies between the target variable and a set of correlated variables (covariates) that can frequently be associated with each location of interest. From this viewpoint, covariates provide partial observability, and the problem consists of inferring values for unobserved channels by exploiting observations at other locations to learn how such variables can correlate. To tackle this problem, we design a novel graph deep learning framework operating on a nested graph structure, which is used to learn dependencies between variables as well as locations. The proposed architecture, named Graph-graph Network (GgNet), relies on propagating information over such nested graph structure. GgNet is extensively evaluated under different virtual sensing scenarios, demonstrating higher reconstruction accuracy compared to the state-of-the-art."
categories:
    - spatio-temporal
link: https://openreview.net/forum?id=CAqdG2dy5
code: https://github.com/gdefe/ggnet-virtual-sensing
venue: ICLR 2024
thumbnail: world_website.png
layout: abstract
order: 7
---
