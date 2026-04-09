# Image Analysis

Jupyter notebook for comparing two images across multiple quality dimensions: sharpness, luminance, color, and noise.

## Features

- SIFT-based image alignment or face-landmark alignment (dlib)
- Sharpness comparison via Laplacian variance
- Luminance and color difference analysis (LAB and RGB)
- Noise estimation via FFT frequency analysis
- Visual diff maps with highlighted regions

## Tech Stack

Python, OpenCV, dlib, scikit-image, NumPy, SciPy, Google Colab

## How to Run

Open `Image_comparison.ipynb` in [Google Colab](https://colab.research.google.com/), mount Google Drive with input images, and run all cells.
