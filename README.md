# Assignment 4 – Introduction to Image Processing  
## Deep Learning for Computer Vision

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-4.x-green?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-Scientific_Computing-orange?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/SciPy-Signal_Processing-blueviolet?style=for-the-badge&logo=scipy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
</p>

---

## 📌 Overview

This repository contains my solution for **Lab 4** in the **Deep Learning for Computer Vision** course.  
The lab focuses on **fundamental image processing techniques**, implemented and analyzed using Python-based scientific computing libraries.

The goal of this assignment is to build a strong foundation in classical image processing before moving to convolutional neural networks (CNNs).

---

## 🧪 Topics Covered

- Image translation using affine transformation matrices
- Image rotation around the center with scaling
- Manual implementation of a **7×7 mean filter**
- Execution time measurement using `%%time`
- Performance comparison between:
  - Manual filtering
  - OpenCV (`filter2D`)
  - SciPy (`convolve2d`)
- Horizontal and vertical edge detection using derivative kernels
- Border handling and edge behavior analysis

---

## 🧠 Implemented Tasks

### 🔹 Q1: Image Translation
- Applied translation using a manually defined transformation matrix
- Analyzed how pixels outside image boundaries are handled

### 🔹 Q2: Image Rotation
- Rotation by **45°**
- Rotation by **−30° with scale = 0.8**
- Rotation performed around the image center

### 🔹 Q3: Manual Mean Filter
- Implemented a **manual 7×7 mean filter**
- Used nested loops (no built-in filtering functions)
- Measured execution time using `%%time`

### 🔹 Q4: Filter Comparison
- Applied the same 7×7 mean filter using:
  - Manual implementation
  - OpenCV `filter2D`
  - SciPy `convolve2d`
- Compared execution time and output images
- Analyzed differences in border regions

### 🔹 Q5: Edge Detection
- Applied **horizontal and vertical derivative kernels**
- Combined both edge responses
- Normalized output to the range **[0, 1]**
- Analyzed dominant edge directions in the image

---

## ⏱ Performance Analysis

- **Manual implementation** is the slowest due to nested Python loops
- **OpenCV** is the fastest due to optimized C/C++ backend
- **SciPy** offers intermediate performance and flexibility

These results highlight the importance of optimized libraries in real-world computer vision applications.

---

## 🛠 Tools & Technologies

- Python 3.10
- NumPy
- OpenCV
- SciPy
- Matplotlib
- Jupyter Notebook (Anaconda environment)

---

## 📂 Repository Structure
``` text
├── Assignment_4.ipynb
├── flower.jpg
├── walking.jpg
├── README.md
```
---

## ✍️ Author

**Ahmed Monir Almassri**  
Computer Engineering Student  
Entry - Level Data Engineer 🚀
