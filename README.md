# 🩺 Medical Image Enhancement Using Histogram-Based Algorithms

This repository contains implementations of several histogram-based techniques to enhance the visual quality of grayscale medical images. These methods improve contrast, making features clearer for diagnostic purposes.

The project is based on the paper:
**"Medical Image Enhancement Based on Histogram Algorithms"**  
_Nema Salem, Hebatullah Malik, Asmaa Shams (2019) - Procedia Computer Science_  
[DOI: 10.1016/j.procs.2019.12.112](https://doi.org/10.1016/j.procs.2019.12.112)

---

## 📌 Motivation

Medical images such as X-rays, MRIs, and mammograms often lack adequate contrast due to various acquisition limitations. Enhancing these images using histogram-based techniques can:
- Improve visual perception for clinicians.
- Highlight critical details.
- Assist in accurate diagnosis.

---

## 🧪 Implemented Algorithms

The following four algorithms were implemented and tested:

1. **Histogram Equalization (HE)**  
   Enhances global contrast by spreading out the intensity distribution.

2. **Cumulative Histogram Equalization (CHE)**  
   Uses cumulative distribution to refine intensity scaling.

3. **Quadrant Dynamic Histogram Equalization (QDHE)**  
   Divides the image histogram into sub-histograms and applies equalization independently for better brightness preservation.

4. **Contrast Limited Adaptive Histogram Equalization (CLAHE)**  
   Applies localized contrast enhancement while preventing noise amplification by clipping histograms.

---

## 🖼️ Sample Medical Images

We tested the algorithms on fundus of eye grayscale medical images.

---

## 📊 Evaluation Metrics

Each algorithm is evaluated using three common metrics:

- **PSNR (Peak Signal-to-Noise Ratio)**:  
  Measures the ratio of signal power to the noise introduced by enhancement.

- **MSE (Mean Squared Error)**:  
  Indicates the average squared difference between the original and enhanced image.

- **Standard Deviation (SD)**:  
  Measures the spread of intensity values and helps quantify contrast.

---
