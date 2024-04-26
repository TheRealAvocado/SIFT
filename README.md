# SIFT Processor
This is a Python application for performing Scale-Invariant Feature Transform (SIFT) on images. The application utilizes the PyQt5 library for the GUI interface and OpenCV for image processing tasks.
## Overview
The SIFT Processor Python application allows users to perform Scale-Invariant Feature Transform (SIFT) on images. It provides a graphical user interface (GUI) built with the PyQt5 library for easy interaction. The application implements OpenCV functions from scratch for image processing tasks, enabling features such as keypoint detection, descriptor computation, and image display.

Users can load an image using the GUI, and the application will apply the SIFT algorithm to detect keypoints and compute descriptors. These keypoints and descriptors are then displayed on the image, allowing users to visualize the detected features and their characteristics.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/<username>/<repository>.git
   
2. Install dependencies:
     ```bash
   pip install PyQt5 opencv-python numpy
   ```

3. Run code:
  ```bash
python ui.py
```
## Example Result

### SIFT Processor Result

![SIFT Processor Result](box.png)

#### Description

In the example result shown above, keypoints detected by the SIFT algorithm , and their descriptors are visualized using lines . This visualization helps users understand the distribution and characteristics of the detected features in the image.


