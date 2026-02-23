# Modified PPM-SSNet for Post-Disaster Building Damage Classification  
## xBD Dataset | Satellite Image-Based Damage Assessment

<p align="center">
  <img src="images/Model Architecture.jpg" width="40%" />
  <img src="images/Classification Result.png" width="40%" />
</p>

---

## Overview

This project implements and evaluates a modified PPM-SSNet architecture for classifying post-disaster building damage using high-resolution satellite imagery from the xBD dataset.

The objective is to assess whether architectural modifications improve model effectiveness in multi-class building damage classification.

Damage categories include:

- No damage  
- Minor damage  
- Major damage  
- Destroyed  

---

## Model Architecture

PPM-SSNet integrates:

- Pyramid Pooling Module (PPM) for multi-scale contextual feature extraction  
- Semantic segmentation backbone for spatial feature learning  
- Classification head for building-level damage prediction  

This project modifies the original architecture to improve:

- Feature representation robustness  
- Multi-scale contextual sensitivity  
- Classification consistency  

---

## Methodology

### Dataset
- xBD (xView2) satellite imagery dataset  
- Pre- and post-disaster building image pairs  

### Pipeline
- Image preprocessing and augmentation  
- CNN-based feature extraction  
- Modified PPM-SSNet architecture implementation  
- Multi-class classification  

### Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion matrix analysis  

---

## Results

- Achieved competitive classification performance across all four damage categories.
- Confusion matrix analysis highlights class imbalance effects between minor and major damage.
- Multi-scale pooling improved contextual sensitivity in dense urban regions.

(See visual results above.)

---

## Why This Matters

Rapid and reliable post-disaster damage assessment supports:

- Emergency response planning  
- Infrastructure prioritisation  
- Insurance loss estimation  
- Humanitarian resource allocation  

Deep learning models applied to satellite imagery enable scalable disaster impact monitoring.

---

## Tools & Frameworks

Python · PyTorch · CNN architectures · Satellite image processing · Computer vision · Multi-class classification

---

## Repository Structure

- `images/` – Model architecture & classification outputs  
- `Main_code_CNN.ipynb` – Core model implementation  
- `Analysis_doc_CNN.pdf` – Full research document  
- `README.md`  

---

## Author

Mohamad Rendy Irawan Ifran  
MSc Social & Geographic Data Science  
University College London
