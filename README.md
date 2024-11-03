# DCGAN Based Brain Metastases Detection Using Limited Labeled Dataset

This project utilizes Deep Convolutional Generative Adversarial Networks (DCGANs) to tackle the issue of limited labeled datasets in the early diagnosis of brain tumors through Computer-Assisted Diagnosis (CAD).

## Overview
The project addresses the challenge of inaccessible medical data due to confidentiality. By leveraging Data Augmentation (DA) techniques, synthetic data is generated to augment small medical image datasets collected from various scanners. Generative Adversarial Networks (GANs) are employed as the primary DA technique, generating new images that contain realistic characteristics.

## Key Features
- **Data Augmentation**: Generates synthetic data to supplement limited training datasets.
- **Deep Convolutional GANs (DCGANs)**: Utilizes DCGANs to create realistic images for training.
- **Accuracy Improvement**: Achieved a 13.16-fold increase in accuracy by augmenting synthetic images with training data.
- **Visualization Tool**: Used ImageJ to analyze the similarity between original and synthetic images.
- **Model Validation**: Conducted a visual Turing test with expert physicians to validate the CAD model.

## Methodology
1. **Data Collection**: Gathered a small dataset of medical images from various scanners.
2. **Data Augmentation**: Generated synthetic data using DCGANs to augment the training dataset.
3. **Training**: Trained the CAD model on the augmented dataset to enhance detection accuracy.
4. **Visualization and Validation**: Analyzed the similarity of original and synthetic images using ImageJ and validated the model with expert physicians through a visual Turing test.

## Technology Stack
- **Deep Learning**: Implemented DCGANs for data augmentation.
- **Visualization**: Utilized ImageJ for image analysis.
- **Validation**: Conducted validation with expert physicians.

## Conclusion
By using DCGANs for data augmentation, this project significantly improved the accuracy of brain metastases detection in CAD systems. The approach demonstrates the potential of GANs in overcoming data scarcity and enhancing the effectiveness of medical diagnosis.
