# Porous Media Solver using CNN
A deep learning approach to accelerate computational fluid dynamics (CFD) simulations in porous media using Convolutional Neural Networks.
## Project Overview
This repository contains the implementation of a CNN-based solver that aims to provide fast and accurate predictions of fluid flow patterns in porous media. The model serves as an efficient alternative to traditional numerical methods while maintaining high accuracy.
## Key Features
1. CNN architecture optimized for fluid flow prediction
2. Custom loss functions for physics-informed training
3. Data preprocessing pipeline for CFD simulation data
4. Visualization tools for flow field analysis
5. Model evaluation and error analysis utilities
## Usage
The project uses Jupyter notebooks for model training and evaluation:

### Training & Model Development
- `cavityConv2D-V001-channel-11-uvT-layer-3-8-16-32-batch-32-swish.ipynb`
  - Main training notebook
  - Implements CNN architecture with 11 channels
  - Uses swish activation function
  - Contains model architecture with 3-8-16-32 layer configuration
  - Batch size of 32 for training

### Model Evaluation & Testing
- `Load-model-from-checkpoint.ipynb`
  - Loads pretrained models from checkpoints
  - Contains visualization functions for model predictions
  - Implements error analysis and performance metrics
  - Includes functions for comparing predicted vs actual flow fields

### Analysis & Visualization
- `test.ipynb`
  - Contains data analysis utilities
  - Text analysis and word frequency visualization
  - Used for miscellaneous testing and debuggin

## Results
The model demonstrates:
1. Significant speedup compared to traditional CFD solvers
2. High accuracy in predicting velocity and pressure fields
3. Robust performance across different porous media configurations
