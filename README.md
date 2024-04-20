# Health Care Data Project

## Overview

This repository contains code for a health care data project. The goal is to classify chest X-ray images into two categories: "PNEUMONIA" and "NORMAL." The code is written in Python using Keras and OpenCV libraries.

## Data

- The dataset consists of chest X-ray images.
- Two classes: "PNEUMONIA" and "NORMAL."
- Images are grayscale and resized to 150x150 pixels.

## Code Structure

1. **Data Loading and Preprocessing**:
    - Images are loaded from the specified directories (`train`, `test`, and `val`).
    - Images are converted to grayscale and resized.
    - Labels are assigned based on the folder structure.

2. **Model Architecture**:
    - A Convolutional Neural Network (CNN) is used.
    - Layers include Conv2D, MaxPool2D, Flatten, Dropout, and BatchNormalization.
    - The model architecture is not explicitly shown in the provided snippet.

3. **Data Visualization**:
    - The first and last training images are displayed.
    - The labels (PNEUMONIA or NORMAL) are shown as titles.

## Usage

1. **Data Preparation**:
    - Ensure the dataset is organized in the specified folder structure.
    - Adjust the `img_size` parameter if needed.

2. **Training the Model**:
    - Train the CNN model using the provided data.
    - Monitor training progress using callbacks (e.g., ReduceLROnPlateau).

3. **Evaluation**:
    - Evaluate the model using test data.
    - Compute classification metrics (e.g., accuracy, precision, recall).

## Dependencies

- Python 3.x
- Keras
- OpenCV
- Other necessary libraries (not shown in the snippet)
