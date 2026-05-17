# CNN-Based Computer Vision Prototype for Defect Classification

## Project Overview

This project demonstrates a Convolutional Neural Network (CNN) based computer vision solution for image classification.

The objective of the project is to automatically classify surface images into one of the following categories:

- Dent
- Normal
- Scratch
- Stain

The project uses TensorFlow/Keras to build, train, and evaluate a CNN model capable of learning visual defect patterns from image data.

---

# Problem Statement

The dataset represents an image classification problem where each image belongs to exactly one defect category.

The goal is to train a CNN model that can accurately identify the defect type present in an image.

---

# Dataset Description

The dataset contains 4 image classes:

| Class | Description |
|---|---|
| Dent | Images containing dents |
| Normal | Images without defects |
| Scratch | Images containing scratches |
| Stain | Images containing stains |

## Dataset Summary

| Class | Number of Images |
|---|---|
| Dent | 120 |
| Normal | 120 |
| Scratch | 120 |
| Stain | 120 |

Total images = 480

The dataset is balanced because all classes contain an equal number of images.

---

# Project Structure

```text
part-2-cnn-computer-vision/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
│
├── sample_predictions/
│   └── prediction_outputs.png
│
└── results/
    ├── accuracy_loss_curves.png
    └── confusion_matrix.png


```python

```
