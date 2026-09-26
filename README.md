# AIClassifier
# Cat-Dog-Panda Image Classification using Transfer Learning

A PyTorch-based image classification project that uses **Transfer Learning with a pretrained ResNet18 model** to classify images into three categories:

- 🐱 Cats
- 🐶 Dogs
- 🐼 Panda

The project uses a Kaggle image dataset and supports **GPU acceleration using NVIDIA CUDA**.

---

##  Project Overview

Image classification is a computer vision task where a model learns to identify the class or category of an input image.

In this project, a pretrained **ResNet18** model is used as the feature extractor. The pretrained convolutional layers are frozen, and the final classification layer is replaced with a custom classifier designed for three classes.

### Classification Classes

| Class | Label |
|---|---:|
| Cats | 0 |
| Dogs | 1 |
| Panda | 2 |

---

## 🎯 Objectives

The main objectives of this project are:

- Download and prepare an image classification dataset.
- Perform image preprocessing and augmentation.
- Verify GPU and CUDA support.
- Apply Transfer Learning using ResNet18.
- Freeze pretrained convolutional layers.
- Train a custom classification head.
- Evaluate the model using test accuracy and test loss.
- Generate a confusion matrix.
- Display example predictions.
- Save the trained model for future use.

---

## 📂 Dataset

The dataset used in this project is:

**Cats, Dogs and Pandas Images**

Kaggle Dataset:

https://www.kaggle.com/datasets/gpiosenka/cats-dogs-pandas-images

The dataset contains:

- 1,000 cat images
- 1,000 dog images
- 1,000 panda images

### Original Dataset

```text
3,000 images
├── cats   → 1,000
├── dogs   → 1,000
└── panda  → 1,000
