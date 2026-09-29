# Iterative Fine-Tuning with ResNet50

## Overview
This project demonstrates iterative fine-tuning for Computer Vision using TensorFlow to classify Chest X-Ray images: Normal vs Pneumonia.

## Dataset
Chest X-Ray Pneumonia Dataset from Kaggle

## Method
1. **V1 - Transfer Learning**: Freeze ResNet50 base, train new layers for 5 epochs
2. **V2 - Fine Tuning**: Unfreeze base model, train all layers with low learning rate for 5 epochs

## Results
- **V1 - Transfer Learning**: 75.7% Accuracy
- **V2 - Fine Tuning**: **97.5% Accuracy**

### Accuracy Graph
![Accuracy Graph](Iterative%20Fine%20Tuning%20Accuracy.jpg)

## Tech Stack
`Python` `TensorFlow` `Keras` `ResNet50` `Transfer Learning` `Google Colab`

## How to Run
1. Open `cv_finetune_project.ipynb` in Google Colab
2. Connect to T4 GPU Runtime
3. Run all cells
