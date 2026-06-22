# Food-Image-Classification-Using-CNNs
CNN-based food image classification system built with TensorFlow and Keras, achieving up to 72% accuracy, with optimized training using early stopping and detailed evaluation using classification metrics.

## Overview
This deep learning project was developed as a final project to demonstrate image classification using CNNs.
The dataset contains 6 classes:
- Baked Potato
- Burger
- Crispy Chicken
- Fries
- Hot Dog
- Pizza

## Features
    - Image classification using CNN
    - Data preprocessing with ImageDataGenerator
    - Early stopping to prevent overfitting
    - Model evaluation with:
      - Accuracy
      - Loss curves
      - Confusion matrix
      - Classification report

## Results
### Model 1
  - Training Accuracy: 75%
  - Validation Accuracy: 69%
  - Test Accuracy: 70%

### Model 2 (Improved)
  - Training Accuracy: ~73%
  - Validation Accuracy: ~69%
  - Test Accuracy: 72%
-Model 2 shows better generalization and balanced performance.

## Insights
  - Strong performance on:
    - Crispy Chicken
    - Burger
    - Pizza

- Some confusion between:
    - Burger vs Hot Dog
    - Chicken vs Fries

## Techniques Used
  - CNN (Conv2D, MaxPooling, Dense)
  - Dropout
  - EarlyStopping
  - Data normalization
  - Image augmentation

# File Structure
  * ReadMe.md - project description
  * imageclassification_project1.ipynb - this is for project1
  * imageclassification_project2.ipynb

© 2025 Kusum Katwal
