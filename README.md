# Xray-Classification

X-ray Image Classification for Pneumonia Detection

Machine learning has a wide range of applications, and one of its significant contributions is in the field of health and diagnostics. This project focuses on building a machine learning model to classify X-ray images and predict the presence of pneumonia. Given the current times, where COVID-19 can lead to pneumonia, this project becomes especially relevant.

This README file provides an overview of the project, explaining the complete pipeline from data loading to result prediction. It will guide you through the process of building an X-ray image classification model from scratch, highlighting the steps involved in creating an accurate and efficient solution.
Table of Contents

Introduction
Project Overview
Results
Getting Started
Usage
Contributing
License

Introduction

The goal of this project is to develop a machine learning model that can accurately classify X-ray scans and determine if they indicate the presence of pneumonia. By leveraging the power of machine learning, we can aid medical professionals in diagnosing and treating patients more effectively.
Project Overview

This project encompasses the following key steps:

Loading Data: We discuss the process of obtaining and preparing the X-ray image dataset for training and evaluation purposes.

Model Building: We explain how to construct a Convolutional Neural Network (CNN) architecture from scratch. This architecture will serve as the backbone for our pneumonia detection model.

Model Training: We provide insights into training the CNN model on the prepared dataset. Additionally, we address techniques such as finetuning and regularization to improve model performance.

Result Prediction: Once the model is trained, we demonstrate how to use it to predict the presence of pneumonia in new X-ray images.

Please note that this project does not include data augmentation techniques. Since X-ray scans are typically taken in a specific orientation, real X-ray images do not exhibit variations such as flips and rotations.
Results

Based on our experiments, we achieved the following results:

Accuracy on Test Data: 83%
        It is important to note that the accuracy on the test set is slightly lower compared to the validation set accuracy. This could indicate overfitting. To mitigate this issue, we recommend further finetuning of the model to reduce overfitting to the training and validation sets.

Recall: Greater than Precision
        Our model exhibits higher recall than precision, suggesting that it correctly identifies the majority of pneumonia images but may misclassify some normal images as pneumonia. Therefore, efforts should be made to increase precision.

