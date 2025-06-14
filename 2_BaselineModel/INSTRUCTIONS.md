# Baseline Model

## Overview

The purpose of this milestone is to establish a baseline model for your project. A baseline model is a simple model that serves as a point of comparison for any subsequent, more complex models you may build.

## Guidelines

Provide information on the following issues:

- **Choice of Model**: The baseline model uses MobileNetV2 with Transfer Learning. MobileNetV2 is a lightweight convolutional neural network (CNN) optimized for mobile and embedded vision applications. 

- **Feature Selection**: The input features are raw images belonging to two classes:

- NoActivity

- YesActivity

Each image is:

- Resized to 224×224 pixels (standard for MobileNetV2),

- Converted to RGB format,

- Labeled using binary encoding (0 or 1).

- **Implementation**:

- Framework: TensorFlow / Keras
- Data Source: Folder with subdirectories for each class
Image Handling:
- Used image_dataset_from_directory() for loading
- Split into training and validation sets (80/20 split)

Model Architecture:
- Based on MobileNetV2(weights='imagenet', include_top=False)
- Custom classification head with GlobalAveragePooling2D + Dense layer for binary output

Training:
- Batch size: 32
- Optimizer: Adam
- Loss function: Binary crossentropy

- **Evaluation**:
The model is evaluated using:
- Validation Accuracy
- Loss Curve over training epochs

Follow the instructions provided in brackets in the [Jupyter/Colab notebook](baseline_model.ipynb) in this folder.

## Submission

Complete the [Jupyter/Colab notebook](baseline_model.ipynb) to conduct your implmentation of the baseline model.
