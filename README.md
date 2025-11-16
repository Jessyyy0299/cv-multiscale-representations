# Multiscale Image Representations (Computer Vision)

### ⭐ Project Highlights
- Implemented Gaussian scale space and multiscale smoothing from first principles  
- Constructed Gaussian and Laplacian pyramids with image downsampling  
- Reconstructed original images from pyramid levels and analyzed reconstruction accuracy  
- Applied Laplacian of Gaussian (LoG) for blob detection across scales  
- Visualized multiscale feature responses to understand scale invariance  


This repository contains a course assignment on **multiscale image representations** for the Yale Computer Vision class (CPSC 480/580).

> Author: **Jessy Xue**  
> Topic: Gaussian scale space, Laplacian of Gaussian, blob detection, Gaussian and Laplacian pyramids, and image reconstruction.

---

## 🧠 Overview

The assignment explores how to represent images at multiple scales and how these representations can be used for feature detection and reconstruction. The main ideas include:

- **Gaussian scale space**: progressively smoothing images with increasing σ  
- **Laplacian of Gaussian (LoG)** and **normalized LoG** for blob detection  
- **Blob detection** using `skimage.feature.blob_log`  
- **Gaussian pyramids** (subsampled multi-scale images)  
- **Laplacian pyramids** and  
- **Reconstruction** of images from Laplacian pyramid coefficients

All implementation and visualizations are documented in the attached PDF report.

---

## 📄 Files

- `cv_multiscale_assignment.pdf`  
  Course assignment report containing:
  - Code snippets (Python + skimage)
  - Figures of Gaussian and Laplacian scale spaces
  - Blob detection visualizations
  - Gaussian and Laplacian pyramid visualizations
  - Image reconstruction results

---

## 🛠 Techniques Demonstrated

- Gaussian filtering and scale space
- Laplacian of Gaussian and normalized LoG
- Blob detection across scales
- Construction of Gaussian and Laplacian pyramids
- Coarse-to-fine image reconstruction

