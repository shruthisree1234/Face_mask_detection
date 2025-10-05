# Face Mask Detection

## Overview

This project implements and compares deep learning models for real-time face mask detection using computer vision. The focus is on building efficient pipelines for recognizing whether individuals in images or video streams are wearing face masks—an important application for public health and safety.

## Project Structure

- **BasicCNN_mask.ipynb** — Builds and trains a basic Convolutional Neural Network for mask detection.
- **MobilenetV2_mask.ipynb** — Utilizes the MobileNetV2 architecture for lightweight, rapid mask classification.
- **Nasnet_mask.ipynb** — Experiments with NasNet, a highly optimized neural network model for visual recognition.
- **BasicCNN_test.ipynb, Mobilenetv2_test.ipynb, Nasnet_test.ipynb** — Evaluate trained models on validation/test sets, visualizing predictions and accuracy.

## Approach

- **Data Preparation:** Preprocess and augment images for training/testing mask detection models.
- **Model Training:** Adapt and fine-tune various deep learning architectures (CNN, MobileNetV2, NasNet) to classify mask/no-mask.
- **Evaluation:** Assess model performance using metrics such as accuracy, confusion matrix, and sample predictions.

## Key Features

- Side-by-side implementation of multiple state-of-the-art deep learning models.
- Flexible notebooks for both training and testing/evaluation.
- Easily adaptable for deployment with cameras or video feeds.

## Applications

- Public health monitoring and compliance (e.g., airports, transport hubs).
- Automated safety systems in workplaces, schools, or events.
- Computer vision and transfer learning.


