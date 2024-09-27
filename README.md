# Image-Classification-using-Sklearn
# Introduction
- This repository provides a basic implementation of image classification using scikit-learn, a popular Python machine learning library, without relying on OpenCV. The code demonstrates how to load, preprocess, and classify images using a simple support vector machine (SVM) model.

# Prerequisites
- Python 3.x
- scikit-learn
- NumPy
- Pillow (PIL) (for image loading and basic manipulation)
- Matplotlib (for visualization)

# Code Explanation


- Load images: Images are loaded from the specified directory structure using Pillow.
- Preprocess images: Images are resized and converted to grayscale using Pillow functions.
- Extract features: HOG features are extracted from each image using scikit-learn's HOG descriptor.
- Train Models: An SVM model is trained using the extracted features and corresponding labels.
- Evaluate models: The model's performance is evaluated on a test set using accuracy.
