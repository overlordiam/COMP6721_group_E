# Gastrointestinal Disease Classification using Deep Learning
## Overview

This repository contains the code for an advanced deep learning project focused on classifying gastrointestinal diseases through medical images. The project employs ResNet50, VGG16, and DenseNet architectures on various datasets with differing class sizes and overlaps. Additionally, transfer learning techniques are explored to draw further insights into model behavior.

## Table of Contents

- [Background](#background)
- [Datasets](#datasets)
- [Models](#models)
- [Transfer Learning](#transfer-learning)
- [Results](#results)
- [Usage](#usage)

## Background

Medical image analysis holds immense potential in disease diagnosis and prognosis. This project aims to leverage deep learning to accurately classify gastrointestinal diseases using medical images, contributing to advancements in healthcare technology.

## Datasets

Three datasets were used, each representing different levels of disease classification complexity: 4-classes, 8-classes, and 23-classes. Overlapping classes were incorporated to mimic real-world scenarios and test the robustness of the models.

## Models

- **ResNet50**: A widely used deep convolutional neural network architecture known for its efficiency in image recognition tasks.
- **VGG16**: A classic architecture known for its simplicity and effectiveness in various image classification problems.
- **DenseNet**: A model that emphasizes feature reuse through dense connections, enhancing gradient flow and encouraging feature propagation.

## Transfer Learning

Transfer learning was employed to enhance model performance. Pre-trained versions of the models were fine-tuned on the specific gastrointestinal disease classification task, taking advantage of the valuable features learned from large datasets like ImageNet.

## Results

Experimental results demonstrate the impact of varying dataset complexity and model architecture on classification accuracy. It is observed that as the size of the dataset increases, the larger models perform better while the smaller models suffer mild overfitting problems. Overall, ResNet50 shows the best performance on the 8-class and 23-class datasets while VGG16 performs the best on the 4-class dataset. Transfer learning consistently boosted performance across models, underscoring its importance in medical image analysis.

## Usage

To use this repository, follow these steps:

1. Clone the repository: `git clone https://github.com/overlordiam/GastroInstestinal_Image_Classification .git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Explore the notebooks for dataset preprocessing, model training, and analysis.
