# xai-duck-classifier
오리 이미지 분류 모델 및 Android 앱

This project builds an image classification system using deep learning to distinguish Call Ducks from similar bird species. It also includes an Android application that allows users to identify bird species from images.

---

## Overview
- This project was inspired by the difficulty of visually distinguishing Call Ducks from similar birds like Pekin ducks, Mallards, and geese.
- A pre-trained MobileNetV3-Large model was fine-tuned to classify five bird classes: Call Duck, Pekin, Mallard, Goose, and Other.
- Grad-CAM was used to visualize which parts of the image the model focuses on when making a decision.
- The final model was converted and integrated into a mobile Android application using PyTorch Mobile.

---

## Features

- Image classification using MobileNetV3-Large
- Visualization of model attention using Grad-CAM
- Mobile app for instant bird species recognition

---

## Tools Used

- Python, PyTorch, torchvision
- MobileNetV3-Large (transfer learning used for tuning)
- Grad-CAM for explainable AI
- Android Studio
- Google Colab for training and testing

---
