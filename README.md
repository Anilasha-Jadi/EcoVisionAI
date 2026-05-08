**Hybrid Waste Classification and End-of-Life Recommendation System**

**Overview**

This project presents a hybrid deep learning framework for automated waste classification and sustainable waste management.

The proposed system combines multiple pretrained convolutional neural networks — ResNet50, MobileNetV2, and EfficientNetB0 — with Convolutional Block Attention Module (CBAM) for improved feature extraction and classification performance.

The model classifies waste images into nine categories and additionally provides End-of-Life (EOL) disposal recommendations to promote environmentally responsible waste handling.

**Waste Categories**

Cardboard
Food Organics
Glass
Metal
Miscellaneous Trash
Paper
Plastic
Textile Trash
Vegetation

**Key Features**

Hybrid CNN-based architecture
CBAM attention mechanism integration
Transfer learning and fine-tuning
Data augmentation and preprocessing
Multi-class waste image classification
Real-world image prediction
End-of-Life disposal recommendation system
Confusion matrix and classification report analysis

**Methodology**

Data Preprocessing
Image resizing to 224 × 224
EfficientNet preprocessing
Pixel normalization
Rotation augmentation
Zoom augmentation
Horizontal flipping
Brightness adjustment

**Model Architecture**

The proposed architecture includes:

ResNet50 for deep feature extraction
MobileNetV2 for lightweight feature learning
EfficientNetB0 for optimized feature scaling
CBAM attention modules for feature refinement
Feature fusion using concatenation
Dense classification layers with dropout regularization
Training Strategy
Transfer learning using pretrained ImageNet weights
Frozen backbone training during initial phase
Fine-tuning of last layers using low learning rate
Early stopping and learning rate scheduling
Label smoothing for better generalization

**Evaluation Metrics**

The model performance was evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Classification Report

**End-of-Life Recommendation System**

After predicting the waste category, the system suggests appropriate disposal methods for sustainable waste management.
End-of-Life Recommendation System

After predicting the waste category, the system suggests appropriate disposal methods for sustainable waste management.
