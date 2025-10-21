---
title: Deep Diffeomorphic Normalizing Flows
authors:
- Hadi Salman
- Payman Yadollahpour
- Tom Fletcher
- Kayhan Batmanghelich
date: '2018-11-22'
publishDate: '2025-10-20T23:59:38.271320Z'
publication_types:
- paper-conference
publication: '*arXiv*'
doi: 10.48550/arXiv.1810.03256
abstract: The Normalizing Flow (NF) models a general probability density by estimating
  an invertible transformation applied on samples drawn from a known distribution.
  We introduce a new type of NF, called Deep Diffeomorphic Normalizing Flow (DDNF).
  A diffeomorphic flow is an invertible function where both the function and its inverse
  are smooth. We construct the flow using an ordinary differential equation (ODE)
  governed by a time-varying smooth vector field. We use a neural network to parametrize
  the smooth vector field and a recursive neural network (RNN) for approximating the
  solution of the ODE. Each cell in the RNN is a residual network implementing one
  Euler integration step. The architecture of our flow enables efficient likelihood
  evaluation, straightforward flow inversion, and results in highly flexible density
  estimation. An end-to-end trained DDNF achieves competitive results with state-of-the-art
  methods on a suite of density estimation and variational inference tasks. Finally,
  our method brings concepts from Riemannian geometry that, we believe, can open a
  new research direction for neural density estimation.
tags:
- Computer Science - Machine Learning
- My Publications
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/1810.03256
---
