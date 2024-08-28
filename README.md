# Bar Code Detector Using Classical Computer Vision Techniques

This repository contains a Python project that demonstrates how to detect barcodes in images using classical computer vision techniques. The project employs a combination of image thresholding, edge detection, and morphological operations to identify barcodes.

## Overview

Barcodes are prevalent in many industries for product identification and inventory management. Detecting them in images is a fundamental computer vision task. This project provides a step-by-step guide to implement a barcode detection pipeline using Python and OpenCV, showcasing various image processing techniques.

## Techniques Used

The project leverages the following classical computer vision techniques:

- **Image Thresholding**: Converts the image to a binary format to isolate the barcode from the background.
- **Edge Detection**: Identifies the edges within the image, which helps in highlighting the barcode's boundaries.
- **Morphological Operations**: Applies erosion and dilation to clean up the binary image and emphasize the barcode's structure.
- **Contour Detection**: Finds and draws contours around the barcode to mark its location within the image.
