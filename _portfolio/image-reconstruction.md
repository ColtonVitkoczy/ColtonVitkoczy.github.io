---
title: "Deep Learning for Image Reconstruction from Incomplete Data"
excerpt: "A Python and PyTorch project for reconstructing incomplete or corrupted images using neural networks and proximal-gradient optimization."
collection: portfolio
permalink: /portfolio/image-reconstruction/
---

[View the GitHub repository](https://github.com/ColtonVitkoczy/sparse-image-reconstruction){: .btn .btn--primary}

## Project Description

This project develops a Python machine-learning pipeline for reconstructing incomplete or corrupted images. Using TorchVision MNIST data, images are partially masked to simulate missing information, and an AI model is trained to recover the underlying image structure.

The project combines neural-network training in PyTorch with proximal-gradient optimization. Reconstruction quality is evaluated by comparing the recovered images with the original images and measuring reconstruction error.

## Results

![Original, masked, and reconstructed images](/images/projects/image-reconstruction-results.png)

![Training and reconstruction error](/images/projects/image-reconstruction-error.png)
