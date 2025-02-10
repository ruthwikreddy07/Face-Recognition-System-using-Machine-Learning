# Face- Recognition System using Machine Learning

This project implements a face recognition system using machine learning techniques. The pipeline involves data loading, preprocessing, dimensionality reduction, model training, and evaluation. The primary libraries used are Scikit-learn, OpenCV, NumPy, and Matplotlib.

## Table of Contents

- [Introduction](#introduction)
- [Setup and Installation](#setup-and-installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The face recognition pipeline includes the following steps:
1. Data Loading and Preprocessing
2. Dataset Splitting
3. Dimensionality Reduction using PCA and LDA
4. Model Training with an MLP Classifier
5. Model Evaluation and Visualization

## Setup and Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.7 or higher
- Pip (Python package installer)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ruthwikreddy07/face-recognition-pipeline.git
    cd face-recognition-ppipeline
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Requirements

List of main libraries used:
- matplotlib
- scikit-learn
- numpy
- opencv-python

## Project Structure

```plaintext
face-recognition-pipeline/
│
├── images/
│   └── train/
│       └── person1/
│           └── image1.jpg
│           └── image2.jpg
│       └── person2/
│           └── image1.jpg
│           └── image2.jpg
│       └── ...
├── face_recognition_pipeline.py
├── requirements.txt
└── README.md
