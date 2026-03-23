# Struct-DP: Structure-Aware Local Differential Privacy for Multimodal Collaborative Inference

> **🚧 Status: Active Preparation**
> The source code is currently being cleaned up and reorganized. We will release the full training and evaluation scripts, along with the pre-trained weights, in the near future. 

This repository contains the official implementation of the paper: **"Structure-Aware Local Differential Privacy for Multimodal Collaborative Inference in Cloud–Edge Distributed Learning System"**.

## 📖 Overview

To address the severe feature-oriented reconstruction attacks in cloud-edge collaborative inference, we propose **Struct-DP**, a two-stage structure-aware local differential privacy framework. 

Our framework fundamentally optimizes the privacy-utility trade-off through two key mechanisms:
1. **Shared-Private Representation Decoupling**: Explicitly disentangles task-relevant shared semantics from edge-retained private factors.
2. **Structure-Aware Noise Injection**: Precisely calibrates the noise scale for each heterogeneous dimension based on utility and privacy loss gradients.

![Framework Overview](./framework.png) *(Note: Please upload your Figure 1 here)*

## 🚀 To-Do List

We are actively working on releasing the following assets:
- [ ] Core implementation of the representation decoupling module.
- [ ] Structure-aware noise generation and allocation algorithms.
- [ ] End-to-end evaluation scripts on CMU-MOSEI datasets.
- [ ] Pre-trained edge front-end encoders.

## 🛠️ Environment Setup
*(Coming soon)*

## 📝 Citation
If you find our work helpful, please consider citing our paper (BibTeX will be updated upon acceptance).
