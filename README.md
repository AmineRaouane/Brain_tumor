# Brain Tumor Detection Project

![Brain Tumor](images/brain_tumor.jpg)

## Overview

This project aims to develop a Brain Tumor Detection system using image processing techniques and machine learning algorithms. The goal is to assist medical professionals in identifying the presence of tumors in brain images, enabling early detection and timely intervention.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Brain tumors can have severe consequences, and early detection is crucial for successful treatment. This project focuses on leveraging machine learning techniques to analyze brain images and predict whether a tumor is present or not.

## Features

- Utilizes Convolutional Neural Networks (CNNs) for image classification.
- Integration with popular machine learning libraries such as TensorFlow and Keras.
- In-depth data preprocessing to enhance model accuracy.
- Evaluation metrics for assessing the model's performance.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/brain-tumor-detection.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```


## Dataset

The project utilizes a curated dataset of brain images containing both tumor and non-tumor samples. The dataset is obtained from [source link](https://www.kaggle.com/datasets/jakeshbohaju/brain-tumor) and should be placed in the Brain Tumor directory.

## Preprocessing

The preprocessing script standardizes image sizes, normalizes pixel values, and applies data augmentation to enhance the model's robustness.

## Model Training

The CNN model is trained on the preprocessed dataset using the TensorFlow and Keras libraries. Hyperparameters can be adjusted in the `Analysis.ipynb` script.

## Evaluation

The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1 score. These metrics provide insights into the model's ability to correctly classify tumor and non-tumor images.

## Results

Upon training and evaluation, the project provides insights into the model's performance. Results, including confusion matrices and classification reports, are presented in the `Analysis.ipynb` script.

## Contributing

Contributions to the project are welcome. Feel free to open issues, propose new features, or submit pull requests.
