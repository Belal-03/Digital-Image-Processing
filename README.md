# 🖼️ Digital Image Processing – Assignments 1 & 2

This project includes two foundational assignments in digital image processing, focusing on pixel-level operations, image manipulation, and noise reduction. All tasks are performed on grayscale images using Python and image processing libraries.

---

## 📂 Assignment 1: Image Composition & Manipulation

### 📝 Task Overview

Work with two 256×256 grayscale images: **`LenaGray.jpg`** and **`PeppersGrey.jpg`**, where each pixel has 8-bit depth.

### 🔧 Tasks

#### ✅ a) Read and Display the Images
- Load and display both input images to verify their structure.

#### ✅ b) Create Composite Image J
- Define a new 256×256 image `J`:
  - Upper half (rows 0–127): from **LenaGray**
  - Lower half (rows 128–255): from **PeppersGrey**

#### ✅ c) Create Image K by Swapping Halves
- Define a new image `K` by swapping the upper and lower halves of image `J`.

### 📦 Deliverables
- Source code used to implement tasks.
- Output images:
  - Original Lena and Peppers
  - Combined image `J`
  - Swapped image `K`
- Screenshots or plots of each image as visual confirmation.

---

## 📂 Assignment 2: Image Enhancement & Noise Reduction

### 📝 Task Overview

Use the noisy images **`LenaGrayNoisy.jpg`** and **`PeppersGreyNoisy.jpg`**, which are 256×256 grayscale images corrupted by **salt and pepper noise**.

### 🔧 Tasks

#### ✅ i) Image Negative
- Implement the image negative operation by inverting grayscale pixel values:
  - `output_pixel = 255 - input_pixel`

#### ✅ ii) Grayscale Median Filter
- Apply a **3×3 median filter** to reduce salt and pepper noise.
- Handle edge effects by setting output pixels to **zero** when the filter window overlaps the border.

### 📦 Deliverables
- Source code for the negative transformation and median filtering.
- Output images:
  - Original noisy images
  - Results of the **negative transformation**
  - Results of the **median filter**
- A one-page PDF or markdown **discussion** comparing the effects of both operators.

---

## 🛠️ Tools & Libraries

| Tool / Library   | Usage                            |
|------------------|----------------------------------|
| `OpenCV` (`cv2`) | Image reading, processing, display |
| `NumPy`          | Array operations and manipulation |
| `Matplotlib`     | Display images in notebooks or scripts |
