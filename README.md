# Pill Adherence Tracker
A real-time pill detection system that uses a custom-trained YOLOv8 model to identify and count pills on a tray. This project demonstrates an end-to-end machine learning workflow, from dataset preparation and model training to deployment.

# Purpose
The primary goal of this project is to provide an accurate and efficient solution for pill detection. The YOLOv8 model is highly effective at detecting and identifying pills under various conditions, which is crucial for practical applications such as medicine management and automated pill dispensing machines.

# Technologies Used
Python: The core programming language for the project.

Ultralytics YOLOv8: The state-of-the-art model for object detection.

OpenCV: Used for image and video processing tasks.

ONNX Runtime: An inference engine used to run the model efficiently.

NumPy: A fundamental library for numerical operations.

Google Colab: The development environment for training and running the model.

# Project Files
The repository contains the following key files and folders:

best.pt: The trained YOLOv8 model in its native PyTorch format. This file is ready for inference and can be used for further training.

best.onnx: The model exported to the ONNX format, optimized for deployment on various platforms.

training.ipynb: A Jupyter notebook documenting the training process, including dataset preparation, hyperparameter settings, and performance evaluation.

prediction.ipynb: A Jupyter notebook demonstrating how to use the trained model to perform object detection on new images.

initial dataset/: The raw dataset used for training the model, including the images and their corresponding annotations.

License
This project is licensed under the AGPL-3.0 License. The GNU General Public License v3.0 (GPLv3) is a strong "copyleft" license that allows others to use, copy, modify, distribute, and sell your source code as long as they also make their derivative work available under the same license. This is a good choice if you want to ensure that any improvements to your work are also open-sourced.
