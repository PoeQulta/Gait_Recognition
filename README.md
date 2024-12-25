# Gait Based Person Recognition using GEI and Skeleton Data

## Abstract
This project explores gait recognition for classifying individuals using both Gait Energy Images (GEI) and skeleton data. Deep learning is employed for human silhouette extraction from videos using a segmentation model, and OpenPose is utilized to obtain skeleton keypoints. Machine learning techniques, including Random Forest and Convolutional Neural Networks (CNNs), are implemented for classification.

- For GEI-based classification, a Random Forest model achieved an accuracy of 0.92 , while a CNN achieved a test accuracy of 0.9231.
- Skeleton-based classification was performed with and without data augmentation; the model without augmentation achieved an accuracy of 0.91, whereas the augmented model achieved 0.98 accuracy.
- Ensemble models combining GEI and skeleton data achieved an accuracy of 0.98 without data augmentation and 0.97 with data augmentation.

The results demonstrate the effectiveness of combining multiple modalities and data augmentation for gait recognition.