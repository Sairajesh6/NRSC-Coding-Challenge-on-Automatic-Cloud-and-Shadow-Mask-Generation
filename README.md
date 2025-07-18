# NRSC-Coding-Challenge-on-Automatic-Cloud-and-Shadow-Mask-Generation


This repository provides a Python implementation for efficiently processing large `.tif` satellite images (e.g., LISS-4 TOA scenes) to generate cloud/shadow labels, optimized for low memory usage.

## 🚀 Features

- Handles large `.tif` satellite images without memory overflow
- Uses `rasterio` for efficient TIF reading
- Implements morphological operations to clean and enhance masks
- Includes memory monitoring using `psutil`

---

## 📂 Input

- TOA-corrected `.tif` satellite imagery (e.g., from Resourcesat/LISS-4)

## 📤 Output

- Binary or grayscale cloud/shadow masks
- Optional visualizations of detection

---

## 🧪 Quick Start

### 1. Install Dependencies
```bash
pip install rasterio numpy matplotlib psutil scikit-image
