# 🚗 Vehicle Number Plate Detection

A deep learning project to detect vehicle license plates from images using Faster R-CNN with a ResNet50-FPN backbone. Trained on the [Kaggle Number Plate Dataset](https://www.kaggle.com/datasets/aslanahmedov/number-plate-detection).

## 🔍 Features
- XML Annotation parsing
- Custom PyTorch Dataset class
- Transfer learning with Faster R-CNN
- Bounding box visualization on test images

## 🧠 Model
- Architecture: Faster R-CNN (ResNet50-FPN)
- Framework: PyTorch
- Epochs: 10
- Loss ⬇: ~0.08 at best

## 📁 Dataset
- Source: Kaggle
- Format: Pascal VOC (JPEG + XML)

## 🚀 Setup & Training

```bash
pip install torch torchvision pillow opencv-python
# Upload kaggle.json via Colab to access dataset

# Then run training script (see notebook or .py)
