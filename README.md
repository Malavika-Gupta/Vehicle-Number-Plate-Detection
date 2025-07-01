# 🚗 Vehicle Number Plate Detection

A deep learning project to detect vehicle license plates from images using Faster R-CNN with a ResNet50-FPN backbone. Trained on the [Kaggle Number Plate Dataset](https://www.kaggle.com/datasets/aslanahmedov/number-plate-detection).

## 📝 About

This project demonstrates end-to-end vehicle number plate detection using modern object detection techniques. It covers data annotation parsing, custom dataset creation, transfer learning, and bounding box visualization.
**Date of completion:** *November 2, 2024*

## 🔍 Features

* XML Annotation parsing
* Custom PyTorch Dataset class
* Transfer learning with Faster R-CNN
* Bounding box visualization on test images

## 🧠 Model

* Architecture: Faster R-CNN (ResNet50-FPN)
* Framework: PyTorch
* Epochs: 10
* Best Loss: \~0.08

## 📁 Dataset

* Source: Kaggle
* Format: Pascal VOC (JPEG + XML)

## 📸 Sample Outputs

| Example 1                                           | Example 2                                           | Example 3                                           |
| --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- |
| ![Output 1](./Screenshot%202025-07-01%20194844.png) | ![Output 2](./Screenshot%202025-07-01%20194856.png) | ![Output 3](./Screenshot%202025-07-01%20194907.png) |

## 🚀 Setup & Training

```bash
pip install torch torchvision pillow opencv-python
# Upload kaggle.json via Colab to access dataset

# Then run training script (see notebook or .py)
```
