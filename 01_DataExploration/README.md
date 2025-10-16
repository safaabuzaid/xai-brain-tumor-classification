# Brain Tumor MRI Dataset - Data Exploration Summary

## 1. Dataset Overview

- Source: Local dataset (originally from [Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) / [HuggingFace](https://huggingface.co/datasets/Simezu/brain-tumour-MRI-scan?utm_source=chatgpt.com))
- Total images: 7,023
- Number of classes: 4

---

## 2. Training and Testing Data

- Training set: 5,712 images
- Testing set: 1,311 images

### Images per class (Training)

- glioma: 1321
- meningioma: 1339
- notumor: 1595
- pituitary: 1457

### Images per class (Testing)

- glioma: 300
- meningioma: 306
- notumor: 405
- pituitary: 300

---

## 3. Data Exploration

- Random Image Samples: Visualized 3–5 random images per class

<img width="794" height="270" alt="Image" src="https://github.com/user-attachments/assets/3700879d-6377-4b82-b444-a115edc8b0a3" />

- Image Details:
- Size: variable (width and height differ between images)
- Format: JPEG / PNG (depending on dataset)
- Color channels: RGB  
- Image Size Distribution: Histogram shows variation in width and height
[image](path)
- Class Balance: Training set is slightly imbalanced
[image](path)

---

## 4. Insights / Notes

- Images will need resizing to a consistent size for model training  
- Data augmentation may be applied to address class imbalance  
- All images are RGB, no grayscale images found  
- No corrupted files detected

---
