# Hybrid Affine–Residual Deep Learning Framework for Tumor-Aware Multimodal Brain MRI Registration with NSGA-Based Loss Optimization.

## 📌 Overview
This project presents a hybrid deep learning framework for multimodal brain MRI registration integrating classical affine alignment with residual deformation learning using an enhanced 3D VoxelMorph architecture.

The method introduces tumor-aware spatial attention and automatic loss weight optimization using NSGA to improve pathological region alignment.

---

## 🧠 Dataset
**BraTS 2020 Dataset**

Modalities used:
- T1
- T2
- FLAIR
- T1CE (Fixed Reference)

Tumor segmentation masks are used for pathology-aware learning.

---

## ⚙️ Methodology

### 1. Preprocessing
- NIfTI MRI loading
- Intensity normalization
- Spatial resizing
- Dataset standardization

### 2. Hybrid Registration
- Mutual Information–based Affine Registration
- Dense Affine Flow Field Generation
- Residual Attention VoxelMorph Network

### 3. Tumor-Aware Learning
- Tumor mask guided spatial attention
- Pathology-focused feature learning

### 4. Multi-Modal Joint Registration
Simultaneous alignment of:
- T1
- T2
- FLAIR → T1CE reference

### 5. Multi-Objective Optimization
Loss functions:
- Image Similarity Loss
- Dice Loss
- Smoothness Loss

Optimized using:
**Non-Dominated Sorting Genetic Algorithm (NSGA)**

---

## 🚀 Key Contributions
- Hybrid Affine + Deep Residual Registration
- Tumor Mask–Guided Spatial Attention
- Unified Multimodal Registration Network
- Automatic Loss Weight Optimization using NSGA

---

## 🏗 Architecture
![Architecture](docs/architecture.png)

## ▶️ How to Run

### 1. Clone Repository
```bash
git clone https://github.com/<your-username>/Brain-MRI-Registration-NSGA.git

pip install -r requirements.txt

Results

The proposed hybrid framework improves tumor-region alignment and multimodal anatomical consistency.

Author

Balamurugan M
B.Tech – Information Technology
PSG College of Technology