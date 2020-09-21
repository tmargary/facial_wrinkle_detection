# Facial Wrinkle Detection
Hero House AI Incubation Program

The script converts the image into grayscale, resizes the image, and detects the edges (wrinkles) on the person's face. Based on the number of edges, the program detects if the person has significant number of wrinkles. The optimal number of edges is found empirically.

Please refer to `find_wrinkles.ipynb` for visualizations.

### References
- Python Version: 3.8
- Packages: cv2, numpy, matplotlib
- https://docs.opencv.org/trunk/da/d22/tutorial_py_canny.html
- https://github.com/nishishah77
