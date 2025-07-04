# Brain Tumor Detection Using VGG16

## Overview
This project detects brain tumors in MRI scans using a transfer learning approach based on the VGG16 CNN model.

## Dataset
A curated dataset with labeled images (tumor / no tumor) was used. Images were resized to 150x150 pixels.

## Model Architecture
- Base: VGG16 (pretrained on ImageNet)
- Custom dense head with dropout
- Binary classification (sigmoid)

## Training Details
- Optimizer: Adam
- Loss: Binary Crossentropy
- Epochs: 5

## How to Use
1. Load `brain_tumor_vgg16.h5`
2. Use `predict_brain_tumor()` function to test any MRI image

## Results
- Sample Prediction Output:
  - `yes_1.jpg → Tumor Detected`
  - `yes_2.jpg → No Tumor`
  - 'validation accuracy=0.5'
    

