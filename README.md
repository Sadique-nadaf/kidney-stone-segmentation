# kidney-stone-segmentation
Simple kidney stone segmentation &amp; localization using OPENCV's basic operations.

### Project Description

This project focuses on detecting and segmenting kidney stones from medical images using computer vision techniques.

### Steps Involved:

- **Preprocessing:**
  - Crop the region of interest, convert to grayscale, and apply a median filter for noise reduction.
- **Image Enhancement:**
  - Smooth the image using a custom matrix, apply a top-hat filter for contrast enhancement, and binarize using Otsu's thresholding.
- **Morphological Operations:**
  - Perform erosion and dilation to refine the image.
- **Segmentation:**
  - Use watershed algorithm and k-means clustering to segment the kidney stones.
- **Post-processing:**
  - Create a binary mask from segmented regions and apply it to the original image.

### Technologies Used:

- **OpenCV:** For image processing tasks.
- **Matplotlib:** For image visualization.
