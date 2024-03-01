# Skin Disease Classification Project

## Motivation:

This project is motivated by the pressing need for efficient diagnosis and treatment of skin diseases, particularly in determining the presence of malignant or benign tumors. Recognizing the challenges and time-consuming nature of traditional diagnostic methods, we aimed to leverage deep learning tools to streamline the process.

## Dataset: ISIC 2017

The ISIC 2017 dataset provides a comprehensive collection of dermoscopic images, facilitating research in dermatology and computer-aided diagnosis.
![melanoma_example](https://github.com/saideepakmara/Melanoma_classification/assets/118351987/fd536d2c-5105-4643-b2c8-8b3221289f15)


## Problem Statement:

The project focuses on developing a system capable of accurately identifying specific skin diseases solely through image analysis. In particular, our aim was to distinguish between malignant and benign tumors using deep learning algorithms.

## Methods:


### Transfer Learning:
Leveraging pre-trained models like EfficientNet and ResNet to enhance CNN accuracy.
### Data Augmentation: 
Mitigating data imbalance by applying random horizontal and vertical flips to melanoma images.

## Architectures:


### Simple CNN:
A custom-built CNN architecture inspired by LeNet.
![simple_cnn](https://github.com/saideepakmara/Melanoma_classification/assets/118351987/5fc43b38-94a8-41fb-b8fe-9dd053db1aea)

### Not-So-Simple CNN:
Another custom-designed architecture.
![not_simple_cnn](https://github.com/saideepakmara/Melanoma_classification/assets/118351987/d8ea08dc-585a-41a5-bc06-0981116e941c)

### ResNet:
A well-established pre-trained CNN architecture known for its depth and efficiency.
### TinyVGG:
A compact version of the VGG architecture tailored for smaller datasets.
### EfficientNet:
State-of-the-art CNN renowned for scalability and performance.

## Optimizers:

Stochastic Gradient Descent (SGD)
SGD with Momentum
Adam
RAdam
RMSprop
L2 Regularization and Early Stopping: Used to combat overfitting.

## Main Findings:

Overfitting was observed across most models, despite the implementation of L2 regularization.
Surprisingly, simpler architectures performed comparably to more complex ones.

## Conclusion:

EfficientNet and ResNet with transfer learning yielded the most accurate results in classifying benign and malignant skin cancer.
Models trained without transfer learning were susceptible to overfitting due to data scarcity.
Custom-built CNN models demonstrated competitive performance compared to pre-trained models.
Regularization methods and optimizers did not significantly impact performance given the dataset size.





