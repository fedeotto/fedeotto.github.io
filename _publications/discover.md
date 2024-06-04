---
title: "Not as simple as we thought: A rigorous examination of data aggregation in materials informatics"
authors:
    - Federico Ottomano<sup>*</sup>
    - Giovanni De Felice<sup>*</sup>
    - Vladimir Gusev
    - Taylor Sparks
abstract: "Recent Machine Learning (ML) developments have opened new perspectives on accelerating the discovery of new materials. However, in the field of materials informatics, the performance of ML estimators is heavily limited by the nature of the available training datasets, which are often severely restricted and unbalanced. Among practitioners, it is usually taken for granted that more data corresponds to better performance. Here, we investigate whether different ML models for property predictions benefit from the aggregation of large databases into smaller repositories. To do this, we probe three different aggregation strategies prioritizing training size, element diversity, and composition diversity. For classic ML models, our results consistently show a reduction in performance under all the considered strategies. Deep Learning models show more robustness, but most changes are not significant. Furthermore, to assess whether this is a consequence of a distribution mismatch between datasets, we simulate the data acquisition process of a single dataset and compare a random selection with prioritizing chemical diversity. We observe that prioritizing composition diversity generally leads to a slower convergence toward better accuracy. Overall, our results suggest caution when merging different data sources and discourage a biased acquisition of novel chemistries when building a training dataset."
categories:
    - materials-informatics
link: https://pubs.rsc.org/en/content/articlehtml/2024/dd/d3dd00207a
code: https://github.com/fedeotto/data-aggregation-mi
venue: Digital Discovery
thumbnail: data_aggr.png
layout: abstract
order: 5
---
