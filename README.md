# Fake-Currency-Detection
This project identifies fake Indian currency notes using Image Processing. 

# Abstract
The advancement of color printing technology has increased the rate of fake currency note printing and 
duplicating the notes on a very large scale. A few years back, printing could be done in a print house, but 
now anyone can print a currency note with maximum accuracy using a simple laser printer. As a result, 
the issue of fake notes instead of genuine ones has decreased very largely. This leads to the design of a 
system that detects fake currency notes in less time and more efficiently. The proposed system 
gives an approach to verify the Indian currency notes. 
Verification of currency notes is done by image processing conceptsusing Deep Learning and Machine Learning algorithms.

# Requirement Analysis
Image processing library: OpenCV 
Language: Python 3.7
Code Editor: Visual Studio Code
Data Set: Kaggle(https://www.kaggle.com/)

# Implementation
1) IMAGE ACQUISITION
   The dataset of the Indian currency notes is extracted from Kaggle 
   
2) GRAYSCALE CONVERSION
    The acquired image is obtained as an RGB image which is now converted into a grayscale image 
    since it carries intensity information. Grayscaling is the process of converting an image from other 
    color spaces e.g. RGB. 

3) EDGE DETECTION
    Edge detection is an image processing technique for finding the boundaries of objects within 
    images. It works by detecting discontinuities in brightness.
    Algorithms used for edge detection include: 
    • CANNY EDGE DETECTION
    • SOBEL EDGE DETECTION
    • KRISCH EDGE DETECTION
    • GAUSSIAN FILTER
    • TOP HAT AND BLACK HAT
    • GABOR FILTER

4) IMAGE SEGMENTATION
    Image segmentation involves converting an image into a collection of regions of pixels that are 
    represented by a mask or a labeled image.
    
5) FEATURE EXTRACTION
    Features of currency notes like security thread, Identification mark, Bleed lines, and the signature 
    of the RBI Governor, were extracted.
   
6) FEATURE MATCHING
    Feature matching refers to the act of recognizing features of the same object across images with 
    slightly different viewpoints.
    FLANN is a library for performing fast approximate nearest neighbor searches in highdimensional spaces. It contains a collection of algorithms we found to work       best for the nearest neighbor search and a system for automatically choosing the best algorithm and optimum 
    parameters depending on the dataset. 



