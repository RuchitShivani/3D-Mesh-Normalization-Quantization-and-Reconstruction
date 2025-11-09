# 🧩 3D Mesh Normalization, Quantization, and Reconstruction


This project implements a complete 3D mesh processing pipeline using Python and Google Colab.  
It demonstrates how to load, inspect, normalize, quantize, and reconstruct `.obj` meshes using **Trimesh**, **NumPy**, and **Open3D**, followed by quantitative error analysis.

---

## 📚 Table of Contents
1. [Overview](#overview)
2. [Environment Setup](#environment-setup)
3. [Dataset](#dataset)
4. [Tasks & Methodology](#tasks--methodology)
    - [Task 1: Load and Inspect the Mesh (20 Marks)](#task-1-load-and-inspect-the-mesh-20-marks)
    - [Task 2: Normalize and Quantize the Mesh (40 Marks)](#task-2-normalize-and-quantize-the-mesh-40-marks)
    - [Task 3: Reconstruction and Error Analysis (40 Marks)](#task-3-reconstruction-and-error-analysis-40-marks)
5. [Results](#results)
6. [Deliverables](#deliverables)
7. [References](#references)

---

## 🧠 Overview
The objective of this assignment is to understand how **3D mesh geometry** can be numerically represented, transformed, and reconstructed.  
We explore:
- Mesh data loading and statistical analysis  
- Two normalization methods: **Min–Max** and **Unit Sphere**  
- Quantization and dequantization using fixed bins  
- Reconstruction quality analysis through **MSE** and **MAE** metrics  
- Visualization of normalized, quantized, and reconstructed meshes  

All experiments were performed in **Google Colab** (CPU only).

---

## ⚙️ Environment Setup

Run the following in a Colab cell:

```bash
!pip install trimesh open3d numpy matplotlib
