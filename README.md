# Point Cloud Diffusion Models for Automatic Implant Generation
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Static Badge](https://img.shields.io/badge/Project-page-blue)](https://pfriedri.github.io/pcdiff-implant-io/)
[![arXiv](https://img.shields.io/badge/arXiv-2303.08061-b31b1b.svg)](https://arxiv.org/abs/2303.08061)

This is the official PyTorch implementation of the MICCAI 2023 paper [Point Cloud Diffusion Models for Automatic Implant Generation](https://pfriedri.github.io/pcdiff-implant-io/) by Paul Friedrich, Julia Wolleb, Florentin Bieder, Florian M. Thieringer and Philippe C. Cattin.

## Paper Abstract
Advances in 3D printing of biocompatible materials make patient-specific implants increasingly popular. The design of these implants is, however, still a tedious and largely manual process. Existing approaches to automate implant generation are mainly based on 3D U-Net architectures on downsampled or patch-wise data, which can result in a loss of detail or contextual information. Following the recent success of Diffusion Probabilistic Models, we propose a novel approach for implant generation based on a combination of 3D point cloud diffusion models and voxelization networks. Due to the stochastic sampling process in our diffusion model, we can propose an ensemble of different implants per defect from which the physicians can choose the most suitable one. We evaluate our method on the SkullBreak and SkullFix dataset, generating high-quality implants and achieving competitive evaluation scores.

![](./media/overview_pipeline.png)

## Code availability
We are currently working on making the code for the paper available on this repository as soon as possible. Stay tuned!
