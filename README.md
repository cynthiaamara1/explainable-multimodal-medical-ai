# MSc Dissertation

# Explainable Multimodal Model for Chest X-ray Disease Classification Using Images and Radiology Reports

This repository contains my MSc dissertation project, which investigates explainable multimodal deep learning for chest X-ray disease classification using chest X-ray images and radiology reports.

Unlike conventional image-only systems, this framework integrates visual and textual information using multimodal learning to improve diagnostic performance while generating clinically meaningful explanations.

The project compares two multimodal fusion strategies:

- Late Fusion
- Joint Fusion

and investigates how each influences predictive performance and explainability.

---

## Objectives

- Develop an explainable multimodal AI framework
- Combine chest X-ray images with radiology reports
- Compare unimodal and multimodal learning
- Evaluate Late Fusion vs Joint Fusion
- Generate visual and textual explanations for predictions

---

## Dataset

**MIMIC-CXR-JPG**

The project uses paired:

- Chest X-ray images
- Radiology reports
- CheXpert labels

for multi-label thoracic disease classification.

---

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- LLaMA 3.1
- DenseNet121
- PEFT
- LoRA
- QLoRA
- Captum
- Grad-CAM
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Models

### Image Model

DenseNet121

### Text Model

LLaMA 3.1 8B

### Fusion Models

- Late Fusion
- Joint Fusion

---

## Explainability

The framework provides interpretable predictions using:

- Grad-CAM
- Integrated Gradients

---

## Repository Contents

- Jupyter Notebook
- Dissertation Report
- Dataset
- Explainability Visualisations
- Requirements File
