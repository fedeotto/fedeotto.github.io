---
title: "NA-LR: Noise-Adaptive Low-Rank Parameterisation for Efficient Diffusion Models"
authors:
    - Jingyuan Wang
    - Federico Ottomano
    - Yingzhen Li
abstract: "Scaling diffusion models delivers state-of-the-art image quality but at substantial training and inference cost. Low rank parameterisation effectively attacks both of these bottlenecks. We empirically find that the effective ranks of weights and gradients in diffusion models are noise-dependent: as noise increases, updates concentrate in lower-dimensional subspaces. This makes static low-rank parameterisations inefficient, underallocating capacity to low-noise (hard) steps while overallocating to high-noise (easy) ones. We propose Noise-Adaptive Low-Rank parameterisation (NA-LR) that uses a nested rank schedule: harder timesteps with less noise are allocated more rank slices, while easier ones with high noise require fewer. This is implemented via per-sample masking at training time and structured rank slicing at inference time. Coupled with a timestep curriculum learning, which initially restricting the timestep sampling range, we reduce both inference and training compute by achieving training-time slicing. On DiT-S/2 across CIFAR-10 and CelebA, our method improves FID by 15–26% over static low-rank at matched compute, cuts inference FLOPs by up to 25% at matched parameters with negligible FID change, and lowers training FLOPs by up to 12%"
categories:
    - Diffusion
link: https://rethinking-ai.github.io/assets/papers/9_NA_LR_Noise_Adaptive_Low_Ran.pdf
code: 
venue: EurIPS 2025 (Rethinking AI Workshop)
thumbnail: nalr.png
layout: abstract
order: 6
---
