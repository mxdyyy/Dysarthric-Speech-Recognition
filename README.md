# Spectrogram-Driven Classification of Dysarthric Speech for Enhanced Recognition

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
![custom-badge](https://raw.githubusercontent.com/mxdyyy/badge/7bbc06cca83b680ed421674221d629ebd9eab43f/built-on-jupyter-notebook.svg)
![custom-badge](https://raw.githubusercontent.com/mxdyyy/badge/e283407160e7c08b17db40211c9418f2a41807a7/built-by-team-dorkyduos%20(1).svg)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

### Welcome to the DorkyDuos team's GitHub repository for our project on Spectrogram-Driven Classification of Dysarthric Speech

This project aims to improve the recognition of dysarthric speech using a spectrogram-driven approach. Dysarthria is a motor speech disorder often resulting from neurological conditions. Traditional Automatic Speech Recognition (ASR) systems struggle with recognizing dysarthric speech due to the altered phonemes and the scarcity of dysarthric speech data. Our approach leverages visual representations of speech (spectrograms) to enhance the accuracy of speech recognition for individuals with dysarthria.

## Team Members

- **Mathangi N (Team Leader)**
  - Branch: B.Tech Computer Science Engineering (AI & DS)
- **Madhav N**
  - Branch: B.Tech Information Technology

## Table of Contents
- [Introduction](#introduction)
- [Abstract](#abstract)
- [Problem Statement](#problem-statement)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Approach](#approach)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Contributors](#contributors)

## Introduction
Dysarthria affects the articulation of speech due to muscular impairments, making it challenging for traditional ASR systems to accurately transcribe. This project focuses on using spectrogram analysis to improve dysarthric speech recognition, thereby enhancing communication for individuals with speech disorders.

## Abstract
This project explores a spectrogram-driven approach to enhance dysarthric speech recognition. By converting audio signals into spectrograms, the system captures detailed frequency and time-domain information crucial for accurate speech classification and transcription.

## Problem Statement
Develop a robust system for dysarthric speech recognition that overcomes challenges such as altered phonemes, limited training data, and varying severity of speech impairments.

## Features
- **Spectrogram Visualization**: Converts audio speech into spectrograms to capture frequency and time dynamics.
- **Machine Learning Classifiers**: Utilizes advanced ML models for speech classification.
- **Dimensionality Reduction**: Applies Principal Component Analysis (PCA) to enhance feature representation.
- **Improved ASR**: Achieves higher accuracy in dysarthric speech recognition compared to traditional ASR systems.

## Technologies Used
- Python
- TensorFlow / PyTorch
- Scikit-learn
- NumPy
- Pandas

## Dataset
- Utilised UA Speech dataset, a curated dysarthric speech popular dataset

## Approach
1. **Data Collection**: Gathered dysarthric speech recordings and annotated them with corresponding labels.
2. **Spectrogram Generation**: Converted audio recordings into spectrograms to visualize speech features.
3. **Model Training**: Developed and trained machine learning models/classifiers on the spectrogram data.
4. **Evaluation**: Assessed model performance using evaluation.

## Evaluation Metrics
- **Accuracy**: Percentage of correctly classified dysarthric speech samples.
- **Precision and Recall**: Measures of model performance in detecting specific speech classes.
- **Confusion Matrix**: Visualization of classification errors and strengths.

## Results
The developed system demonstrates significant improvements in dysarthric speech recognition accuracy compared to traditional ASR systems. Detailed performance metrics and visualizations are available in the results directory.

## Contributors
- **Madhav N**: [madhavnarayanan2004@gmail.com](mailto:madhavnarayanan2004@gmail.com)
- **Mathangi N**: [mathanginarayanan2004@gmail.com](mailto:mathanginarayanan2004@gmail.com)
