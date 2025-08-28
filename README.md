# FireSat-Lite

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17OTAirYRfrpMoM4Qtdo6t_4H_ds_R3rQ)

*Click the badge above to explore the full notebook and run the code.*

## Project Overview
Inspired by Google's [FireSat](https://blog.google/technology/research/first-firesat-images/), an AI-powered constellation of satellites that will be able to detect any wildfire on Earth greater than 5x5 meters within 20 minutes, this project aims to build a collection of deep learning neural network models as proof of concept.

To train, validate and test the models, we'll utilize [FireEye](https://www.kaggle.com/datasets/amerzishminha/forest-fire-smoke-and-non-fire-image-dataset?utm_source=chatgpt.com), the Forest Fire, Smoke, and Non-Fire Image Dataset. The dataset consists of **nearly 43K images**, distributed across **three classes**: 

1. Fire 
2. Smoke  
3. Non-Fire

## Project Roadmap

- **Load, preprocess and explore the dataset** -- prepare images with resizing, batching and training/validation and test splits
- **Build the baseline model** -- a fully connected Deep Neural Network (DNN) as a benchmark
- **Train a collection of Convolutional Neural Networks (CNNs)** -- leverage spatial patterns in images for improved accuracy

## Key Highlight

Our best model reached **95.9% test accuracy**, surpassing our previous best of 92.5%. Along the way, we explored **data augmentation** and **Dropout** to combat overfitting. Up next: **FireSat–Lite, Version 2**, where we’ll experiment with fine-tuning pre-trained models such as MobileNetV3.

Let's dive in.

