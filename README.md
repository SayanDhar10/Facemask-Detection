# FaceMask Detection Using Deep Learning Approach

## 🚀 Overview

This repository showcases a deep learning-powered face mask detection system developed with PyTorch and the MobileNetV2 architecture. The model is trained to categorize images into two distinct classes:

- `with_mask`
- `without_mask`

The project offers a full-fledged pipeline encompassing data preprocessing, model training, validation, performance evaluation, and inference.

---

## 🚀 Features

- Utilizes the MobileNetV2 architecture, tailored for face mask detection.
- Incorporates data augmentation techniques to enhance model generalization.
- Includes automated splitting of data into training and validation sets.
- Visualizes training performance with accuracy and loss graphs.
- Supports model saving and loading for easy inference.
- Provides sample predictions on test images for demonstration.

---

<div align="center">

## 🧠 Model Architecture Details

| **Parameter**         | **Value**                         |
|-----------------------|-----------------------------------|
| Base Model            | MobileNetV2                       |
| Input Image Size      | 224 x 224 pixels                  |
| Number of Classes     | 2 (with_mask, without_mask)       |
| Optimizer             | Adam                              |
| Learning Rate         | 0.001                             |
| Loss Function         | CrossEntropyLoss                  |
| Batch Size            | 32                                |
| Number of Epochs      | 20                                |

</div>

---

## 📊 Model Outputs

<div align="center">
  <img src="https://github.com/SayanDhar10/Facemask-Detection/blob/40ca3e6a961b4bcba33d9d2858f28217aeab8b9b/Output_Images/Accuracy_Curve.png" height="220px" style="margin-right: 10px;">
  <img src="https://github.com/SayanDhar10/Facemask-Detection/blob/40ca3e6a961b4bcba33d9d2858f28217aeab8b9b/Output_Images/Loss_Curve.png" height="220px">
</div>

<div align="center">
  <img src="https://github.com/SayanDhar10/Facemask-Detection/blob/40ca3e6a961b4bcba33d9d2858f28217aeab8b9b/Output_Images/confusion_matrix.png" height="300px" style="margin-right: 10px;">
  <img src="https://github.com/SayanDhar10/Facemask-Detection/blob/40ca3e6a961b4bcba33d9d2858f28217aeab8b9b/Output_Images/matrices_curve.png" height="300px">
</div>

---

## Sample Prediction

<div align="center">
  <img src="https://github.com/SayanDhar10/Facemask-Detection/blob/40ca3e6a961b4bcba33d9d2858f28217aeab8b9b/Output_Images/Sample_Output1.png" height="300px" style="margin-right: 10px;">
  <img src="https://github.com/SayanDhar10/Facemask-Detection/blob/40ca3e6a961b4bcba33d9d2858f28217aeab8b9b/Output_Images/Sample_Output2.png" height="300px">
</div>

---




