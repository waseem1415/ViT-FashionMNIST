# ViT-FashionMNIST
Implementation of Vision Transformer (ViT) on Fashion-MNIST for image classification with reproducible, modular, and accessible PyTorch code.

# Vision Transformer (ViT) on Fashion-MNIST

## Description
This repository contains a professional and reproducible implementation of the Vision Transformer (ViT) applied to the Fashion-MNIST dataset. It demonstrates modular PyTorch code for training, evaluation, and visualization of results.

## Repository Structure




---

## Features

- Modular Vision Transformer (ViT) architecture implemented in PyTorch  
- Reproducible training with fixed random seeds  
- Training, validation, and test workflows  
- Evaluation with confusion matrix and classification report  
- Visualization of loss and accuracy curves  
- Accessible plots with color-blind friendly palettes  
- Designed for easy extension to other datasets  

---

## Setup Instructions

1. **Clone the repository:**

```bash
git clone <repository_url>
cd ViT-FashionMNIST
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the notebook:

Open notebooks/ViT_FashionMNIST.ipynb and execute all cells to train the model, visualize results, and evaluate performance.

Usage
Notebook: Complete workflow from data loading to evaluation with detailed explanations and plots.

Scripts: Modular usage:

src/dataset.py → Data loading and preprocessing

src/model.py → Vision Transformer architecture

src/train.py → Training loop with validation

src/evaluate.py → Test evaluation, confusion matrix, and metrics

src/utils.py → Helper functions for plotting, seed setting, etc.

Outputs: Training/validation loss, accuracy plots, confusion matrix, and optional model checkpoints are stored in outputs/.

Results
Test Accuracy: ~89%

Analysis:

High accuracy on easily distinguishable classes (e.g., trousers, sneakers)

Slight confusion on visually similar items (e.g., shirts vs t-shirts)

Visualization: Includes training/validation loss curves, accuracy curves, and a confusion matrix for easy interpretation and reproducibility.

License
This project is licensed under the MIT License, allowing reuse, modification, and redistribution with proper attribution.
