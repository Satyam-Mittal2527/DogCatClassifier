# Dog Image Classifier using Transfer Learning

This project is a beginner-friendly exploration into **Transfer Learning** using the **MobileNet** model to classify whether an image contains a **dog** or not. It marks the first step in learning how pre-trained models can be adapted for real-world applications with limited data.

## Project Overview

* **Goal**: Classify user-uploaded images as either "dog" or "not dog"
* **Approach**: Used a MobileNet model pretrained on ImageNet and added custom layers for binary classification
* **Learning Focus**: Understanding the mechanics of transfer learning and applying it to a simple classification problem

## Files

* `dog_classifier_model.h5`: Saved trained model
* `README.md`: Project documentation

## Techniques Used

* Transfer Learning with MobileNet
* Flatten and Dense layers for custom head
* EarlyStopping to avoid overfitting
* Binary crossentropy loss for classification

## Training Summary

* Input Shape: 224x224 RGB images
* Optimizer: Adam
* Loss: Binary Crossentropy
* Evaluation Metric: Training accuracy and loss and Validation accuracy and Loss
* Used 20% validation split and EarlyStopping callback

## Real-World Applications

* Pet detection in photo apps
* Smart camera integrations for pet monitoring
* Pet adoption and rescue automation
* E-commerce pet product filtering

## What I Learned

This project helped me understand how transfer learning works and how to apply it to a real-world task. It's a small but meaningful first step into the world of deep learning.

## Next Steps

* Add model evaluation and visualization
* Try fine-tuning last layers of MobileNet
* Deploy as a web or mobile app

## Tags

`#TransferLearning` `#DeepLearning` `#TensorFlow` `#ComputerVision` `#DogCatClassifier`
