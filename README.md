#Skin Disease Classification Project

##Motivation:

This project is motivated by the pressing need for efficient diagnosis and treatment of skin diseases, particularly in determining the presence of malignant or benign tumors. Recognizing the challenges and time-consuming nature of traditional diagnostic methods, we aimed to leverage deep learning tools to streamline the process.

##Problem Statement:

The project focuses on developing a system capable of accurately identifying specific skin diseases solely through image analysis. In particular, our aim was to distinguish between malignant and benign tumors using deep learning algorithms.

##Steps of Classification:

To address the problem statement, we adopted the following major steps:

###Methods, Architecture, and Optimizers:


####Methods:


#####Transfer Learning: Leveraging pre-trained models like EfficientNet and ResNet to enhance CNN accuracy.
#####Data Augmentation: Mitigating data imbalance by applying random horizontal and vertical flips to melanoma images.

####Architectures:


Simple CNN: A custom-built CNN architecture inspired by LeNet.
Not-So-Simple CNN: Another custom-designed architecture.
ResNet: A well-established pre-trained CNN architecture known for its depth and efficiency.
TinyVGG: A compact version of the VGG architecture tailored for smaller datasets.
EfficientNet: State-of-the-art CNN renowned for scalability and performance.

####Optimizers:

Stochastic Gradient Descent (SGD)
SGD with Momentum
Adam
RAdam
RMSprop
L2 Regularization and Early Stopping: Used to combat overfitting.

##Main Findings:

Overfitting was observed across most models, despite the implementation of L2 regularization.
Surprisingly, simpler architectures performed comparably to more complex ones.

##Conclusion:

EfficientNet and ResNet with transfer learning yielded the most accurate results in classifying benign and malignant skin cancer.
Models trained without transfer learning were susceptible to overfitting due to data scarcity.
Custom-built CNN models demonstrated competitive performance compared to pre-trained models.
Regularization methods and optimizers did not significantly impact performance given the dataset size.



