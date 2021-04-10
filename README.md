# Number Plate Recognition System
# INTRODUCTION
The project developed is used to extract the license number of vehicles from images. It is an embedded system which has numerous applications and challenges. The sole intention of this project is to find the most efficient way to recognize the registration information from the digital image (obtained from the camera). This process usually comprises of three steps. First step is the license plate localisation, regardless of the license plate size and orientation. The second step is the segmentation of the characters and the last step is the recognition of the characters from the license plate. It also helps us in noting the date and time the vehicle arrived. Thus this project uncovers the fundamental idea of various algorithms required to recognise the characters from the license plate using template matching.

# SOFTWARE USED
We have used Image Processing Toolbox with MATLAB to develop this system. The Image Processing Toolbox provides a comprehensive set of reference-standard algorithms and workflow apps for image processing, analysis, visualization, and algorithm development. We can perform image segmentation, image enhancement, noise reduction, geometric transformations, image registration, and 3D image processing using this toolbox.

# PROPOSED METHODOLOGY

In India, basically there are two kinds of license plates, black characters in white plate and black characters in yellow plate. The process of the proposed system is as follows.

LOAD RGB IMAGE
↓
GRAYSCALE CONVERSION
↓
BINARIZATION
↓
DILATION
↓
EDGE DETECTION
↓
PLATE REGION EXTRACTION
↓
CHARACTER SEGMENTATION
↓
TEMPLATE MATCHING
↓
OUTPUT STORED IN FILE

# ABOUT MATLAB

MATLAB (matrix laboratory) is a multi-paradigm numerical computing environment and proprietary programming language developed by MathWorks. MATLAB allows matrix manipulations, plotting of functions and data, implementation of algorithms, creation of user interfaces, and interfacing with programs written in other languages, including C, C++, C#, Java, Fortran and Python. 

Although MATLAB is intended primarily for numerical computing, an optional toolbox uses the MuPAD symbolic engine, allowing access to symbolic computing abilities. An additional package, Simulink, adds graphical multi-domain simulation and model-based design for dynamic and embedded systems. 

As of 2018, MATLAB has more than 3 million users worldwide.  MATLAB users come from various backgrounds of engineering, science, and economics.

# ASSUMPTIONS AND LIMITATIONS

1.	ASSUMPTIONS
•	Input is an image of a stationary Car.
•	Only the most common type of license plates (single line) will be dealt with for best results.
•	The license plate has a yellow or white background with text written in black.

2.	LIMITATIONS
•	If the image contains too much spoiled license plate or has designs on it, the program can fail to localize the license plate.
•	If the license plate happens to be much tilted from horizontal, then again the result of segmentation of the license plate is very poor.

# BIBLIOGRAPHY
Books:
International Journal of Computer Theory and Engineering, Vol. No. 2, 2 April, 2010.
Websites:
https://en.wikipedia.org/wiki/MATLAB
https://in.mathworks.com/products/matlab.html?s_tid=hp_products_matlab
