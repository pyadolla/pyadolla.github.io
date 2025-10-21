---
title: 'Incorporating External Information in Tissue Subtyping: A Topic Modeling Approach'
authors:
- Ardvan Saeedi
- Payman Yadollahpour
- Sumedha Singla
- Brian Pollack
- William Wells
- Frank Sciurba
- Kayhan Batmanghelich
date: '2021-10-21'
publishDate: '2025-10-20T23:59:38.263368Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 6th Machine Learning for Healthcare Conference*'
abstract: Probabilistic topic models, have been widely deployed for various applications
  such as learning disease or tissue subtypes. Yet, learning the parameters of such
  models is usually an ill-posed problem and may result in losing valuable information
  about disease severity. A common approach is to add a discriminative loss term to
  the generative model’s loss in order to learn a representation that is also predictive
  of disease severity. However, finding a balance between these two losses is not
  straightforward. We propose an alternative way in this paper. We develop a framework
  which allows for incorporating external covariates into the generative model’s approximate
  posterior. These covariates can have more discriminative power for disease severity
  compared to the representation that we extract from the posterior distribution.
  For instance, they can be features extracted from a neural network which predicts
  disease severity from CT images. Effectively, we enforce the generative model’s
  approximate posterior to reside in the subspace of these discriminative covariates.
  We illustrate our method’s application on a large-scale lung CT study of Chronic
  Obstructive Pulmonary Disease (COPD), a highly heterogeneous disease. We aim at
  identifying tissue subtypes by using a variant of topic model as a generative model.
  We quantitatively evaluate the predictive performance of the inferred subtypes and
  demonstrate that our method outperforms or performs on par with some reasonable
  baselines. We also show that some of the discovered subtypes are correlated with
  genetic measurements, suggesting that the identified subtypes may characterize the
  disease’s underlying etiology.
links:
- name: URL
  url: https://proceedings.mlr.press/v149/saeedi21a.html
---
