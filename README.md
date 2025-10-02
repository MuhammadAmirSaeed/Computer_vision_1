# Computer_vision_1


## 📌 Environment Setup


### Required Libraries:

* OpenCV (`cv2`)
* NumPy (`numpy`)
* Matplotlib (`matplotlib`)


## 🚀 Running on Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the provided `.ipynb` or `.py` file.
3. Upload your image to Colab storage (`/content/your_image.jpg`).

   * If you don’t have an image, you can generate one with the **Synthetic Image Code** provided in the notebook.
4. Update the image path in the code:

   ```python
   image = cv2.imread('/content/your_image.jpg')
   ```
5. Run all cells in sequence.

---

## 🖼️ Code Sections

The assignment is divided into **12 parts** for clarity:

1. **Load Image** – Read and display input image.
2. **Color Conversions** – RGB → Gray, HSV.
3. **Cropping** – Select a region of the image.
4. **Histogram** – Compute & display histogram.
5. **Histogram Equalization** – Improve contrast.
6. **CLAHE** – Advanced local contrast enhancement.
7. **Point Processing** – Log transform & gamma correction.
8. **Bit-plane Slicing** – Show binary decomposition of image.
9. **Filtering (Blurring)** – Average, Gaussian, Median filters.
10. **Sharpening** – Enhance edges.
11. **Edge Detection** – Detect edges using Canny.
12. **Morphological Ops** – Erosion & Dilation.

---

## 📊 Outputs

The program displays multiple images including:

* Original & processed images
* Histograms before & after equalization
* Transformed images (Log, Gamma)
* Blurred & sharpened images
* Edges and morphological results
* Bit-plane slices

---

## ✅ Notes

* Always run cells **in sequence**.
* For best results, use a **high-contrast photo**.
* All results will appear directly in the Colab output cells.

---

**End of README**
