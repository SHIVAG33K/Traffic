# Traffic
# Overview
This project aims to develop a deep learning model using TensorFlow to classify traffic signs from digital images. The goal is to enable self-driving cars to recognize and distinguish various road signs, such as stop signs, speed limit signs, and yield signs, from images captured by onboard cameras.
# Dataset
The German Traffic Sign Recognition Benchmark (GTSRB) dataset is used, which contains over 50,000 images of 43 different types of road signs. The dataset is split into 39,209 training images and 12,630 test images, with varying light conditions and rich backgrounds.
download dataset - https://cdn.cs50.net/ai/2023/x/projects/5/gtsrb.zip
# Model Architecture
The model is designed to learn visual patterns of each sign class using convolutional neural networks (CNNs). The architecture includes convolutional and pooling layers to extract features, followed by fully connected layers for classification.
# Training and Evaluation
The model is trained on the GTSRB training data and evaluated on the test data. Techniques like data augmentation are used to improve the model's ability to generalize.
# Results
The project achieves a high accuracy in classifying traffic signs, demonstrating the effectiveness of TensorFlow in building a neural network for this task.
# Code
The code is written in Python and uses TensorFlow as the deep learning framework. The project includes a README file with detailed instructions on how to run the code and reproduce the results.
# Dependencies
The project requires the following dependencies:
TensorFlow
Python
OpenCV
NumPy
# Conclusion
This project demonstrates the potential of deep learning in traffic sign recognition and contributes to the development of safer and more efficient autonomous vehicles.
