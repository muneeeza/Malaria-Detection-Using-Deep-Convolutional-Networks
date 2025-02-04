# Malaria Detection Using Deep Convolutional Networks
This repository contains the code and resources for a deep learning-based malaria detection system. The project leverages Convolutional Neural Networks (CNNs) to identify malaria infections from blood smear images, featuring both binary and multiclass classification models. A user-friendly GUI built with Gradio ensures easy interaction with the models.

## Table of Contents
  1. Introduction

  2. Features

  3. Usage

  4. Technologies Used

  5. Contributors

## 1. Introduction 
Malaria is a life-threatening disease, especially in low-resource settings where diagnostic tools are scarce. This project introduces a deep learning solution for malaria detection using CNNs. The system consists of:

  - A binary classifier to detect malaria infections.

  - A multiclass classifier to identify specific Plasmodium species.

The models achieve 96% accuracy for binary classification and 89% for multiclass classification. Integrating a Gradio-based GUI enhances usability, allowing non-technical users to interact with the system effortlessly.

## 2. Features 
- Binary Classification: Detects if a blood sample is infected with malaria.

- Multiclass Classification: Identifies specific Plasmodium species in infected samples.

- Gradio GUI: Provides an intuitive web-based interface for image upload and result visualization.

- High Accuracy: Achieves 96% accuracy for binary and 89% for multiclass classification.

## 3. Usage 
- Run the GUI: After executing python Malaria_Detection_WebInterface.ipynb, a Gradio interface will open in your browser.

- Upload an Image: Upload a blood smear image.

- View Results: The system will first classify the image as infected or uninfected. If infected, it will identify the specific malaria subtype.

## 4. Technologies Used 
- Deep Learning Framework: TensorFlow, Keras

- Model Architecture:

    + Custom CNN for binary classification

    + MobileNetV2 for multiclass classification (transfer learning)

- GUI: Gradio

## Contributers 
- Syed Muhammad Yamann

- Muneeza Iftikhar

- Hafsa Hafeez Siddiqui



