# Natural Scene Classification with CNN and Transfer Learning

## Introduction

This project aims to classify natural scene images into one of six predefined categories: Building, Sea, Forest, Glacier, Street, and Mountain. Utilizing a dataset that comprises 14,000 training images and 3,000 test images, the project employs a custom Convolutional Neural Network (CNN) model as well as three pre-trained models: VGG16, ResNet50, and Inception V3. The objective is to compare these models based on accuracy, recall, and precision to determine the most effective architecture for scene recognition tasks.

## Table of Contents

- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Models](#models)
- [Evaluation Metrics](#evaluation-metrics)
- [Dependencies](#dependencies)
- [Configuration and Training](#configuration-and-training)
- [Results](#results)

## Installation

To set up the project environment, ensure you have Python installed on your machine. Then, install the necessary libraries using the following command:

```bash
pip install numpy pandas matplotlib seaborn tensorflow scikit-learn
```

## Dataset

The dataset used in this project is the Intel Image Classification dataset, which is categorized into six classes. The dataset structure is as follows:

- Training set: 14,000 images
- Test set: 3,000 images

## Usage

To start training and evaluating the models, run the script provided in the project. Ensure you have the dataset organized into the correct directory structure as mentioned above.

## Models

The project explores the following models for scene classification:

- Custom CNN Model
- VGG16
- ResNet50
- Inception V3

Each model's performance is evaluated based on accuracy, recall, and precision metrics.

## Evaluation Metrics

The models are evaluated using the following metrics:

- Accuracy
- Recall
- Precision

These metrics provide insights into the models' effectiveness in classifying the scenes correctly.

## Dependencies

The project requires the following Python libraries:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow

## Configuration and Training

The project uses a batch size of 32 and image dimensions of 150x150 for training. Data augmentation techniques such as rotation, width shift, height shift, shear, zoom, and horizontal flip are applied to the training data. Early stopping and model checkpoints are used to monitor the training process.

## Results

After training, the models' performances are compared to identify the most suitable architecture for scene recognition tasks. The comparison is based on the calculated accuracy, recall, and precision metrics.
