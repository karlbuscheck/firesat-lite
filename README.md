# FireSat-Lite:A Deep Learning Wildfire Detection Model

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/karlbuscheck/firesat-lite/blob/main/firesat_lite.ipynb)

---

### Project Overview

Inspired by Google’s [FireSat](https://blog.google/technology/research/first-firesat-images/), this project builds and compares deep learning architectures to detect wildfires (Fire, Smoke, Non-Fire) using the 43K image [FireEye](https://www.kaggle.com/datasets/amerzishminha/forest-fire-smoke-and-non-fire-image-dataset) dataset.

To ensure **rigorous and unbiased results**, the entire modeling process adheres to strict machine learning best practices, including using global random seeds for reproducibility, dedicated train/validation/test splits, and strategic **EarlyStopping** to combat overfitting. The final, best-performing model achieved a highly competitive and unbiased **95.30% Test Accuracy**.

The dataset consists of **nearly 43K images**, distributed across **three balanced classes**:
1. Fire
2. Smoke
3. Non-Fire

---

### Key Highlight

Our champion model, a **Convolutional Neural Network (CNN) with strategic Dropout**, achieved an unbiased **95.30% Test Accuracy** on the unseen test set, proving that strong regularization is critical for generalizing on this high-performance task.

---

### Project Roadmap (Summary of Techniques Used)
* **Clean Data Split:** Ensures a fixed train/validation/test split for a fair final evaluation.
* **Baseline Benchmarking:** A fully connected Deep Neural Network (DNN) used as a rigorous benchmark.
* **Overfitting Mitigation:** Systematic testing of **Data Augmentation** and strategic **Dropout** to achieve optimal model generalization.

---

### Next Steps

Given the model's high performance, the current architecture is a highly effective, production-ready solution. Future work would explore **transfer learning** with pre-trained models like MobileNetV3 to tackle larger, higher-resolution datasets or explore marginal accuracy gains.
