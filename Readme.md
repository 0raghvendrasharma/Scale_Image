# Image Resizing Project

This project contains a Python script that uses OpenCV to resize images.

## File: image.py

This script reads an image, resizes it by a specified percentage, and then writes the resized image to a new file.

### How it works

1. The script first imports the necessary module, `cv2` from OpenCV.

2. It then defines some configurable parameters:
   - `source`: The source image file (e.g., '4.1 (1).jpg').
   - `destination`: The output file where the resized image will be saved (e.g., 'newAlphaImage.png').
   - `scale_percent`: The percentage by which the image will be resized (e.g., 50).

3. The script reads the source image using `cv2.imread()` and stores it in `src`.

4. It calculates the new dimensions for the image based on the `scale_percent`.

5. It resizes the image using `cv2.resize()` and saves the resized image in `output`.

6. Finally, it writes the `output` image to the `destination` file using `cv2.imwrite()`.

### Usage

To use this script, simply modify the `source`, `destination`, and `scale_percent` variables as needed, then run the script.

## Dependencies

This script requires the OpenCV library. You can install it using pip:

```bash
pip install opencv-python