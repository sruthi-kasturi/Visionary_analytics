# Visionary Analytics

Welcome to **Visionary Analytics**! This repository is dedicated to the innovative application of deep learning techniques for object detection and semantic segmentation using the COCO-2017 dataset. Our goal is to provide a comprehensive toolkit for accurately detecting and segmenting objects in images, leveraging state-of-the-art models.

## Table of Contents

- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Object Detection Model Development](#object-detection-model-development)
- [Semantic Segmentation Model Development](#semantic-segmentation-model-development)
- [Results](#results)

## Project Overview

**Visionary Analytics** focuses on two main tasks in computer vision:
1. **Object Detection Model Development**
2. **Semantic Segmentation Model Development**

Each task utilizes advanced deep learning models to achieve high accuracy and efficiency in identifying and segmenting objects within images.

## Datasets

### COCO-2017 Dataset
The COCO-2017 dataset is a large-scale object detection, segmentation, and captioning dataset. It contains over 200,000 labeled images with annotations for multiple classes. For this project, we focus on:
- **Object Detection:** "Person" class
- **Semantic Segmentation:** "Person," "Cat," and "Car" classes

## Object Detection Model Development

### Objective
- Load the "person" class from the COCO-2017 dataset.
- Create training and test splits.
- Train an object detection model (e.g., YOLO, Faster R-CNN).
- Evaluate model performance using Intersection over Union (IoU).

## Semantic Segmentation Model Development

### Objective
- Load the "person," "cat," and "car" classes from the COCO-2017 dataset.
- Create training and test splits.
- Train a U-Net segmentation model.
- Evaluate model performance using mean Dice score and IoU.

## Results

### Object Detection
- **IoU:** Achieved a mean IoU score of 0.63 on the test dataset for object detection.

### Semantic Segmentation
- **Dice Score:** Achieved a mean Dice score of 0.36.
- **IoU Score:** Achieved a mean IoU score of 0.32 for semantic segmentation.

For questions or collaboration, feel free to contact me at skastur6@asu.edu

