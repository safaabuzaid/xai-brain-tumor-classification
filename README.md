# Evaluating the Clinical Reliability of Deep Learning Models for Brain Tumor Classification Using MRI: An Explainable AI Approach

This repository contains the implementation of an **explainable deep learning model** for brain tumor MRI classification.  
The goal is not only to achieve accurate predictions but also to provide **interpretable visual explanations** that highlight the MRI regions most responsible for each decision.

---

## Abstract
The increasing use of deep learning in medical imaging raises concerns about the interpretability of AI-driven diagnoses.  
This project explores an approach to brain tumor classification that integrates explainability tools such as **Grad-CAM** and **LIME**, enabling visual insight into the model’s reasoning.  
By visualizing attention regions, the project aims to bridge the gap between model accuracy and clinical interpretability.

### Research Question:
Does high classification accuracy in CNN models for brain tumor MRI truly reflect clinically meaningful decision-making, or do models rely on spurious or irrelevant image features?

---
## Goals of the Project:
1. **Build a robust CNN model** for brain tumor classification that achieves high predictive accuracy.
2. **Evaluate model reliability** using explainable AI techniques (e.g., Grad-CAM) to visualize attention on MRI images.
3. **Analyze discrepancies** between high accuracy and clinical relevance, identifying cases where the model focuses on non-tumor regions.
4. **Understand limitations** of deep learning models in medical imaging and provide insights into improving model trustworthiness for clinical applications.

---
## Methodology
1. **Dataset**: Public Brain Tumor MRI dataset (7,000+ labeled 2D scans).  
2. **Preprocessing**: Image normalization, resizing, and augmentation.  
3. **Model**: Convolutional Neural Network (CNN) architecture for multi-class classification.  
4. **Explainability**: Grad-CAM and LIME to visualize the model’s decision-making regions.  
5. **Evaluation**: Performance metrics (accuracy, precision, recall) and interpretability analysis.

---

## Repository Structure
*(to be updated)* 

---

## Example Output
Example explanation of model prediction using Grad-CAM:

*(to be updated with visual sample)*  
> The generated heatmap highlights regions within the MRI scan that contributed most to the model’s classification decision.

---

## Future Work
*(to be updated)*  

---

## Author
**Safaa Osman**  
MSc in Biomedical Engineering— Medical Image Processing  
Interested in AI for medical imaging and interpretable deep learning.

---

## License
You are welcome to use and adapt the code with proper attribution.
