# Application of Machine Learning to Fingerprint Similarity Pattern Detection to Support Forensic Investigation 
This repository contains the code and resources for the research paper "Application of Machine Learning to Fingerprint Similarity Pattern Detection to Support Forensic Investigation". The study explores how machine learning, specifically a VGG16-based CNN model, can improve fingerprint recognition accuracy for damaged or imperfect fingerprints commonly encountered in forensic investigations.

## 📌 Overview

This project implements a VGG16-based CNN model to enhance fingerprint recognition accuracy, particularly for damaged or imperfect fingerprints commonly found in forensic cases. The research demonstrates that training with a mix of clean and artificially degraded fingerprints significantly improves performance on real-world forensic samples.

## 🚀 Key Features

- **CNN Model**: VGG16-based architecture optimized for fingerprint recognition
- **Forensic Case Simulation**: Artificially degraded training data mimicking forensic conditions
- **Advanced Preprocessing**:
  - CLAHE contrast enhancement
  - Bilateral filtering
  - Morphological operations
- **Data Augmentation**: Rotation, scaling, noise addition, and more
- **Performance Analysis**: Comparative results of different training approaches

## 📌 Dataset

The research uses publicly available fingerprint datasets from:

- Neurotechnology (CrossMatch and UareU)

- Fingerprint Verification Competition (FVC)

## 🚀 Contributor

- Vincent Oliver Limarus
- Marcello Arvel Sudarta
- Andrew Aldrich Lee
- Anderies Notanto

School of Computer Science, Bina Nusantara University, Jakarta, Indonesia

**Pull the Code**
---
Clone this repository into ur Local
```
git clone https://github.com/VincentLimarus/fingerprint-recognition.git
```
Go to the Directory
```
cd fingerprint-recognition
```
-----

**Visualization**
---
https://github.com/VincentLimarus/thesis-graphic-helper

The study evaluates four experimental approaches:

1. EfficientNetB0 trained on a combined dataset (80:20 ratio of clean to damaged fingerprints).
2. EfficientNetB0 trained exclusively on clean fingerprint images.
3. VGG16 trained on a combined dataset (80:20 ratio of clean to damaged fingerprints).
4. VGG16 trained exclusively on clean fingerprint images.

