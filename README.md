# Image Processing with Python

The goal of this example is to create an image dataset consisting of 50 handwritten images (10 images per character of the following 5 types "x", "o", "+", "-", "#"). These images will be read from the file system and processed with scikit-image ([https://scikit-image.org/](https://scikit-image.org/)). 

Processing steps include:

- Conversion to pixel matrix (numpy array)
- Scaling image to 10x10 pixels
- Apply threshold to grayscale image and create binary image from it

At the very end a CSV file is created holding the original filename of the image in column 1 and the pixel values of the processed image in column 2-101.