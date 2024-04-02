# Handwritten Digit Recognition System

This Python project implements a handwritten digit recognition system using machine learning techniques. The system processes input images containing handwritten digits, identifies and segments the digits, and then classifies them into one of the ten digits (0-9). It utilizes various image processing techniques, feature extraction, and classification algorithms to achieve accurate digit recognition.

## Key Features

- **Digit Segmentation**: The system can identify and isolate individual digits from input images using contour detection and bounding box extraction techniques.
  
- **Feature Extraction**: It extracts features from segmented digits using Histogram of Oriented Gradients (HOG), which captures the local shape and gradient information.
  
- **Classification**: Two classification algorithms are implemented: k-Nearest Neighbors (k-NN) and Support Vector Machine (SVM). These models are trained on labeled digit images to classify digits accurately.
  
- **Custom Training**: The system supports custom training using user-provided images containing handwritten digits. It automatically segments and labels the digits for training the recognition models.

## Components

- **Image Processing**: Utilizes OpenCV and scikit-image libraries for image preprocessing tasks such as thresholding, erosion, dilation, and contour detection.
  
- **Feature Extraction**: HOG features are extracted from segmented digits using scikit-image's HOG function.
  
- **Classification Models**: Two custom classes are defined for k-NN and SVM models using OpenCV's machine learning module.
  
- **User Interface**: Provides a simple command-line interface for processing user-provided images and displaying the recognized digits.
  
- **Evaluation**: Evaluates the performance of the recognition system using accuracy metrics on a test dataset.

## Usage

1. Prepare training data:
   - Use the provided MNIST dataset or create a custom dataset of handwritten digits.
  
2. Train the recognition models:
   - Choose k-NN or SVM model and train it on the training dataset.
  
3. Process input images:
   - Provide an input image containing handwritten digits.
   - The system will segment, classify, and display the recognized digits.

## Requirements

- Python 3.x
- NumPy
- OpenCV
- scikit-image
- matplotlib

---

Enjoy the Project...
