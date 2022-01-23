# Google-Street-View-Identify
Identify characters from Google Street View images for Kaggle competition

## Data
- Bmp images of characters taken from Google Street View pictures
- Class label for each picture in the training data

## Data augmentaton
Classes in dataset are imbalanced.

We should perform augmentation to increase number of samples in small classes and to mitigate overfitting:
- Horizontal and Vertical Shift
- Horizontal and Vertical Flip
- Random Rotation
- Random Brightness
- Random Zoom
- Kernel filters (Gaussian blur, sharpening)

## Approaches
- CNN + MLP (fully connected dense layer)
- CNN + SVC
- CNN + KNN
- K-fold cross validation
- Ensemble (Voting Classifier: SVC, KNN, LogReg, MLP
- Transfer learning

The predictions were evaluated using **Classification Accuracy**.
