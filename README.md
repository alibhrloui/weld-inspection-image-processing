# Weld Inspection using Image Processing

This repository contains scripts for inspecting welds in images using image processing techniques. It provides functionalities for preprocessing images, detecting weld defects, and generating heatmap overlays for visualization.

## Overview

Weld inspection is a critical process in ensuring the structural integrity and quality of welded joints. Manual inspection methods can be time-consuming and subjective. Automated inspection using image processing techniques offers a faster and more consistent approach.

## Features

- **Image Preprocessing:** Enhance image quality using Unsharp Mask filter for better detection of weld defects.
- **Region of Interest (ROI) Extraction:** Extract specific regions of interest from the image for focused analysis.
- **Adaptive Thresholding:** Convert grayscale images to binary mode using adaptive thresholding to highlight weld defects.
- **Morphological Operations:** Apply erosion to reduce noise and refine defect detection.
- **Contour Detection:** Identify weld defects by detecting contours within the extracted regions.
- **Bounding Box Visualization:** Visualize detected defects by drawing bounding boxes on the original image.
- **Heatmap Generation:** Generate heatmap overlays to visualize defect severity and distribution.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/weld-inspection.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the scripts:

   - For weld defect detection:
     ```bash
     python weld_defect_detection.py
     ```

   - For generating heatmap overlays:
     ```bash
     python heatmap_generation.py
     ```

4. Follow the instructions provided within the scripts for loading images and adjusting parameters as needed.

## Results

The repository provides visualizations of the original images with detected weld defects overlaid, along with processed images showing enhanced clarity and heatmap overlays highlighting defect areas.

## Contribution

Contributions are welcome! If you have any ideas for improvements, feel free to open an issue or submit a pull request.
