# Waste Image Classifier using PyTorch

A Convolutional Neural Network (CNN) built from scratch using **PyTorch** to classify waste images into 6 categories.

## Project Overview
This project demonstrates a complete supervised learning pipeline for image classification.  
A custom neural network was designed, trained, and evaluated on the Garbage Classification dataset.

### Classes
- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash

## Dataset
- Source: Garbage Classification Dataset (Kaggle)
- Total images: ~2500
- Split: 80% Training | 20% Validation
- Image size used: 128×128

## Neural Network Architecture
The model is a custom CNN with the following layers:

- 3 Convolutional layers (feature extraction)
- Max Pooling layers
- ReLU activation
- Fully Connected layers for classification
- Dropout for regularization

The network was trained using:
- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Learning Rate: 0.001

## Results
- Validation Accuracy: **XX%** (replace with your actual accuracy)
- The model performs well on clear images of common waste items.
- Some confusion occurs between similar-looking materials (e.g., certain plastics and glass).

## How to Run
1. Open the notebook in Google Colab
2. Mount Google Drive or upload the dataset
3. Run all cells in order
4. The trained model is saved as `waste_classifier.pth`

## Files Included
- `Waste_Classifier_PyTorch.ipynb` → Complete training and testing notebook
- `waste_classifier.pth` → Trained model weights
- Prediction samples and training graphs

## Limitations
- Performance decreases with poor lighting or blurry images
- Limited number of classes
- Currently works best with single-object images

## Future Improvements
- Add more classes
- Use data augmentation
- Deploy as a simple web application
- Improve accuracy with a deeper network or transfer learning

## Author
[Your Full Name]  
MSc AI Student
