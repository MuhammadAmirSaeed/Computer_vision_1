
Computer_vision_1

Course: Computer Vision
Name: Amir Saeed
Semester: 2
Registration Number: 08075512012


📌 Environment Setup
Required Libraries:
OpenCV (cv2)
NumPy (numpy)
Matplotlib (matplotlib)
🚀 Running on Google Colab
Open Google Colab.

Upload the provided .ipynb or .py file.

Upload your image to Colab storage (/content/your_image.jpg).

If you don’t have an image, you can generate one with the Synthetic Image Code provided in the notebook.
Update the image path in the code:

image = cv2.imread('/content/your_image.jpg')
Run all cells in sequence.

🖼️ Code Sections
The assignment is divided into 12 parts for clarity:

Load Image – Read and display input image.
Color Conversions – RGB → Gray, HSV.
Cropping – Select a region of the image.
Histogram – Compute & display histogram.
Histogram Equalization – Improve contrast.
CLAHE – Advanced local contrast enhancement.
Point Processing – Log transform & gamma correction.
Bit-plane Slicing – Show binary decomposition of image.
Filtering (Blurring) – Average, Gaussian, Median filters.
Sharpening – Enhance edges.
Edge Detection – Detect edges using Canny.
Morphological Ops – Erosion & Dilation.
📊 Outputs
The program displays multiple images including:

Original & processed images
Histograms before & after equalization
Transformed images (Log, Gamma)
Blurred & sharpened images
Edges and morphological results
Bit-plane slices
✅ Notes
Always run cells in sequence.
For best results, use a high-contrast photo.
All results will appear directly in the Colab output cells.
