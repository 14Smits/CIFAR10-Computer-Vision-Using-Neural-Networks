# CIFAR-10 Image Classification using ResNet18

This repository contains code for training, evaluating, and analyzing a ResNet18 model for the CIFAR-10 image classification task. CIFAR-10 is a popular dataset in the field of computer vision, consisting of 60,000 32x32 color images across 10 classes.

## Files Included
- `Cifar10 with ResNet Computer Vision_Image Classification.ipynb`: Jupyter notebook containing the complete code for the project.
  
## Model Used
- **ResNet18**: We utilized the ResNet18 architecture pretrained on ImageNet and fine-tuned it for CIFAR-10 classification by replacing the final fully connected layer.

## Training and Evaluation
- **Training**: The model was trained using the CIFAR-10 training dataset and evaluated on the validation set to monitor accuracy and logarithmic loss.
  
- **Evaluation**: We evaluated the trained model's performance on the CIFAR-10 test set to determine its final accuracy and log loss metrics.

## Performance Analysis
- The performance of the model was analyzed in terms of accuracy and log loss across multiple epochs of training.
