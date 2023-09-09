# Citizenship Card Tampering Detection

This project utilizes Computer Vision to detect tampering of citizenship cards and determine whether a provided card is genuine or altered.

## Project Overview

1. **Purpose**: Detect tampering of Citizenship cards.
2. **Steps**:
    - Obtain user-provided images.
    - Verify image size and format.
    - Resize images to match the original dimensions.
    - Convert images to grayscale.
    - Calculate the Structural Similarity Index (SSIM).
    - Determine the image threshold.
    - Find contours to identify objects.
    - Display differences, thresholds, and original vs. tampered images.
    - Compare images to assess tampering.

## Required Packages

- `skimage.metrics.structural_similarity`
- `imutils`
- `cv2` (OpenCV)
- `Pillow` (PIL)
- `requests`
- `os`

## Directory Setup

- Create directories to store images.

## Image Acquisition

- Load original and tampered images from URLs.

## Image Resizing

- Resize images to a specified dimension.

## Image Processing and Detection

- Convert images to grayscale.
- Calculate SSIM to assess similarity.
- Calculate thresholds and identify contours.

## Result Interpretation

- Determine the similarity percentage to assess tampering.
