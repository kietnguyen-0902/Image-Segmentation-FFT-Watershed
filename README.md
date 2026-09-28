# Image Segmentation using FFT & Watershed 🔬

An advanced computer vision pipeline built with Python, OpenCV, and NumPy to accurately count objects (e.g., cells, grains) from images degraded by periodic sinusoidal noise.

## 🚀 Core Pipeline
1. **Frequency Domain Filtering:** Applied 2D Fast Fourier Transform (FFT) and a custom Notch Filter to isolate and remove periodic noise frequencies.
2. **Illumination Correction:** Utilized Morphological Top-hat transform to balance uneven lighting conditions.
3. **Image Enhancement:** Contrast stretching and Gaussian blurring for noise suppression.
4. **Binarization:** Adaptive Gaussian Thresholding to effectively separate foreground from background.
5. **Segmentation & Counting:** Implemented the Watershed algorithm with Distance Transform to accurately separate clustered/touching objects and output the final count.

## 🛠️ Technologies Used
- Python 3
- OpenCV (cv2)
- NumPy
- Matplotlib

## 📂 Project Structure
- `main_pipeline.ipynb`: The complete executable Jupyter Notebook containing all processing steps and visualizations.
- `images/`: Directory containing sample images for testing. The notebook is configured to automatically download a sample if not available locally.
