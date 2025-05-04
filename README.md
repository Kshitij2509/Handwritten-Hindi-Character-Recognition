# Devanagari Handwriting Recognition System

## Overview
This project implements a handwriting recognition system for the Devanagari script, primarily used in languages such as Hindi, Marathi, and Nepali. Utilizing deep learning and computer vision techniques, the application captures handwritten input in real-time and accurately recognizes the drawn characters.

## Features
- **Real-Time Recognition**: Draw Devanagari characters and receive instant feedback on recognition.
- **Convolutional Neural Network**: Trained model with high accuracy based on a comprehensive dataset of handwritten characters.
- **Interactive Interface**: User-friendly drawing area that mimics a blackboard, allowing for easy character input.
- **Color Detection**: Isolates drawn characters using specific color thresholds for effective recognition.

## Technology Stack
- **Deep Learning**: Keras (with TensorFlow backend)
- **Computer Vision**: OpenCV
- **Data Manipulation**: Pandas, NumPy

## Dataset
The dataset used for training the model consists of Devanagari characters. You can download it using the following link: [Devanagari Character Set](https://www.kaggle.com/datasets/rishianand/devanagari-character-set).

## Workflow
1. **Model Training**: Trains a CNN on a dataset of grayscale images of Devanagari characters.
2. **Video Capture**: Uses webcam input to detect and process drawn characters.
3. **Character Prediction**: Processes images and predicts the character using the trained model.

## Results
The system demonstrates effective recognition of handwritten Devanagari characters, showcasing the potential of AI in language processing.

## Usage
To use this system, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Kshitij2509/Handwritten-Hindi-Character-Recognition.git
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Download the dataset from the provided link.
4. Train the model using the provided script:
   ```bash
   python train.py
6. Run the application to start real-time handwriting recognition:
   ```bash
   python app.py
