# Panorama Image Stitching using OpenCV

## Project Overview

This project implements a simple **image stitching system** using Computer Vision techniques.
The goal is to combine two overlapping images and generate a **single panoramic image**.

This project is inspired by standard image stitching methods and has been **modified and implemented independently**.

---

## Objective

* To understand feature-based image stitching
* To apply concepts like feature detection, matching, and transformation
* To generate a seamless panoramic image from multiple inputs

---

## Technologies Used

* Python
* OpenCV
* NumPy

---

## Concepts Used

* SIFT (Scale Invariant Feature Transform)
* Feature Matching (KNN)
* RANSAC (Random Sample Consensus)
* Homography Matrix
* Image Warping and Blending

---

## Project Structure

```
├── panorama_generator.py
├── images/
│   ├── img1.jpg
│   ├── img2.jpg
├── README.md
```

---

## Installation & Setup

### Step 1: Clone Repository

```
git clone https://github.com/satwik068/CV-Project.git
cd CV-Project
```

## How to Run

Run the following command in terminal:

```
pip install -r requirements.txt
python panorama_generator.py images/q11.jpg images/q22.jpg
```

---

## Output

* Feature matching visualization
* Final stitched panoramic image

---

## Limitations

* Works best when images have sufficient overlap
* May fail for complex scenes or low-quality images
* Currently supports only 2 images

---

## Future Improvements

* Support multiple image stitching
* Improve blending quality
* Add GUI interface
* Use deep learning-based approaches

---

## Author

**Satwik Agrawal**
B.Tech Student

---

## Note

This project is developed for academic purposes.
The implementation is based on commonly used computer vision techniques and modified for learning.

---
