# CaneGuard AI: Sugarcane Disease Detection using EfficientNetB0

CaneGuard AI is a deep learning-based sugarcane leaf disease detection system. It uses transfer learning with EfficientNetB0 to classify sugarcane leaf images into five classes: Healthy, Mosaic, RedRot, Rust, and Yellow Leaf symptoms.

## Features

- Sugarcane leaf disease classification
- EfficientNetB0 transfer learning
- Train, validation, and test split
- Confidence score for each prediction
- Treatment recommendation card
- Grad-CAM visual explanation
- Upload custom image and get disease prediction

## 🦠 Diseases Detected

| Disease | Action Needed |
|---------|--------------|
| ✅ Healthy | Regular monitoring |
| 🟡 Mosaic Virus | Apply Imidacloprid 0.3ml/L |
| 🔴 Red Rot | Destroy infected stalks immediately |
| 🟤 Rust | Spray Propiconazole 25EC |
| 🟡 Yellow Leaf | Apply micronutrient mix |

## 🚀 Run This Project

**Google Colab:**

1. Open `CaneGuard_PestDetection.ipynb`
2. Runtime → T4 GPU
3. Run all cells


## Dataset

The dataset contains sugarcane leaf images organized into five classes:

- Healthy
- Mosaic
- RedRot
- Rust
- Yellow

Dataset path used in Google Colab:

```python
/content/drive/MyDrive/CaneGuard_AI/data/pest_images/real

**Dataset Download:**
```python
!kaggle datasets download -d nirmalsankalana/sugarcane-leaf-disease-dataset

```
##colab link
project : https://colab.research.google.com/drive/1unAlXBZW5uxejI-A6Q2IysaD3bu2VvDV?usp=sharing
---
## 👩‍💻 Author

**Prerna** — Chandigarh University  
ANNAM.AI Course — IIT Ropar, 2026

---

## 📄 License
MIT License
