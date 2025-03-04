# Diagnosis of Diabetic Retinopathy through Image Analysis using Deep Learning

## Overview
Diabetic retinopathy (DR) is a **serious and irreversible** condition that primarily affects individuals with **diabetes mellitus**. It is one of the leading causes of **blindness worldwide**. As a result of chronic **hyperglycemia**, alterations in retinal blood vessels lead to:

- Microaneurysms
- Hemorrhages
- Exudates
- Pathological neovascularization

Early diagnosis remains a **challenge** for ophthalmologists, as determining the stage of the disease requires specialized interpretation of retinal fundus images. **Convolutional Neural Networks (CNNs)** have been successfully applied to address this issue, offering **high-accuracy solutions** that minimize human error.

---

## Project Objective
The primary goal of this project is to **develop and apply five (5) deep learning models** under the same preprocessing conditions on the same dataset, to determine which model performs best in classifying **diabetic retinopathy stages**. The deep learning models implemented are:

- AlexNet
- VGG19
- DenseNet
- ResNet50
- EfficientNetB0

---

## Dataset
The dataset used for this project was sourced from the **Kaggle** platform and consists of **3,662 retinal fundus images**. These images are labeled into five categories:

| Category            | Description                             |
|--------------------|---------------------------------|
| No DR             | No Diabetic Retinopathy         |
| Mild              | Early-stage DR                  |
| Moderate          | Progressing DR                  |
| Severe           | High risk of vision loss        |
| Proliferative DR | Advanced stage with neovascularization |

---

## Development Environment
- The project was developed using **Jupyter Notebook** within **VSCode**.
- **Python Libraries Used:**
  - TensorFlow & Keras
  - OpenCV
  - NumPy
  - Pandas

---

## Results
Each model's performance is compared based on:
- Accuracy
- Precision
- Recall
- F1-score

To determine which model provides the **most accurate classification** of diabetic retinopathy.

---


