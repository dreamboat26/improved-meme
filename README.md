# 🧪 AI for Predicting Superhydrophobicity of Copper-Coated Aluminum Surfaces 

Official implementation of the paper:  
**"AI Approach for Predicting Superhydrophobicity of Thermal Sprayed Copper Coated Aluminum Surfaces"**  
by **Mahule Roy**
Published in *Journal of Diagnosis & Case Reports*, May 2025  
**ISSN:** 2754-4923 | **Open Access**

---

## 📌 Overview

This repository contains the official implementation of a Convolutional Neural Network (CNN)-based model to predict the hydrophobicity (or superhydrophobicity) of thermally sprayed, copper-coated aluminum surfaces treated with various chemical etchants.

By analyzing high-resolution 3D profilometer images, the model learns to correlate surface morphological features — such as roughness, vein patterns, and textural structures — with experimentally measured contact angle values.

---

## 🧠 Research Context

Wettability, determined by a surface's contact angle, is a key property for a variety of applications including:

- Biomedical implants
- Self-cleaning surfaces
- Anti-fog coatings
- Water-repellent materials

Surfaces with a contact angle >150° are classified as **superhydrophobic**. Traditional contact angle measurements are often time-consuming and equipment-intensive. This study proposes a deep learning alternative using surface image data.

---

## 🧬 Abstract

This project presents a CNN-based approach to classify whether copper-coated aluminum surfaces are **hydrophobic** or **superhydrophobic** based on profilometer images. These surfaces were treated with different chemical reagents, and corresponding contact angle measurements were recorded. The CNN model aims to learn surface-feature representations predictive of wettability.

> Note: Initial training accuracy may be limited due to dataset size. Future work includes dataset expansion and hybrid modeling techniques.

---

## 🖼️ Dataset

- **Source**: 3D non-contact profilometer images of copper-coated aluminum surfaces
- **Labels**: Hydrophobic / Superhydrophobic (based on measured contact angles)
- **Format**: `.png` or `.jpg` images with associated contact angle values
- **Size**: Small (initial prototype); augmentation recommended

---

## 🧰 Requirements

- Python 3.8+
- TensorFlow or PyTorch
- NumPy
- OpenCV or PIL
- Matplotlib
- Scikit-learn

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/dreamboat26/improved-meme.git
cd improved-meme
```

---

## 🏗️ Project Structure

```
.
├── dataset/
│   ├── images/
├── code implementation
└── README.md
```

---

## 📊 Results

- **Initial Accuracy**: ~70% (baseline)
- **Observations**:
  - Improved accuracy expected with dataset augmentation
  - Surface roughness and textural patterns are strong predictors
  - Hybrid models (CNN + statistical features) could further improve performance

---

## 🧪 Applications

- **Biomedical implants**: Superhydrophobic coatings reduce bacterial adhesion
- **Surface engineering**: Aid in rapid surface characterization
- **Material science**: Predictive modeling of wettability for new treatments

---

## 📚 Citation

If you use this code or dataset in your work, please cite the paper:

```
Mahule Roy. (2025). AI Approach for Predicting Superhydrophobicity of Thermal Sprayed Copper Coated Aluminum Surfaces. 
Journal of Diagnosis & Case Reports. ISSN: 2754-4923.
```

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
