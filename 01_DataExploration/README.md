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

- Random Image Samples: Visualized 3 random images per class

<img width="794" height="270" alt="Image" src="https://github.com/user-attachments/assets/3700879d-6377-4b82-b444-a115edc8b0a3" />

<img width="794" height="270" alt="Image" src="https://github.com/user-attachments/assets/12ab127f-ca53-46a4-8184-12b2ab98eb34" />

<img width="794" height="273" alt="Image" src="https://github.com/user-attachments/assets/04866352-e676-46c6-a008-aa94da6f63ac" />

<img width="794" height="270" alt="Image" src="https://github.com/user-attachments/assets/eabe86ac-8129-4efa-ae89-9fe683b293a7" />

- Image Details:
  
![alt text](image.png)

  1. Image size: (512, 512)
  2. Image mode: L
  3. Image format: JPEG  
   
- Image Size Distribution: Histogram shows variation in width and height
  
<img width="699" height="374" alt="Image" src="https://github.com/user-attachments/assets/0e60286a-f7de-4319-aab5-6de4c64de2a2" />

- Class Balance: Training and Testing set are slightly imbalanced

<img width="859" height="316" alt="Image" src="https://github.com/user-attachments/assets/268ececf-8bbb-4d89-9f05-7d383168718f" />

<img width="850" height="316" alt="Image" src="https://github.com/user-attachments/assets/9e974547-cb4c-445c-b2f1-6a3a6689adb3" />

---

## 4. Insights / Notes

- Images will need resizing to a consistent size for model training  
- Data augmentation may be applied to address class imbalance  
- All images are RGB, no grayscale images found  
- No corrupted files detected

---
