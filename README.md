# Project Name

Driver Drowsiness Detection System

# Objective

- The Driver Drowsiness Detection System is a deep learning application developed to detect whether a driver is alert or drowsy by analyzing the driver's eye and mouth conditions from images.

- The system uses Convolutional Neural Networks (CNNs) to identify eye closure/opening and mouth conditions such as yawning. These predictions are combined to determine the driver's fatigue level and help identify potential drowsiness while driving.

# Key Features
- Driver drowsiness and fatigue detection.
- Eye state detection (Open or Closed).
- Mouth state detection (Yawning or Not Yawning).
- Multi-level fatigue detection.
- Image-based driver condition analysis.

# Technologies and Tools Used
- OS Module – File system operations, directory management, file paths, and dataset organization.
- Matplotlib – Data visualization and analysis.
- PIL (Pillow) – Image processing and corrupted image verification.
- TensorFlow & Keras – Building, training, validating, and evaluating deep learning models.
- Sklearn - Model Evaluation.

# Deep Learning Model
- Model Used: Convolutional Neural Network (CNN).
- Problem Type: Image Classification.
- Eye Model: Binary Classification.
- Mouth Model: Binary Classification.

# Project Workflow
- Dataset Organization using OS Module.
- Corrupted Image Detection.
- Train, Validation and Test Split.
- Image Resizing.
- Data Augmentation.
- MobileNetv2 Model Building.
- Eye Model Training.
- Mouth Model Training.
- Model Evaluation.
- Multi-Level Fatigue Classification.
