---
title: "Inflationary Flows: Calibrated Bayesian Inference with Diffusion-Based Models"
collection: publications
permalink: /publication/phd_IFs_paper
excerpt: 'In this project we exploited a previously established connection between the stochastic and probability flow ordinary differential equations (pfODEs) underlying
Diffusion-Based Models (DBMs) to derive a new class of models, <i>inflationary flows</i>, that uniquely and deterministically map high-dimensional data to a lower-dimensional 
Gaussian distribution via ODE integration.'
date: 2024-07-11
venue: 'ArXiv (preprint)'
paperurl: 'https://arxiv.org/pdf/2407.08843v1'
citation: '<strong> De Albuquerque, D.</strong>, & Pearson, J.(2024). &quot;Inflationary Flows: Calibrated Bayesian Inference with Diffusion-Based Models.&quot; <i>arXiv: 2407.08843 [cs, stat]</i>'
---

<i>Abstract:</i> Beyond estimating parameters of interest from data, one of the key goals of statistical inference is to properly quantify 
uncertainty in these estimates. In Bayesian inference, this uncertainty is provided by the posterior distribution, the computation of which 
typically involves an intractable high-dimensional integral. Among available approximation methods, sampling-based approaches come with strong theoretical 
guarantees but scale poorly to large problems, while variational approaches scale well but offer few theoretical guarantees. In particular, variational methods 
are known to produce overconfident estimates of posterior uncertainty and are typically non-identifiable, with many latent variable configurations generating 
equivalent predictions. Here, we address these challenges by showing how diffusion-based models (DBMs), which have recently produced state-of-the-art performance 
in generative modeling tasks, can be repurposed for performing calibrated, identifiable Bayesian inference. By exploiting a previously established connection between 
the stochastic and probability flow ordinary differential equations (pfODEs) underlying DBMs, we derive a class of models, <i>inflationary flows</i>, that uniquely and 
deterministically map high-dimensional data to a lower-dimensional Gaussian distribution via ODE integration. This map is both invertible and neighborhood-preserving, 
with controllable numerical error, with the result that uncertainties in the data are correctly propagated to the latent space. We demonstrate how such maps can be 
learned via standard DBM training using a novel noise schedule and are effective at both preserving and reducing intrinsic data dimensionality. The result is a class of 
highly expressive generative models, uniquely defined on a low-dimensional latent space, that afford principled Bayesian inference.
