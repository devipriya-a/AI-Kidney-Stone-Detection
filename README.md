# AI-based Kidney Stone Detection using CT Imaging

## Project Overview
This project presents a two-stage AI pipeline for automatic kidney stone
detection and localization from CT scan images.

## Methodology
- **Stage 1:** CNN-based binary classification (Stone / No Stone)
- **Stage 2:** YOLOv8-based object detection for stone localization

## Dataset
- Source: Mendeley Axial CT Imaging Dataset (2025)
- Images: 3,364 original + 35,457 augmented
- Preprocessing: Resize to 224×224, normalization
- Split: 80% Training / 20% Testing

## Tools & Technologies
- Python
- TensorFlow / Keras
- YOLOv8
- OpenCV
- NumPy
- scikit-image

## Results
- CNN Classification Accuracy: **86%**
- YOLOv8 Detection mAP: **0.85**

## Files
- 📊 `ppt/` – Project presentation
- 💻 `code/` – Python implementation (segmentation + object detection)

## Authors
- Devipriya A (2024DSS1005)
- Kartik Srivastava (2024DSS1008)

MSDSM – IIT Ropar  
Academic Year: 2025–26
