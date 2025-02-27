# **Deep Neural Networks - CIFAR-10 Classification**

This project focuses on **image classification** using **Deep Neural Networks (DNNs)**, specifically a **Convolutional Neural Network (CNN)**, to classify images from the **CIFAR-10 dataset**. The model is designed with key deep learning techniques, including **convolutional layers, max pooling, flattening, and data augmentation**.

## **Model Architecture**

- **Convolutional Layers (`Conv2D`)**: Extract spatial features using filters.  
- **Max Pooling (`MaxPooling2D`)**: Reduces dimensionality while retaining important features.  
- **Flatten Layer (`Flatten`)**: Converts feature maps into a 1D vector for the fully connected layers.  
- **Fully Connected (`Dense`) Layers**: Perform classification using learned features.  

## **Data Augmentation**

To improve model generalization and prevent overfitting, **ImageDataGenerator** is used to apply real-time augmentations, including:  

✅ Rotation  
✅ Vertical Flip  
✅ Height Shift Range  
✅ Brightness Range 

## **Dataset**

- **CIFAR-10**: A collection of **60,000** 32×32 color images across **10 classes** (e.g., airplanes, cars, birds, cats, etc.).  
- **Split:** 50,000 images for training and 10,000 for testing.  

## **Results**

By leveraging CNNs and data augmentation, the model achieves **significant accuracy** in classifying CIFAR-10 images.
