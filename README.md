# Emotion Recognition by Speech

This project focuses on recognizing human emotions from speech using machine learning techniques. The implemented model utilizes a Support Vector Machine (SVM) algorithm with a linear kernel for classification.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Model](#model)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Emotion recognition by speech aims to identify and classify emotions expressed in audio data. This can be used in applications like sentiment analysis, virtual assistants, and user behavior analysis.

## Features

- Preprocessing of audio data for feature extraction.
- Implementation of SVM with a linear kernel for emotion classification.
- Supports multiple emotion classes.

## Dataset

The project uses a dataset of labeled audio files. Each audio file corresponds to a specific emotion.

## Model

The model employs the **Support Vector Machine (SVM)** algorithm:
- **Kernel**: Linear
- **C (Regularization)**: 1

## Usage

1. Prepare the dataset in the appropriate format.
2. Run the Jupyter Notebook file `Emotion_Recognition_by_Speech.ipynb` to train and evaluate the model.
3. Load the pre-trained model using `emotion_recognition_project.pkl` for predictions.

## Results

The SVM model achieved an accuracy of **0.6666** for classifying emotions in speech. Detailed metrics are provided in the notebook.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request for any improvements or bug fixes.
