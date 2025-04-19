# CIFAR-CNN
Object detection is a fundamental problem in computer vision that involves
identifying objects within an image. Convolutional Neural Networks (CNNs) have proven to
be highly effective in extracting spatial features and classifying objects. In this task, we
implement a CNN for object detection using the CIFAR-10 dataset, focusing on
preprocessing, model architecture design, training, evaluation, and performance
improvement.

Dataset: CIFAR-10 dataset, loaded via Keras
Number of images: The output of X_train.shape, X_val.shape, and X_test.shape
would show this (typically 40,000 training, 10,000 validation, and 10,000 test images)
Number of classes: 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship,
truck)
Image dimensions: 32x32x3 (from the shape outputs)
Source: The CIFAR-10 dataset is a widely used benchmark dataset collected by the
Canadian Institute For Advanced Research
Examples of images: The code generates and saves a visualization of sample images in
'sample_images.png'
Class distribution: The code creates bar charts showing the distribution across classes in
'class_distribution.png'. The visualization shows that CIFAR-10 is a balanced dataset with
equal representation of each class.
