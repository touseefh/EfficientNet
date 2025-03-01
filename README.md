# EfficientNetB3 Image Classification Pipeline
## Overview
This project is about crafting an image classification model with EfficientNetB3—a super-efficient CNN—using TensorFlow. I fine-tuned it for a custom 6-class dataset, starting with pre-trained ImageNet weights. The workflow handles data prep, augmentation, training, and evaluation, all while keeping things visual and insightful.

## Features
### Data Setup:
Pulls data from Google Drive, applies augmentation, and splits it into training/validation sets.
### Model:
Builds on EfficientNetB3 with custom layers (think dense, dropout, and softmax) for 6-class classification.
### Training:
Uses categorical cross-entropy, Adam optimizer, and callbacks like EarlyStopping to keep it sharp.
### Evaluation:
Checks performance with accuracy, confusion matrices, and a detailed classification report.
### Requirements
1. Python 3.x
2. Libraries: TensorFlow, EfficientNet, Scikit-learn, Matplotlib
