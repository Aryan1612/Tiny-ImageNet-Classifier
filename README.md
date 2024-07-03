# Tiny ImageNet Classifier | Self Project April 2024 - May 2024

## Overview
This repository documents a self-project focused on building a classifier for the TinyImageNet dataset using deep learning techniques with PyTorch. The project explores batch size effects and condition number trends in model training to optimize performance and stability.

## Implemented Architecture and Techniques

### ResNet-18 Architecture
- **Objective:** Implemented the ResNet-18 architecture for image classification tailored to the TinyImageNet dataset.
- **Implementation:** Utilized PyTorch framework for efficient model training and evaluation.

### Data Augmentation
- **Techniques Used:** Applied diverse PyTorch data transformations to augment dataset variability and improve model generalization.
- **Benefit:** Enhanced model robustness and performance on diverse image data.

### Batch Size Effects
- **Experimentation:** Evaluated model performance across a range of batch sizes (64, 256, 512, 1024, 4096).
- **Observations:** Noted trends in accuracy, training time, and computational efficiency with varying batch sizes.

### Hyperparameter Tuning
- **Optimization:** Conducted thorough hyperparameter tuning to enhance model accuracy.
- **Key Parameter:** Favored a learning rate of 0.001 for significantly improved accuracy on validation data.

### Condition Number Analysis
- **Investigation:** Explored condition numbers across different batch sizes during training.
- **Insights:** Provided insights into model stability and convergence based on condition number trends.

## Project Organization

### Files and Notebooks
- **Implementation:** Code files and Jupyter Notebooks (`*.ipynb`) detail the implementation, experimentation, and analysis.
- **Visualization:** Matplotlib used for visualizing data transformations, batch size effects, and model performance metrics.

## Usage
- Clone the repository and explore the provided Jupyter Notebooks for detailed implementation steps and analysis.
- Ensure PyTorch and necessary libraries are installed to replicate experiments and visualize results.
