# Convolutional Neural Networks (CNN) for Solid Waste Detection
This project utilizes the TrashNet dataset prepared by students from Stanford University. The dataset consists of six different classes: glass, paper/cardboard, plastic, metal, and trash, totaling 2527 images.

# Business Problem
To develop an artificial intelligence solution for waste classification and optimization of recycling processes, aiming to reduce environmental pollution.

# Understanding the Data
The dataset comprises 501 glass, 594 paper/cardboard, 403 plastic, 482 metal, and 137 trash images, summing up to 2527 images in total.

# Data Preparation
During data preparation, images are resized to the specified target size and data augmentation techniques are applied for the training and test datasets.

# Modeling
The model is built using Convolutional Neural Networks (CNN), including convolutional layers, pooling layers, dense layers, and dropout layers to prevent overfitting.

# Evaluation
At the end of the training process, the model's performance metrics including accuracy, loss, precision, and recall are evaluated. Additionally, a classification report and confusion matrix are used to assess the model's performance in detail.

# Usage
You can test the model with a new image by using the model_testing function. Simply upload a new image and see the classification result.

# Requirements
The following libraries are required to run the project:

TensorFlow
Keras
OpenCV
NumPy
Pandas
Seaborn
Matplotlib
Imutils

# Installation
To install the necessary dependencies for running the project in a local or virtual environment, follow these steps:
```
pip install tensorflow keras opencv-python numpy pandas seaborn matplotlib imutils
```

# License
This project is licensed under the MIT License. For more information, see the LICENSE file.

