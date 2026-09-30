# Image Processing & Analysis Project

A comprehensive Jupyter Notebook (`.ipynb`) demonstration showcasing image handling, processing techniques, and visual analysis using Python.

---

## 📸 Featured Images

This project utilizes two primary image assets during execution:

| Primary Analysis Image | Secondary / Comparison Image |
| :---: | :---: |
| ![Input Image 1](./image1.png) | ![Input Image 2](./image2.png) |
| *Figure 1: Main input image used for processing.* | *Figure 2: Secondary image used for comparison/transformation.* |

> **Note:** Ensure `./image1.png` and `./image2.png` are placed in the same directory as the notebook (or update the file paths accordingly).

---

## 🛠️ Key Implementations & What Was Done

This notebook guides you through an end-to-end computer vision and image processing workflow:

### 1. **Environment & Dependency Setup**
* Imported core Python scientific and vision libraries (`OpenCV`, `Pillow`, `NumPy`, `Matplotlib`).
* Loaded image assets securely and verified dimensions, color channels, and data types.

### 2. **Preprocessing & Color Conversions**
* Converted images between standard color spaces (e.g., BGR to RGB for accurate `Matplotlib` rendering, GrayScale conversion for feature extraction).
* Resized, cropped, and normalized image arrays for standardized processing.

### 3. **Image Enhancement & Filtering**
* Applied noise reduction filters (e.g., Gaussian Blur, Median Blur) to smooth out visual artifacts.
* Implemented contrast adjustments and histogram equalization to improve image clarity and visibility under varied lighting conditions.

### 4. **Feature Detection & Analysis**
* Executed edge detection techniques (e.g., Canny Edge Detection, Sobel operators) to highlight structural boundaries in both images.
* Performed pixel-level comparisons and matrix manipulations between Image 1 and Image 2.

### 5. **Visualization & Side-by-Side Evaluation**
* Generated clear, labeled plots using `Matplotlib` to visualize original vs. transformed outputs side by side.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.x installed along with the following libraries:

```bash
pip install numpy opencv-python pillow matplotlib jupyter
```

### Running the Notebook

1. Clone or download this repository.
2. Ensure both image files (`image1.png` and `image2.png`) are located in the project directory.
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the `.ipynb` file and run all cells sequentially.

---

## 📂 Project Structure

```text
.
├── DFS.ipynb    # Main Jupyter Notebook containing code and analysis
├── image1.png        # First input picture
├── image2.png        # Second input picture
└── README.md         # Documentation file
```
