# Spam Email Detection and Emotion Recognition from Speech

## Overview

This repository contains two distinct projects:
1. **Spam Email Detection**: A classification model to detect spam and non-spam emails.
2. **Emotion Recognition from Sound**: A classification model to identify emotions from audio files.

## Spam Email Detection

### Dataset

The dataset consists of email texts with two columns:
1. **Label**: Indicates if the email is spam or non-spam.
2. **Text**: The body of the email.

### Objectives

1. **Preprocessing**:
   - Analyze word frequency to identify common words in spam and non-spam emails.
   - Apply tokenization to prepare the text data for modeling.

2. **Model Implementation**:
   - Implement LSTM, RNN, and GRU models to classify emails.
   - Compare model performance using accuracy and error graphs for training and testing data.
   - Report precision, recall, and F1-score to evaluate model performance.
   - Experiment with different optimizers and learning rates to determine the best model configuration.

## Emotion Recognition from Sound

### Dataset

The dataset is extracted from the ShEMO dataset and consists of audio files in WAV format. File names follow this structure:
- **Voice ID** (number)
- **Gender** (F or M)
- **Emotion** (H for happiness, A for anger, S for sadness, N for neutral, W for surprise)

### Objectives

1. **Feature Extraction**:
   - Extract features using the Mel-Frequency Cepstral Coefficients (MFCC) method.

2. **Model Implementation**:
   - Implement LSTM networks for emotion classification.
   - Plot accuracy and error graphs for training data.
