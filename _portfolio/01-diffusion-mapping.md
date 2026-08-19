---
title: "Diffusion Mapping"
collection: portfolio
permalink: /portfolio/diffusion-mapping/
excerpt: |
  <img src="/images/Diffusion-map1.png"
       alt="Comparison of nonlinear dimension-reduction methods"
       style="width: 100%; max-width: 850px; height: auto; margin: 1rem 0;">

  A Python implementation and analysis of Diffusion Maps for nonlinear dimensionality reduction and manifold learning.
---

[View the GitHub repository](PASTE-YOUR-DIFFUSION-REPOSITORY-URL-HERE){: .btn .btn--primary}

## Project Description

This project studies and implements Diffusion Maps, a nonlinear dimension-reduction method designed to recover low-dimensional geometric structure from high-dimensional data. Local similarities between observations are represented using a Gaussian kernel and normalized to construct a Markov transition matrix.

Powers of the transition matrix describe diffusion through the data over multiple time steps. Spectral decomposition of this matrix produces diffusion coordinates from its dominant eigenvalues and eigenvectors. The resulting representation preserves diffusion distance and reveals nonlinear structure that may not be visible in the original coordinate system.

The experiments compare Diffusion Maps with principal component analysis, multidimensional scaling, and Isomap. They also examine how the resulting embedding changes with diffusion time and sample size.

## Comparison of Dimension-Reduction Methods

![Comparison of PCA, MDS, Isomap, and Diffusion Maps](/images/Diffusion-map1.png)

*Comparison of PCA, multidimensional scaling, Isomap, and Diffusion Maps applied to a three-dimensional nonlinear manifold.*

## Effect of Diffusion Time

![Diffusion Maps across different diffusion times](/images/Diffusion-map2.png)

*Diffusion-map embeddings for increasing values of the diffusion time parameter.*

## Effect of Sample Size

![Diffusion Maps across different sample sizes](/images/Diffusion-map3.png)

*Diffusion-map embeddings across increasing sample sizes.*
