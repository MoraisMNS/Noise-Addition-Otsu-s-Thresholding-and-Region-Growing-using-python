# 📘 EC7212 – Computer Vision and Image Processing - Take Home 02

Welcome! This assignment contains two classic image segmentation techniques implemented in Python:

🔹 **Task 1:** Apply Otsu’s Thresholding after introducing Gaussian noise  
🔹 **Task 2:** Implement Region Growing using seed-based color segmentation

---

## 📁 Folder Contents

```
📦 Project Folder
├── image.png                    # Input image (required)
├── notebook.ipynb               # Python script with all functionality
└── README.md                    # This document
└── EC7212_4077_Assignment2.pdf  # Pdf file for detail of the Take Home Assignment - 02

```

---

## 🛠️ Setup Instructions

Install the required Python packages using pip:

```bash
pip install numpy opencv-python matplotlib
```

---

## 🚀 Running the Program

Ensure `image.png` is available in the folder. Then execute:

```bash
python notebook.ipynb
```

The script will display each step of the process, including plots for:

- Original and Noisy images
- Histogram of grayscale values
- Otsu thresholded binary result
- Region-growing mask and overlay

---

## 🧠 Assignment Breakdown

### 🔍 Part 1: Otsu Thresholding with Noise

- Load color image
- Add Gaussian noise per channel
- Convert to grayscale
- Compute Otsu's threshold (custom implementation)
- Segment and visualize binary output

### 🌱 Part 2: Region Growing Segmentation

- Define initial seed points
- Grow region based on color similarity (Euclidean distance)
- Generate binary mask and overlay result

---

## 🖼️ Outputs to Expect

| Visual | Description                  |
|--------|------------------------------|
| 📷     | Original input image         |
| 🎨     | Noisy version of image       |
| 📊     | Histogram of grayscale       |
| 🔲     | Otsu-based binary image      |
| 🌐     | Region-grown binary mask     |
| 🟥     | Overlay with red-highlighted region |

---

## 🔧 Customization

- ✅ Modify `seeds` to test different regions
- ✅ Adjust `tolerance` in region growing to widen or tighten segmentation
- ✅ Replace `image.png` with your own image

---

## ✍️ Notes

- Works best with clear foreground-background contrast
- Self-contained script, no additional files needed
- Suitable for academic and demo purposes

---

👨‍💻 Prepared for **EC7212 – Computer Vision and Image Processing - Take Home Assignment 02**

