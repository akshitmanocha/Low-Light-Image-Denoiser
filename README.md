# Low-Light Image Enhancement

This repository contains the implementation of a low-light image enhancement model that was used in the NTIRE-2024 Low Light Image Enhancement competition.

## Model Overview

The model utilized in this project is based on the ImageNet architecture, specifically tailored for low-light image enhancement. This architecture integrates several advanced techniques to improve image quality, including:

- **Spatial Information Enhancement**: Improves the detail and structure of low-light images.
- **Intricate Feature Capture**: Effectively captures detailed features in low-light conditions.
- **Multi-Scale Feature Refinement**: Refines features at multiple scales for better image quality.
- **Effective Noise Suppression**: Reduces noise while preserving important image details.

## Performance

The enhanced images produced by this model achieved an average Peak Signal-to-Noise Ratio (PSNR) value of 20 dB on the training set.

## Training Details

- **Training Platform**: Kaggle Notebook
- **GPU Used**: NVIDIA Tesla P100

## Reference

The model architecture and training methodology are based on the research presented in the following paper:
- [Research Paper](https://arxiv.org/pdf/2404.14248)
