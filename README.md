# CV_Dicom_

## Table of Contents

- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Practice Reading and Processing DICOM Images](#practice-reading-and-processing-dicom-images)
- [Object Detection Model Development](#object-detection-model-development)
- [Semantic Segmentation Model Development](#semantic-segmentation-model-development)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributors](#contributors)

## Project Overview

This project is divided into three main tasks:
1. **Practice Reading and Processing DICOM Images**
2. **Object Detection Model Development**
3. **Semantic Segmentation Model Development**

Each task involves different aspects of computer vision and deep learning, utilizing datasets and models to achieve specific goals.

## Datasets

### DICOM Dataset
- A set of DICOM images provided in a zipped folder (`0003b3d648eb.zip`).
- The goal is to load, process, and visualize these medical images.

### COCO-2017 Dataset
- A large-scale object detection, segmentation, and captioning dataset.
- Contains images with multiple classes, annotations, and segmentation masks.
- For object detection, we focus on the "person" class.
- For semantic segmentation, we focus on the "person," "cat," and "car" classes.

## Practice Reading and Processing DICOM Images

### Objective
- Load and process DICOM images from a provided dataset.
- Find the middle slice from the volume.
- Visualize the slice using lung and bone window settings in a 1x2 grid.
- Save the two images as 16-bit depth PNG images.

## Object Detection Model Development

### Objective
- Load only the "person" class from the COCO-2017 dataset.
- Create train and test splits.
- Train an object detection model (e.g., YOLO, Faster R-CNN).
- Compute test performance using Intersection over Union (IOU).

## Semantic Segmentation Model Development

### Objective
- Load the "person," "cat," and "car" classes from the COCO-2017 dataset.
- Create train and test splits.
- Train a U-Net segmentation model.
- Compute test performance using mean Dice score and IOU.

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/visionary-insights.git
   cd visionary-insights
Follow the instructions in each respective directory for running the code and training the models.
Dependencies
Python 3.7+
NumPy
Pandas
Matplotlib
PyTorch
torchvision
pydicom
scikit-learn
fiftyone
pycocotools
Contributors
Sruthi Kasturi
